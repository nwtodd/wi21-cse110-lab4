
# Part 1

1) i will get printed with the value prices.length since var has function scope
2) discountedPrice will have the value of the most recent iteration of the for loop, so when i = prices.length - 1. So discountedPrice = prices[prices.length -1] * (1 - discount). This is also due to var has function scope.
3) finalPrice will have the value that finalPrice held since var has function scope.
4) It would return [50, 100, 150] since effectively the function ends up multiplying each value by 1 - discount, which has the value 0.5 in this case. This means that each value in the prices array gets halved.
5) We will get an error since the scope of let i = 0 is only inside the for loop
6) We will get an error since the scope of let discountedPrice is only inside the for loop
7) This will print the final value of variable finalPrice since it was declared within the same function and not inside the for loop.
8) It should return the correct value of [50, 100, 150] since effecitvely the function ends up multiplying each value by 1 - discount, which has the value 0.5 in this case. This means that each value in the prices array gets halved.
9) We will get an error since the scope of let is only inside the for loop
10) We will get an error since the scope of const is only inside this for loop
11) finalPrice will just have the value 0 since all attempts to redefine it won't work as it was declared a const
12) We should get errors before we even hit that point because line 7 attempts to reassign finalPrice, yet we erroneously decided to make it a const variable, which impedes future progress of the function. However, if we ignore that error, finalPrice will always have the value 0 (const), which gets pushed into the discounted array that gets returned, thus discounted gets returned with the value [0 0 0].
13)
    1) student.name
    2) student["Grad Year"]
    3) student.greeting()
    4) student["Favorite Teacher"].name
    5) student.courseLoad[0]

14)
    1) '32' - string append
    2) 1 - subtraction
    3) 3 - adding null doesn't change anything
    4) '3null' - string append
    5) 4 - true has value 1
    6) 0 - false has value 0 and so does null
    7) '3undefined' - string append
    8) NaN - bad operation

15)
     1) true - integer comparison
     2) false - string comparison, not integer comparison
     3) true - comparison
     4) false - strict equality check
     5) false - true has value 1 and 1 != 2
     6) true - Boolean(2) returns the value true so the types and values match

16) == is a "simple" equality check whereas === is a strict equality check that checks for types as well as values
17) How are you? gets printed since while 2 does not have the value true, any integer value greater than 0 results in the code entering the if statement body.
18) Done in part1-question18.js
19) The result will be [ 6 8 10 ] since what the function is doing is for each element in the input array, we call the doSomething function on that element, then run that result (num + 2) through the function return x * 2. This all gets appended to a new array which gets returned after the for loop.
20) Done in part1-question20.js
21) 1 4 3 2 (with a newline in between each)

