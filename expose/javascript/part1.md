# Part 1 Answers

1. Line 9 will print 20.
2. Line 13 will print 20. 
3. You shouldn't use var because it leads to odd behavior on line 13, allowing line 13 to work even though the variable exists inside a function that line 13 is not a part of. 
4. Line 9 will print 20. 
5. Line 13 will return an error because it is using a variable from within a function, so that variable is not usable for line 13. 
6. Line 9 will give an error because it tries to reassign the constant after initialization. 
7. Line 13 will give an error because it tries to call the result constant outside of the variable's scope.