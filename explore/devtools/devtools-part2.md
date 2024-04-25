1. The bug is that result is of type string, since num1 and num2 are also both strings. Therefore, result adds two strings instead of two numbers.
2. To fix this I would convert num1 and num2 to be integers when calculating result in the calculateSum() function.
