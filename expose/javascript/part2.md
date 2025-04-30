1. 3 will be printed because the for loop ends when i is not less than the length of the prices list, which is 3. Thus, the for loop terminates when i is equal to 3. Because var is used to declare i, it can be accessed throughout the function, meaning that it is still accessible at line 12.
2. 150 will be printed because the last iteration of the for loop is when i equals 2. Thus, discountedPrice would equal 150 in the last iteration. Since var is used to declare discountedPrice, it is still accessible at line 13.
3. 150 will be printed because in the last iteration of the for loop, discountedPrice equals 150. Thus, finalPrice would equal 150 in the last iteration. Since var is used to declare finalPrice, it is still accessible at line 14.
4. This function will return [50, 100, 150] since the finalPrice for each iteration is stored in the discounted list.
5. This code will cause an error because i is declared using let, meaning that it is unable to be used outside of the for loop. Thus, the variable i does not exist in the scope of line 12.
6. This code will cause an error because discountedPrice is declared using let, meaning that it is unable to be used outside of the for loop. Thus, the variable discountedPrice does not exist in the scope of line 13.
7. 150 will be returned because the final iteration of the for loop will update finalPrice to be 150. Since the variable is declared outside of the for loop inside the function, it can be accessed at line 14.
8. This function will return [50, 100, 150] since the discountedList is updated during each iteration of the for loop. This is because discountedList can be accessed anywhere within the function because it is defined in the beginning of the function outside of the for loop. Thus, it can still be accessed at line 16.
9. This code will cause an error because i is declared using let, meaning that it is unable to be used outside of the for loop. Thus, the variable i does not exist in the scope of line 12.
10. 3 will be printed out because the constant variable is declared and initialized with the length of the price list, which is 3. Since it is declared in the beginning of the function outside of the for loop, it can be accessed at line 12.
11. The code will cause an error, because discounted cannot be reassigned in the for loop. This is because discounted is a constant variable, meaning that its value cannot be changed. Thus, the return statement will not work and the code will have errors.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. '32'
    B. 1
    C. 3
    D. '3null'
    E. 4
    F. 0
    G. '3undefined'
    H. NaN
14. A. true
    B. false
    C. true
    D. false
    E. false
    F. true
15. The == operator compares the two values with type conversions, while the === operator is a strict comparison, meaning that there the values are compared without type conversions.
16. JavaScript file
17. The result will be [2, 4, 6] because the for loop iterates over each entry of the array that is given as a parameter. In each loop, the return value of the doSomething function is added to the newArr array. The doSomething function returns the array value multiplied by 2, so each entry in newArr is double the entry in array. Thus, the result will be [2, 4, 6].
18. JavaScript file
19. The output will be the following because setTimeout does not pause code execution. This means that while 2 is waiting to be printed, the other 2 lines run, causing 3 and 4 to be printed.
    1
    3
    4
    2
