# Python-Writing-Conditional-Statements
Force the user's answers to lowercase.

In lines 22 and 25, add two calls to the String object's lower( ) method as shown.

Now, any letters that the user types in uppercase will be immediately converted to lowercase. This makes processing the upcoming conditional statements easier.

Create a conditional statement that handles bad file path input.

Position the insertion point in line 20 and press Enter.

Type two new lines as shown.

Position the insertion point at the end of line 22.

Press Enter to go to the next line and press Backspace to remove the automatic indentation.

Type else: and press Enter.

Examine the code up to this point.

Line 21 checks to see if the input value is False.
If this is the case, then you can't process the file, so line 22 prints a message indicating that the requested file doesn't exist.
Line 23 starts the else block. Every statement indented under this section will execute if the file actually does exist.
PyCharm has automatically indented the insertion point so you can start typing code for the else branch, but you already have two existing statements (in lines 25 through 29) that should be included in this block, so these statements need to be indented.
Note: Later, you'll write code to actually look for the file and return False if the file doesn't exist. For now, you'll temporarily get this True or False value from user input.

Select lines 25 through 29 and press Tab to indent them.

Create a conditional statement that handles a user's decision to strip common words from the results.

Position the insertion point at the end of line 26 and press Enter twice.

Type two new lines of code as shown.

If the user answers y or n, the loop will execute.
For now, you've included the pass statement as a placeholder.
Later, you'll replace this placeholder with code that strips the words in COMMON_WORDS from the results.
Create a conditional statement that handles a user's decision to output the results to a text file.

Position the insertion point at the end of line 32 and press Enter twice.

Type the following code:

If the user agrees to outputting the results to a file, the code in the if branch (line 34) will execute. For now, this will just print "Success!" to the command line, but later, you'll write code to actually output the results to a file.
If the user says no to the question, the program will print "Exiting…" to the console (line 37), with the intention that the program will terminate at this point.
Test your conditions.

Run the program and answer the first prompt by entering This is a test

When asked to strip common words, enter y

Note: Because the code for user_input and common_words is incomplete, their behavior will not change based on your input.

Verify that, depending on how you answer the third question, Python will output something different.

Try lowercase and uppercase "y" and "n", and also try input that isn't either of these characters, like "no" or "yes". Restart the program as necessary to test additional input. When more of your code is fleshed out, these conditional statements will allow you to guide users down certain paths of your program depending on their choices.
