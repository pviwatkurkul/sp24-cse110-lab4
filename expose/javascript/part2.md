Question 1: Line 12 prints out the total value of variable of var i after being incremented from the for loop\
Question 2: 150 will print from the value of discountedPrice which is the result of 300*0.5 = 150.\
Question 3: 150 will print from the value of final price which is the last price in the list to be discounted.\
Question 4: [50, 100, 150] because the for loop adds the discounted price for each original price in the list.\
Question 5: i is not defined error, since i was declared using let, the variable is within a block scope which gets deleted after the for loop.\
Question 6: discountedPrice is not defined error. Since discountedPrice was declared using let, the variable is within a block scope which gets deleted after the for loop.\
Question 7: 150 is printed, since finalPrice has a block scope using let but is declared outside the for loop, it retains its value after the loop.\
Question 8: [50, 100, 150] is returned, since discounted has a block scope using let but is declared outside the for loop, it retains its value after the loop.\
Question 9: i is not defined error, since i was declared using let, the variable is within a block scope which gets deleted after the for loop.\
Question 10: 3 because length is defined with prices.length = 3 and never altered so the const is printed. \
Question 11: [50, 100, 150], the values inside the const array can be changed and therefore can also add new items but cannot reference a new array.\
Question 12: student.name, student["Grad Year"], student.greeting(), student['Favorite Teacher'].name, student.courseLoad[0];\
Question 13: 
- A: '32', converts to 2 to '2' and concanates strings
- B: 1, converts '3' to 3 and subracts because - is a mathematical expression
- C: 3 null is treated as 0
- D: '3null', null is converted to string and concatenated
- E: 4, true is treated as 1 and added to 3
- F: 0, false is 0 and null is treated as 0
- G: '3undefined', undefined is converted to string and concatenated to 3
- H: NaN, '3' cannot mathematically subtract an undefined value  

Question 14:
- A: true, '2' becomes 2 > 1, which is true
- B: false, dictionary '12' is not greater than dictionary '2'
- C: true, '2' becomes 2 == 2 which is true
- D: false, type comparison of string vs number which is false
- E: false, 1 is not equal to 2
- F: true, because 2 is converted to boolean which type checks with boolean true\
Question 15: === is a data type comparison and == is an equality test\
Question 17: [2,4,6] is printed, when calling modifyArray we pass in an array, and a callback function for the called function to utilize. When we start looping over the elements of the array, for each iteration we call the callback function, doSomething, which multiplies each element by 2. The final array after the loop results in [2,4,6]\
Question 19: 1432