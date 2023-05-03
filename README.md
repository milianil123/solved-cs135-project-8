Download Link: https://assignmentchef.com/product/solved-cs135-project-8
<br>
<u>Project [8]: Pointers and Strings</u>




<h1>Project Goals</h1>

The goals of this project are to:

<ul>

 <li>Get students familiar with the use of pointers</li>

 <li>Get students familiar with strings</li>

</ul>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output content and formatting: for example, do not change the text of the problem from “Enter the first string: ” to “Enter string: ”. Your assignment will be auto-graded and any change in formatting will result in a loss in the grade.</li>

 <li><strong>Comments: </strong>Header comments are required on all files, for each function, and recommended throughout the rest of the program. Points will be deducted if no header/function comments are included.</li>

 <li><strong>Restriction: </strong>The use of goto statements anywhere within this program is prohibited. Points will be deducted if gotois used.</li>

</ol>




<h1>Problem 1</h1>

Write a program that implements four of the string library functions using pointers: strcopy (string copy), strconcat (string concatenate), strcomp (string compare), and strlength (string length). First, the program will ask the user to enter two strings with a maximum of 20 characters each. The program will then output the length of each string. Then, it will output which string comes first alphabetically. The program will then add string 1 to string 2 and output the two strings. Finally, the program will copy string 1 into string 2 and print the two strings again.

Your program should:

<ol>

 <li>Using the strlength function, calculate and print out the length of each string.</li>

 <li>Using the strcomp function, print out which string comes first alphabetically.

  <ol>

   <li>If the strings are the same your program should print out: “The two strings are the same.”</li>

   <li>If string 1 comes first alphabetically your program should print out: “String 1 comes before string 2 alphabetically.”</li>

   <li>If string 2 comes first alphabetically your program should print out: “String 2 comes before string 1 alphabetically.”</li>

  </ol></li>

 <li>Using the strconcat function, add string 1 to the end of string 2 and print out string 1 and 2</li>

 <li>Using the strcopy function, copy string 1 into string 2 and print out string 1 and 2</li>

</ol>

The program should function as follows (items underlined are to be entered by the user):

Please enter the first string: <u>jackhammer</u>

Please enter the second string: <u>Jacky</u>

The length of string 1 is: 10

The length of string 2 is: 5

String 1 comes before string 2 alphabetically.

String 1 after concatenation: jackhammer

String 2 after concatenation: Jackyjackhammer

String 1 after copying: jackhammer

String 2 after copying: jackhammer

Your program should implement and use the following functions:

<ul>

 <li>strlength: This function will take as a parameter a character pointer to a string. It will return the length of the string, not including the null terminator.</li>

 <li>strcopy: This function should take as parameters two character pointers to two strings (a destination string and a source string in that order). Then it will copy the source string into the destination string, including the null terminator. It will then return a pointer to the beginning of the destination string.</li>

 <li>strconcat: This function should take as parameters two character pointers to two strings (a destination string and a source string in that order). Then it will add the source string to the end of the destination string. It will then return a pointer to the beginning of the destination string.</li>

 <li>strcomp: This function will take as parameters two character pointers to two strings (string 1 and string 2 in that order). The function then compares the two strings and if string 1 comes first alphabetically it returns 1. If the string 2 comes first alphabetically then it returns -1. If the strings are the same, then the function returns 0. The function should compare the two strings one character at a time and return the appropriate value as soon as a difference is noticed between the strings.</li>

</ul>




<strong>Note: </strong>

<ul>

 <li>You may <strong>NOT </strong>include the string library. The point of this project is to get students to work with pointers and their use in strings. Inclusion of the string library will result in a grade of zero for this project. (You must write all the functions yourself)</li>

 <li>Your functions must use pointers and pointer arithmetic. You are not allowed to use square brackets to move along the strings.</li>

 <li>You can assume that all strings will be just alphabetic characters. The strings will not contain any spaces.</li>

</ul>




Save your program as strings.c





