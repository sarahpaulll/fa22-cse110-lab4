1. At line 12 it will print 3 because the variable i will be equal to 3 since it will be incremented three times (since the length of prices is three)
2. At line 13 it will print 150 since every time the loop runs discountedPrice is reassigned. The last price in prices is 300, so when the for loop ends the discountedPrice is 300 * (1 - 0.5) = 150.
3. At line 14 it will print 150 since every time the loop runs finalPrice is reassigned. During the last loop discountedPrice is 150, thus making finalPrice also 150.
4. The function will return the variable discounted which is represented by [50, 100, 150] since when you call the function with the parameters prices = [100, 200, 300] and discount = 0.5, the function calculates the discounted prices for each input in the array and then pushes it into the array discounted which will then be later returned.
5. There will be an error at line 12, since the variable i is declared with let it will not be accessible after the code block, thus on line 12 when it calls i, i will not be defined.
6. There will be an error at line 13, since the variable discountedPrice is declared with let it will not be accessible after the code block. Thus, on line 13 when it calls discountedPrice, discountedPrice will not be defined.
7. On line 14 it will print 150 to the console, since finalPrice is declared with let it can be reassigned in the for loop. During the last iteration of the loop the finalPrice is set equal to 150. Since finalPrice is declared in the same codeblock as line 14 it can be successfully called in console.log(finalPrice).
8. The function will return the variable discounted which is represented by [50, 100, 150] since when you call the function with the parameters prices = [100, 200, 300] and discount = 0.5, the function calculates the discounted prices for each input in the array and then pushes it into the array discounted which will then be later returned.
9. At line 11 it will have an error that i is not defined since i is declared using let it will not be accessible outside of the code block.
10. At line 12 it will print to the console 3 since the constant variable length is equal to 3.
11. The function will return the array discounted which is [50, 100, 150] since in the first iteration of the loop discountedPrice = 50 and this is pushed into the array discounted, on the second iteration discountedPrice = 100 and this is pushed into the array discounted, and on the last iteration discountedPrice = 150 and this is pushed into the array discounted.
12. 
    - A: student.name
    - B: student['Grad Year']
    - C: student.greeting()
    - D: student['Favorite Teacher'].name
    - E: student.courseLoad[0]
13. Arithmetic
    - A: '3' + 2 = '32' since integers map to their exact string representation
    - B: '3' - 2 = 1 since strings are converted to numbers
    - C: 3 + null = 3 since null becomes 0 for numeric conversion
    - D: '3' + null = '3null' since null maps to a string 'null'
    - E: true + 3 = 4 since true maps to 1 
    - F: false + null = 0 since false maps to 0 and null maps to 0
    - G: '3' + undefined = '3undefined' since undefined maps to a string 'undefined'
    - H: '3' - undefined = NaN since undefined maps to NaN for numeric conversion
14. Comparison
    - A: '2' > 1 = true since the strings are converted to a number
    - B: '2' < '12' = false since the strings are converted to a number
    - C: 2 =='2' = true since the strings are converted to a number
    - D: 2 === '2' = false because === checks the equality without type conversion
    - E: true == 2 = false since true is mapped to 1 for numeric conversion
    - F: true === Boolean(2) = true because === checks for equality without type conversion and Boolean(2) = True
15. The === operator checks for equality without type conversion, while the == operator checks for equality with type conversion. Thus with the === operator if a and b are different types then a === b returns false without trying to convert them.
17. The result is [2,4,6] since in each iteration of the for loop the newArr pushes a value that is returned from the function doSomething, which multiples the number in the parameter array by 2.
18. 
