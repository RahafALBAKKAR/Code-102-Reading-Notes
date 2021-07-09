_____
# [**Control flow**](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
______
The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 
_____
Example:

if (field==empty) 
{
    promptUser();
} 

else {
    submitForm();
}
For example, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code

**Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.**
