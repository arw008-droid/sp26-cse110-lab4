# Part 2 Answers
1. Line 12 will print prices.length - 1 because i is declared using var, so it will still be in scope even after the loop ends. 
2. Line 13 will print the final discountedPrice calculated in the final iteration of the loop because it is declared using var, so it will still be in scope even after the loop ends. 
3. Line 14 will print the final finalPrice calculated in the final iteration of the loop because it is declared using var, so it will still be in scope even after the loop ends. 
4. This function will return an array of the finalPrice calculated in every iteration of the loop because the array is declared within function scope, so its values will be returned.
5. Line 12 will give an error because it calls i, which only exists within the scope of the for loop, which is out of scope by line 12. 
6. Line 13 will give an error because it calls discountedPrice, which only exists within the scope of the for loop, which is out of scope by line 13. 
7. Line 14 will print the final finalPrice calculated in the final iteration of the loop because it is declared within the scope of the function block, so it will still be in scope even after the loop ends. 
8. This function will return an array of the finalPrice calculated in every iteration of the loop because the array is declared within the scope of the function block, so its values will be returned at the end.
9. Line 11 will give an error because it calls i, which only exists within the scope of the for loop, which is out of scope by line 11. 
10. Line 12 will print prices.length because length is declared as a const, so its value is constant from declaration all the way through line 12. 
11. This function will return the array of finalPrice calculated in each iteration of the loop because the array is declared within the scope of the function block, so it will sitll be in scope even after the loop ends and that's what the function will return. 
12. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. 
    a. '32'
    b. 1
    c. 3
    d. '3null'
    e. 4
    f. 0
    g. '3undefined'
    h. NaN
14. 
    a. True
    b. False
    c. True
    d. False
    e. False
    f. True
15. The == operator only compares between the values after the two values are coerced, but the === operator will check the types of the values and the values itself without any coercion. 
16. In part2-question16.js
17. The modifyArray call will pass the array and the function into the code for the modifyArray function. Inside the function, a new array where each value is double the value of the array passed into the modifyArray function. 
18. in part2-question18.js
19. 1
    4
    3
    2