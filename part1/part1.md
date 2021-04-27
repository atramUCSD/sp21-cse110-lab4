### 1a

1. values added:  20
2. final result:  20
3. values added:  20
4. ReferenceError: result is not defined. This is due to the let variable being unaccessable as it only exists in the scope of where it was declared.
5. TypeError: Assignment to constant variable. A const in JS can not be re-assigned or re-declared
6. ReferenceError: result is not defined. const gives the same scope as let, so the result value is unaccessable at that point of the code block. 

### 1b

1. 3
2. 150
3. 150
4. [ 50, 100, 150]. The discountPrices function applies the discount to the input via the for loop. Then returns the resulting values in a list named discounted. 
5. ReferenceError: i is not defined. We called let i, hence i will only exist in the scope of the loop code block. The console.log(i) outside the block cannot access i.
6. ReferenceError: discountedPrice is not defined. We called let discountedPrice, hence it will only exist in the scope of the loop code block. The console.log(discountedPrice) outside the block cannot access it per let variable rules
7. 150
8. [50,100,150]. Reason why we are able to get a return value here is because the let var discounted defined at the beginning of the function is still within the scope of the return statement. If we were to initialize discounted within the for loop using let, then we'd arrive at a ReferenceError. 
9. Reference Error: i is not defined. This error is due to initializing i as a let variable, hence it's only accessible within the for loop block.
10. Returned 3. Length id defined in the scope of the print statement, and the value of length was not altered at any point of the execution. 
11. [ 50, 100, 150 ]. The function was able to return properly as discounted does not have let and const properties that restrain its scope.


#### Data types

12a. student.name 
12b. student["Grad Year"]
12c. student.greeting();
12d. student["Favorite Teacher"].name
12e. student.courseLoad[0]


#### Arithmetic
13a. 32. This is because strings map to their exact string representation. String concatenation is done with + in JS.
13b. 1. This is because we cannot perform subtraction on strings, so JS converts the string to a number. 
13c. 3. null converts to 0 in arithmetic operations.
13d. 3null. The + sign with a string value results in concatenation. 
13e. 4 . True is turned to its integer representation (1) and then added onto 3. 
13f. 0 . False is turned to its integer representation (0) and then added onto null which is also 0. 
13g. 3undefined. The + sign with a string value results in the concatenation of string '3' and undefined.
13h. NaN. Subtraction cannot be done with a string so it is converted to an integer. Undefined is not a number (NaN), so the output results in NaN.

#### Comparison
14a. true. 2 is converted to it's integer value by nature of JS and compared with 1.
14b. false. 2 and 12 are converted to their integer values by nature of JS and compared.
14c. true. '2' is converted to its integer value and equates to 2.
14d. false. === is a strict equality operator and checks the equality without type conversion. Hence a string and int do not equate. 
14e. false. true is compared to 2 as it's integer equivalent (1). 1 != 2 hence false
14f. true. Since the value is not: 0, -0, null, false, NaN, undefined, or an empty string within the boolean function; true === true is the comparison being made. Hence true. Thery also match in data types.


#### == and === difference
15. The difference between == and === is that, == allows for data type conversion when making a comparison. === is strict equality operator and checks the equality without type conversion.

#### Functions
17. The result is [2,4,6] from the given input. Essentailly the values of the array are multiplied by 2 via the callback implementation. The doSomething function essentially runs right after the first function finishes, hence the change in numeric values in the array. 


19. 1 
    4
    3
    2


