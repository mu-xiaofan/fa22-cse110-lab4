# Lab 4 part 2

1. Line 12 will print out the value stored in variable i, which is 3 in this case. i is the iterator that is used to iterate through array prices, which has a length of 3 according to line 19.
2. Line 13 will print out the value stored in variable discountedPrice, which is 150. At the third iteration, prices[i] returns the third element of the array, which is 300. And according to line 7, 300*(1-0.5) = 150.
3. Line 14 will print out the value stored in variable finalPrice, which is 150. The variable finalPrice was calculated on line 8. from the previous question we know that discountedPrice is 150 at the third iteration. So based on how the finalPrice is calculated, we get 150*100/100 = 150 because 150 is already rounded.
4. This function will return an array [50,100,150] because we created a variable discounted on line 3. Each time after we calculated the finalPrice, we push it into this array before the next iteration begins. So in the end the array discounted will be filled with the list of the result from our calculation for finalPrice based on the argument prices [100,200,300] and discount 0.5
5. This will cause an error because i was declared with datatype let, which can not be accessed outside the block.
6. This will cause an error because discountedPrice was declared with datatype let, which can not be accessed outside the block.
7. Line 14 will print the value inside finalPrice because finalPrice was declared with datatype let and was inside the same scope with line 14.
8. This function will return the array discounted with [50,100,150]. Although discounted is an array declared with datatype let, it is in the same scope with line 16, where it gets returned.
9. Line 11 will cause an error because variable i was declared using datatype let and it is in a for block that is not in a same scope of line 11. So it is not accessable outside this for block.
10. Line 12 will print the value inside the variable length because length was declared with prices.length and it was a constant and it was never being reassigned.
11. This function will return an array [50,100,150] because it stores the values that we calculated for discounted price and store it into an array before the next iteration begins.
12. - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad[0]
13. - A. '32' because the integer 2 was converted automatically and added as a string.
    - B. 1 because subtraction indecates it will be converted into integer while + did the opposite.
    - C. 3 because null will be converted into 0 for addition.
    - D. '3null' because null will be converted into string.
    - E. 4 because true has a value of 1 by default.
    - F. 0 because both false and null has a value of 0 by default.
    - G. '3undefined' because undefined will be converted into string by addition.
    - H. NaN because although 3 will be converted into integer by addition, subtract undefined will return NaN.
14. - A. True because string 2 will be converted into integer for comparison.
    - B. False because it compares 1 and 2.
    - C. True because string '2' will be converted into integer.
    - D. False because they are not strictly eaqual to each other.
    - E. False because true is 1 by default and 1 is not equal to 2.
    - F. True because Boolean(2) is true.
15. == returns true as long as those two have the same value after datatype conversion. === doesn't allow datatype conversion.
16. See part2-question16.js
17. The result will be [2,4,6]. The doSomething function doubles the value passed in and in modifyArray modifys the actual array using a for loop.
18. See part2-question18.js
19. 1
    4
    3
    2