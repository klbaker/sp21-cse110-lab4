## Part 1A  
1. values added:  20
2. final result:  20
3. values added:  20
4. Line 13 causes a ReferenceError because result is only defined within the sumValues code block since let is used.
5. Line 9 causes a TypeError because result is a constant, but line 9 is attempting to reassign/modify its value
6. After commenting out line 9, line 13 causes a ReferenceError because result is only defined within the sumValues code block since const is used.

## Part 1B  
1. 3 is printed because i is defined using var so it is a global variable, meaning it exists everywhere
2. 150 is printed because it is also a global variable (exists beyond the for loop block) and 150 is the last value that it was assigned to
3. 150 is printed because it is also a global variable (exists within and outside of the for loop) and 150 is the last variable it was assigned to
4. [50, 100, 150] becuase discounted is defined using var meaning that it exists and is accessible in all parts of the code and it is modified in the for loop
5. This causes a ReferenceError becuase i is not defined outside of the for loop block since let is used.
6. This causes a ReferenceError becuase discountedPrice is not defined outside of the for loop block since let is used.
7. 150 is printed because finalPrice is defined at the top of the discountPrices code block so it is accessible throughout this function and 150 is the last value it was assigned to
8. [50, 100, 150] because discounted is defined at the top of the discountPrices code block so it is accessible thrughout this function and it is modified in the for loop
9. This causes a ReferenceError because i is defined using let so it only exists within the for loop code block but line 11 is outside of this block
10. 3 is printed becuase length exists throughout the discountPrices block and it has not been reassigned
11. [50, 100, 150] because discounted is defined as a const but only the values inside the array are changed but it still refers to the same array
12. below:
    1.  student\['name'\];
    2.  student\['Grad Year'\];
    3.  student.greeting();
    4.  student\['Favorite Teacher'\];
    5.  student\['Favorite Teacher'\]\['name'\]
    6.  console.log(student\['courseLoad'\]\[0\]);
13. Arithmetic
    1.  '32' becuase integers map to string representation
    2.  1 because numeric coversion occurs due to the mathematical function
    3.  3 becuase null becomes 0 (numeric conversion)
    4.  '3null' becuase null is converted to the string null
    5.  4 becuase after numeric conversion, true becomes 1
    6.  0 becuase after numeric conversion, both become 0
    7.  '3undefined' becuase null is converted to the string null since '3' is a string
    8.  NaN because you can't do substraction with strings
14. Comparison
    1.  true because '2' is converted to a number
    2.  false because 2 is later alphabetically and they are both strings
    3.  true because the string '2' is converted to a number
    4.  false because the 2 are not equivalent without conversion
    5.  false because false converts to the number 1
    6.  true becuase 2 is not 0, null, or empty
15. == is used to determine equality using conversions, but === is the strict equality operator and checks equality without using conversions
16. JS file
17. The function called in line 13 returns the array \[2, 4, 6\] because the for loop iterates 3 times (0, 1, 2) each time line 4 doubles that value at that index in array and pushes it into newArr.
18. JS file
19. Output:
    > 1  
    > 4  
    > 3  
    > 2
