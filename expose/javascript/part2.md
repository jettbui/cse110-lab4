# expose/javascript - Part 2

1. It would print the final value of `i` after iteration (which is `3`) since `i` is scoped throughout the entire function by `var`.
2. It would print the value of `discountedPrice` from the last iteration (which is `150`) since `discountedPrice` is scoped throughout the entire function by `var`.
3. It would print the value of `finalPrice` from the last iteration (which is `150`) since `finalPrice` is scoped throughout the entire function by `var`.
4. The function returns an array corresponding to `prices` after applying the given discount to each of the element in `prices`. The result is `[50, 100, 150]`.
5. It would give a ReferenceError since `i` is no longer defined outside of the for-loop.
6. It would give a ReferenceError since `discountedPrice` is no longer defined outside of the for-loop.
7. It would print the value of `finalPrice` from the last iteration (which is `150`) since `finalPrice` is scoped throughout the function block by `let`.
8. The function still returns `[50, 100, 150]` as it behaves similarly as described in question 4.
9. It would give a ReferenceError since `i` is no longer defined outside of the for-loop.
10. It would print the value of `length` defined on line 4 (which is `3`).
11. The function still returns `[50, 100, 150]` as it behaves similarly as described in question 4.
12. Answers to Question 12
    1. `student.name`
    2. `student['Grad Year']`
    3. `student.greeting()`
    4. `student['Favorite Teacher'].name`
    5. `student.courseLoad[0]`
13. Answers to Question 13
    1. `'32'` since the `+` operator performs string concatenation after automatically converting `2` to a string
    2. `1` since the `-` operator performs integer subtraction after automatically converting `'3'` to an integer
    3. `3` since the numeric value of `null` is `0`
    4. `3null` since concatenation with `null` is interpreted as `'null'`
    5. `4` since the numeric value of `true` is `1`
    6. `0` since the numeric value of both `false` and `null` is `0`
    7. `'3undefined'` since the `+` operator performs string concatenation with `undefined` interpreted as `'undefined'`
    8. `NaN` since the `-` operator performs integer subtraction but `undefined` is `NaN`
14. Answers to Question 14
    1. `true` since it converts the types of the operands to be the same
    2. `false` since it performs a string comparison and not a numeric comparison
    3. `true` since the elements are equal with type conversion
    4. `false` since the elements are not the same type
    5. `false` since the numeric value of `true` is `1`
    6. `true` since `Boolean(2)` is converted to `true`
15. Both `==` and `===` perform equality comparison between two elements. However, `===` also ensures that the data types of the two elements are the same. `==` may return true if the elements are equal after conversion.
16. See [part2-question16.js](part2-question16.js).
17. The function will return `[2, 4, 6]` as `modifyArray` iterates through each element in the given `array`, passing each element into `callback` which is given to be `doSomething`; `doSomething` multiplies the element by 2.
18. See [part2-question18.js](part2-question18.js).
19. The output is `1`, `4`, `3`, `2`.
