1. What will happen at line 12 and why? The code will print 3. Because the parameter prices has 3 elements, so the loop will stop when i reaches 3.

2. What will happen at line 13 and why? The code will print 150. Because, in the last iteration of the for loop, discountedPrice = 300 * 0.5 = 150.  

3. What will happen at line 14 and why? The code will print 150. Because, in the last iteration of the for loop, finalPrice = Math.round(discountedPrice*100)/100 = 150. 

4.  What will this function return? The function will return an array of numbers. In this example, the array will be [50, 100, 150] each of the 3 iterations of the for loop adds 50, 100, 150 respectively into the discounted variable. 

5. What will happen at line 12 and why? This is because i is now declared using the 'let' keyword; this means it has block scope and thus attempting to use it outside of the block it was declared throws us an error that it is not defined.

6. What will happen at line 13 and why? We get an error this time. This is because discountedPrice is now declared using the 'let' keyword; this means it has block scope and thus attempting to use it outside of the block it was declared throws us an error that it is not defined.

7. What will happen at line 14 and why? It will print out 150. This is because this line is in the same block as the declaration of the finalPrice variable so no error is thrown.

8. What will this function return? The same as question 4, the function will return an array of numbers. In this example, the array will be [50, 100, 150] each of the 3 iterations of the for loop adds 50, 100, 150 respectively into the discounted variable. 

9. What will happen at line 11 and why? The program will give an error that i is not defined. This is because it was declard using the 'let' keyword and the program is attempting to print it outside of that block.

10. What will happen at line 12 and why? It will print 3, because it prints out the variable length that is constant and was declard in the same block.  

11. What will this function return? The same as question 4 and 8 the function will return an array of numbers. In this example, the array will be [50, 100, 150] each of the 3 iterations of the for loop adds 50, 100, 150 respectively into the discounted variable. 

12. A- Accessing the value of the name property in the student object: student.name
    
B- Accessing the value of the Grad Year property in the student object: student['Grad Year']

C- Calling the function for the greeting property in the student object: student.greeting()

D- Accessing the name property of the object in the Favorite Teacher property in student: student['Favorite Teacher'].name

E- Access index zero in the array of the courseLoad property of the student object: student.courseLoad[0]

13. A- '3' + 2  = '32'. '3' is a string and + is a concatenation operator so it will concatenate 2 to it and make it a longer string.

B- '3' - 2 = 1. This time '3' gets converted to a number because the - operator is not overloaded and so all values get converted to numbers. Now the operation is simply 3-2 which is 1.

C- 3 + null = 3. This is because null is the same as zero in arithmetic so 3 + 0 is still going to be 3.

D- '3' + null = '3null'. '3' is a string and + is a concatenation operator so it will concatenate null to it and make it a longer string.

E- true + 3 = 4. This is because during arithmetic true gets converted to the number 1 and so we perform 1 + 3 which is 4.

F- false + null = 0. This is because during arithmetic false gets converted to the number 0 and so does null. 0 + 0 gives us 0.

G- '3' + undefined = '3undefined'.'3' is a string and + is a concatenation operator so it will concatenate undefined to it and make it a longer string.

H- '3' - undefined = NaN. '3' is a string and the - operator is not overloaded so it gets treated as a number. However, undefined is NaN as a number so we output NaN since 3 - NaN is still NaN.

14. A- '2' > 1 = true. The string '2' gets converted to a number and 2 is greater than 1.

B- '2' < '12' = false. Since these are both strings, a string comparison is used and unicode order dictates that 2 is greater than 1 when doing string comparision.

C- 2 == '2' = true.  A non strict comparison operator is used this time. It converts the string '2' to a number and 2 is equal to 2.

D- 2 === '2' = false. A strict comparison operator is used this time. A string is not equal to a number.

E- true == 2 = false. For boolean values true becomes 1, and 1 is not equal to 2.

F- true === Boolean(2) = true. Boolean(2) gives us true and true is equal true so we output true.

15. Explain the difference between the == and === operators : The == operator is a non strict equality comparison. This means that it performs type conversion when comparing different variables. For example, a string '2' would get converted to a number 2 when doing '2' == 2 and it would output true. On the other hand, the === operator does a strict equality comparison. This means that type conversion does not exist for comparisons and the previous example would output false.

17. The result will be [2,4,6]. This is because when we call modifyArray(...) we pass the function doSomething as a parameter. Then when we push to the new array we call the function and it doubles the values from the old array. Then we return this new array with values that have been doubled from the original.

19. What is the output of the above code? 1 4 3 2

