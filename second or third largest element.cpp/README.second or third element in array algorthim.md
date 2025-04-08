 algorthim of second or third element in array:

 1. Include the necessary header files for input/output and INT_MIN.

 2. Declare a function named findSecondAndThirdLargest that takes in an array of integers (arr) and its size (size) as parameters.

 3. Check if the size of the array is at least 3, if not, print an error message and return.

 4. Initialize three variables (first, second, third) to store the three largest elements in the array. Set them to INT_MIN, the smallest possible value for an integer.

5. Traverse the array using a for loop.

 6. Inside the loop, check if the current element is greater than the value of the first variable. If so, update the values of first, second and third accordingly.

7. If the current element is not greater than the first variable, check if it is greater than the second variable and not equal to the first variable. If so, update the values of second and third.

 8. If the current element is not greater than the second variable and not equal to the first variable, check if it is greater than the third variable. If so, update the value of the third variable.

 9. After the loop, print out the values of the second and third variables as the second and third largest elements in the array.

10. In the main function, define an array of integers and its size.

 11. Call the findSecondAndThirdLargest function passing in the array and its size.

 12. Finally, return 0 to end the program.
The out put of the code is:the second largest:90
                           :the third largest:89
                           
