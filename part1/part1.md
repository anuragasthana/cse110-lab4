# Part 1 Questions
1. The console will log the value of i at the completed loop because var allows the value of i to exist outside of the loop
2. The console will log the value of discountedPrice that was assigned last by the loop because var allows the value of discountedPrice to exist outside of the loop and it will continue to be reassgined by the loop until the loop is completed.
3. The console will log the value of finalPrice that was set last by the loop because finalPrice continues to be reassigned by the loop until it is complete.
4. The function will return [50,100,150]. The loop will essentially take each value in prices, multiply them by (1-0.5), round them (is not necessary in this case because the nuumbers divide evenly), and put them in the discounted which is the array that is returned after all other functions are completed.
5. A ReferenceError will be thrown because i is a let variable and thus is only available in the scope of the loop.
6. A ReferenceError will be thrown because discountedPrice is a let variable and thus is only available in the scope of the loop.
7. The console will log the value of finalPrice that was set last by the loop because finalPrice was defined outside of the loop and can be accessed by the log statement as they are in the same scope.
8. The function will return [50,100,150]. Assuming there are no statements that would cause an error, this array would be returned because the discounted array is defined in the same scope as the return statement. The loop will essentially take each value in prices, multiply them by (1-0.5), round them (is not necessary in this case because the nuumbers divide evenly), and put them in the discounted which is the array that is returned after all other functions are completed.
9. A ReferenceError will be thrown because i is a let variable and thus is only available in the scope of the loop.
10. An error would be thrown because discountedPrice is defined in the loop  and thus is only available in the scope of the loop.
11. Assuming there are no previous statements that throw errors, the console will print 0 because finalPrice is a const that was set to 0 and thus cannot be changed.
12. Assuming there are no previous statements that throw errors, the console will print an empty array because discounted is a const array that was initially empty and thus cannot be set again.
13.   
    1. student.name
    2. student["Grad Year"]
    3. student.call(greeting)
    4. student["Favorite Teacher"].name
    5. student.courseLoad[0]
14.   
    1.  '32', the string '3' concatenated with the number 2.
    2.  1, the string '3' turned into a number because of the subtraction sign and 3 - 2 resulted in 1.
    3.  3, 3 was added to null which took on a value of 0.
    4.  '3null', the string '3' concatenated with null, which turned into a string.
    5.  4, true took on a value of 1 and added to 3 to result in 4.
    6.  0, false took on a value of 0 and null took on a value of 0 and both added to 0.
    7.  '3undefined', the string "3" concatenated with undefined.
    8.  NaN, undefined is not a number so substracting that from "3" resulted in a number that does not exist.
15. 
    1.  true, '2' gets converted from a string to a number and is greater than 1
    2.  true, '2' and '12' get converted into numbers and 2 is less than 12
    3.  true, the number 2 and the string '2' have the same value
    4.  false, the number 2 and the string '2' may have the same value but they are not the same type
    5.  false, true has a value of 1 and 1 is not equal to 2
    6.  true, the number 2 is evaluated as a boolean and is true, returns true when compared to true
16. == compares the values of the experssions on either of its sides while === compares the values and types of the expressions on either of its sides.
17. "How are you?" is printed because in the first if statement, 2 == true evaluates to 2 == 1 which is not true and the next if statement is reached. 2 is evaluated as a boolean expression. Since it is not equal to 0, the second log statement is printed. Since this is part of an else if block, the code snippet stops there.
18. part1-question18.js
19. An empty array would be returned because newArr is a const array and was initially defined to be empty.
20. part1-question20.js
21. 1
    4
    3
    2