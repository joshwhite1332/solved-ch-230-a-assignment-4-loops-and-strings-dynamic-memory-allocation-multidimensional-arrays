Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-4-loops-and-strings-dynamic-memory-allocation-multidimensional-arrays
<br>
<h1><strong>Problem 4.1 </strong>A table for circles</h1>

Write a program that prints a table where each line consists of a value x, the area of the circle with radius x, and the perimeter of the circle with radius x (i.e., three values separated by space). Ask the user to input from the keyboard the lower and upper limits as well as a step size for the table (i.e., at which value to start and where to stop, and the increment from one line to the next).

<em>You can safely assume that the upper and lower limits, and the step size will be valid.</em>

Use a for loop for solving this problem.

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="564">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 4.1: input</strong>1.530.5</td>

   <td width="274"><strong>Testcase 4.1: output</strong>1.500000 7.068583 9.4247782.000000 12.566371 12.5663712.500000 19.634954 15.7079633.000000 28.274334 18.849556</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 4.2 </strong><em>Word as zig zag</em></td>

   <td width="274"> </td>

  </tr>

 </tbody>

</table>

<h2><strong>Language: C</strong></h2>

Write a program where you read a string (which may contain spaces) from the standard input. You can safely assume that the string will not be longer than 50 characters. Print the string on the screen as in the following testcase.

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="431">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 4.2: input</strong>Hello world</td>

   <td width="141"><strong>Testcase 4.2: output</strong>H</td>

  </tr>

 </tbody>

</table>

e l l o

w o r l d

<h1><strong>Problem 4.3 </strong>Using switch and calling functions</h1>

Write a program where you can read up to 15 floats from the keyboard into an array. A negative value ends the input loop and the negative value is not part of the array. You can assume that no more than 15 integers will be read.

Then by using a switch statement, pressing m (and ’Enter’) computes the geometric mean of the array (and prints the result), h determines and prints the highest number in the array, l determines and prints the smallest number in the array and s determines and prints the sum of all elements in the array. Write functions for each task. The result of these functions must be printed from the main() function.

The prototype to compute the geometric mean should have the following form:

float geometric_mean(float arr[], int num);

The formula for computing the geometric mean of an array of positive values (x<sub>i</sub>)<sub>i</sub><sub>=1<em>,…,</em>n </sub>with n elements is:<u><sub>1</sub></u>

!n

gmean =

<em>You can safely assume that the input will be valid.</em>

<h1><strong>Problem 4.4 </strong>Determine consonants in string I</h1>

Write a function int count_consonants(char str[]) that determines and returns the number of consonants in a given string.

Then write a simple main() function where you can repeatedly enter a string and then the number of consonants is determined and printed on the screen (from the main() function). If the entered string is empty (it will contain only a ’
’ then) the program should stop its execution. <em>You can safely assume that the entered string will be not longer than </em>100 <em>characters and will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1><strong>Testcase 4.4: inputTestcase 4.4: output</strong></h1>

Hello worldNumber of consonants=7 thisNumber of consonants=3 lastNumber of consonants=3

<h2><strong>Problem 4.5 </strong>Determine consonants in string II</h2>

Rewrite the function int count_consonants(char str[]) from your solution of the previous problem to walk through the string using a pointer and address arithmetic. Reuse your main() function from the previous problem’s solution.

<h2><strong>Problem 4.6 </strong>Dynamic memory allocation</h2>

Write a program which allocates memory for an array of integers entered from the keyboard having n elements (value read also from the keyboard). Write and call a function which determines and prints on the screen the two greatest values within this array. At the end of the program make sure that the memory will be released.

<em>You can safely assume that the input will be valid. Solve the problem without sorting the array or without iterating through the array more than one time.</em>

<h2><strong>Problem 4.7 </strong>Under the main diagonal of matrix</h2>

Write a program which declares a two dimensional array of integers having at most 30 rows and 30 columns. Read from the keyboard an integer n representing the number of rows and the number of columns of the matrix.

Then read the values of the matrix row by row and column by column. Then write and call a function for printing the values of the matrix in its form. Also write and call a function which prints on the screen the elements of the matrix which are under the main diagonal.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="481">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 4.7: input</strong>312345</td>

   <td width="191"><strong>Testcase 4.7: output</strong>The entered matrix is:1 2 34 5 67 8 9Under the main diagonal:4 7 8</td>

  </tr>

 </tbody>

</table>

6

7

8

9

<h2><strong>Problem 4.8 </strong>Under the secondary diagonal of matrix</h2>

Modify your solution for the previous problem such that the elements under the secondary diagonal (i.e., the other diagonal) are printed on the screen.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="564">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 4.8: input</strong>3123456789</td>

   <td width="274"><strong>Testcase 4.8: output</strong>The entered matrix is:1 2 34 5 67 8 9Under the secondary diagonal:6 8 9</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 4.9 </strong><em>Dynamic Array</em></td>

   <td width="274"> </td>

  </tr>

  <tr>

   <td width="290"> </td>

   <td width="274"> </td>

  </tr>

 </tbody>

</table>

Write a function int prodminmax(int arr[], int n) that determines and returns the product of the smallest and largest elements of an array of integers.

Then write a program where you first read an integer n and then n integers that are stored in an array called arr. Test the function above and print on the screen the results from the main() function. Use dynamic memory allocation and deallocation. <em>You can safely assume that the input will be valid.</em>

<table width="446">

 <tbody>

  <tr>

   <td width="446"><strong>Problem 4.10 </strong><em>Passing by reference</em></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a function void proddivpowinv(float a, float b, float *prod, float *div, float *pwr, float *invb) that computes and “returns” by reference the product, the division of the two floats as well as the result of a<sup>b </sup>and 1<em>/</em>b.

Also write a simple test program to check that your function works correctly (by printing on the screen the results from the main() function).

<em>You can safely assume that the input will be valid and that b will not be </em>0<em>.</em>

<h2><strong>Problem 4.11 </strong>Walk the string</h2>

Write a function int countinsensitive(char *str, char c) that counts the occurrences of the character c in the string str in the case insensitive manner (i.e., no difference between uppercase and lowercase letters). Write a program that tests this function. You should be able to process a string of arbitrary length. First you can dynamically allocate a string of maximal length of 50 characters, then you read the string from the keyboard, then you allocate memory for another string of the correct size, copy the original string into the new string and then deallocate the memory occupied by the first string. You may use the functions tolower() or toupper() which are in ctype.h. Use the man page to see how these functions work.

<em>You can safely assume that the input will be valid.</em>

Determine the occurrence of the characters ’b’, ’H’, ’8’, ’u’, and ’$’. For each character the output should be as follows, for example:

The character ’b’ occurs 3 times.

<h2><strong>Problem 4.12 </strong>String functions</h2>

Write a function void replaceAll(char *str, char c, char e) that replaces all occurrences of the character c by the character e.

Write a program to test the function. The program should repeatedly read a string (up to 80 chars), a character to be replaced and then the replacing character until you enter “stop” for the string. Your program should repeatedly print the character to be replaced, the replacing character and the strings on the screen from the main function before and after the replacement. <em>You can safely assume that the input will be valid.</em>