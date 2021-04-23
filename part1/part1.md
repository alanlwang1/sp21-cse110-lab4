## Part 1a

    1. values added: 20
    2. final result: 20
    3. values added: 20
    4. Returns an error (variable result is out of scope)
    5. Returns an error (const result cannot be reassigned)
    6. Returns an error (const result cannot be reassigned)

## Part 1b

    1. The function will print the value of i (3) because i is declared with var and has function scope. At the end of the for loop, i will contain the length of prices[] = 3. 
    2. The function will print the value of discountedPrice (150) because it is declared with var and has function scope. At the end of the for loop, discountedPrice will contain the discounted price of the last item in prices[], which is 300 * 0.5 = 150. 
    3. The function will print the value of finalPrice (150) because it is declared with var and has function scope. At the end of the for loop, finalPrice will contain the final price of the last item in prices[], which is (300 * 0.5) * 100/100 = 150. 
    4. This function will return the array [50, 100, 150] because the function loops through all values in prices = [100, 200, 300] and applies the discount=0.5 to these values. 
    5. The function will return an error because the variable i is declared with let and is out of scope when the for loop is exited. 
    6. The function returns and error because the variable discountedPrice is declared with let and is out of scope when the for loop is exited. 
    7. The function will print the value of finalPrice (150) because it is declared with let outside of the for loop. At the end of the for loop, finalPrice will contain the final price of the last item in prices[], which is (300 * 0.5) * 100/100 = 150. 
    8. This function will return the array [50, 100, 150] because the function loops through all values in prices = [100, 200, 300] and applies the discount=0.5 to these values. 
    9. This function will return an error because discountedPrice is declared as a constant. After the first iteration of the for loop, the function will attempt to modify the value of discountedPrice after it is assigned, which causes the error. 
    10. This function will return an error because discountedPrice is declared as a constant. After the first iteration of the for loop, the function will attempt to modify the value of discountedPrice after it is assigned, which causes the error. 
    11.  This function will return an error because discountedPrice is declared as a constant. After the first iteration of the for loop, the function will attempt to modify the value of discountedPrice after it is assigned, which causes the error. 
   
    12A. student.name
    12B. student['Grad Year']
    12C. student.greeting()
    12D. student['Favorite Teacher'].name
    12E. student.courseLoad[0]

    13A. '32'  (2 maps to '2' and '3' is a string)
    13B. 1 ('3' maps to 3 and - is an integer operation)
    13C. 3 (null maps to 0 and 3 is an integer)
    13D. '3null' (null maps to 'null' and '3' is a string)
    13E. 4 (true maps to 1 and 3 is an integer)
    13F. 0 (false and null both map to 0)
    13G. '3undefined' (undefined maps to 'undefined' and 3 is a string) 
    13H. NaN (undefined maps to NaN and - is an integer operation)

    14A. true ('2' maps to 2)
    14B. false ('2' comes after '12' in string order)
    14C. true ('2' maps to 2)
    14D. false ('2' and 2 are different types)
    14E. false (true maps to 1)
    14F. true (Boolean(2) = true)

    15. == converts its operands to numbers if they are of different types before comparison, while === compares operands without conversion. 

    16. See part1b-question16.js
    17. The function will return the array [2, 4, 6]. This is because the function modifyArray() will call the function doSomething() for all elements the array, which will multiply each of these elements by 2. The loop then pushes these values to newArr, which gets returned. 
    18. See part1b-question18.js
    19. 1
        4
        3
        2
     