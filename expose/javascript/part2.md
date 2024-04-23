1. At line 12 it will print 3 because the variable i will be equal to 3 since it will be incremented three times (since the length of prices is three)
2. At line 13 it will print 150 since every time the loop runs discountedPrice is reassigned. The last price in prices is 300, so when the for loop ends the discountedPrice is 300 * (1 - 0.5) = 150.
3. At line 14 it will print 150 since every time the loop runs finalPrice is reassigned. During the last loop discountedPrice is 150, thus making finalPrice also 150.
4. The function will return the variable discounted which is represented by [50, 100, 150] since when you call the function with the parameters prices = [100, 200, 300] and discount = 0.5, the function calculates the discounted prices for each input in the array and then pushes it into the array discounted which will then be later returned.
5. There will be an error at line 12, since the variable i is declared with let it will not be accessible after the code block, thus on line 12 when it calls i, i will not be defined.
6. There will be an error at line 13, since the variable discountedPrice is declared with let it will not be accessible after the code block. Thus, on line 13 when it calls discountedPrice, discountedPrice will not be defined.
7. On line 14 it will print 150 to the console, since finalPrice is declared with let it can be reassigned in the for loop. During the last iteration of the loop the finalPrice is set equal to 150. Since finalPrice is declared in the same codeblock as line 14 it can be successfully called in console.log(finalPrice).
8. 
