**IFT 194/101 – Information Technology Programming Logic**

**Lab 1**

**The purpose of this lab is to**

1. Setup Python and the integrated development environment (IDE) that you will use to write Python code through-out this course.
2. Learn how you can define variables with different data types in Python.
3. Write some simple mathematical, relational and logic expressions in Python.
4. Learn



**Part I: Installing Python**

The steps for this part will direct you towards downloading and installing a specific IDE. This IDE is called **IDLE**. IDLE can be used with Linux, Mac or Windows. If you choose to work with a different IDE, that is fine. Please notice that all the coding that will done by the instructor in the online sessions will be using IDLE.

**Part I Steps:**

1. Go to [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Download Python 3.6.4, selecting the appropriate version for you OS (Linux, Mac or Windows).
3. Install Python using the downloaded package. This step will automatically install IDLE. IDLE is just a GUI (graphical user interface) that you will be using to create new files, type python code in them and run them.
4. Once you are done, open IDLE. For windows, you can find it using the start menu. For Mac, it should appear in your applications folder.
5. IDLE opens to a console where you can type single instructions and have them executed, one at a time. Type this command on the IDLE console:
print(&quot;Hello&quot;)
Then press enter.
6. You should see the word Hello printed on a new line.
7. Now go to the **File** menu, and click on **New File**. This will open a new empty file.
8. Type the two instructions:
print(&quot;Hello!&quot;)
print(&quot;This is my first python program!&quot;)
9. Save your file.
10. Then go to the **Run** menu, and select **Run Module     F5**.
11. This should take you back to the IDLE console, and you will find the two lines above printed there.

**Part II: Defining Variables in Python**

In this part we will learn how to define variables of different types, and initialize them in Python.

**Part II Steps:**

1. Open IDLE. This will open to the main Python console, where you can write simple instructions. We will use this console.
2. Create a numeric integer variable named x, and assign it the value of 10. This is done by simply typing this in the console:
x = 10
then press enter.

This allocates a location in the main memory (RAM), and saves the value of 10 in that location. You can always access that memory location using the variable name, x.

1. Now, let us print the value of x, by calling the print() function in Python. Just type this in the console:
print(x)
You should see the number 10 printed for you.
2. Now you define another variable named y, and set it with the value of 15, just the same way you defined x.
3. Then print y, the same way you printed x.
4. Create another variable named z to hold a real numeric value of 0.7 by typing:
z = 0.7
5. Print z.
6. Create another string variable named course\_name to hold the name of our course:
course\_name = &quot;Introduction to Programming Logic&quot;
7.  Print course\_name, also by calling the print() function:
print(course\_name)
8. Create a logic variable named a, and set it to true:
a = True
Pay attention to the upper case T in True. Python is case sensitive. If you type true with a lower case t, you will get an error.
9. Then create another logic variable b and set it to false:
b = False

We will use the variables that we just defined in Part III of the lab. Do NOT close IDLE before you finish Part III. If you do so, all your variables will be lost (erased from the memory), and you will have to recreate them to do Part III.



**Part III: Doing Simple Operations**

In this part, you will learn how to do simple mathematical, relational and logic operations in Python. You will use the same variables that you defined in Part II.

**Part III Steps:**

1. Let us add the values in x and y, and store the result in another variable named sum. We can do that by typing:
sum = x + y
2. Use the print function to print the value in sum by typing
print(sum)
This should print out 25.
3. Apply the relational operator \&gt; to see if x is greater than y by typing:
x \&gt; y
This should print out False.
Notice that  x \&gt; y is an expression, and not an equation. That is, the result (False) is not stored in any variable, and so, Python just prints that result out.
In other words, if you type an expression, the result of the expression will be displayed right away. But if you type an equation, the result will be stored in the variable at the left hand side of the equation. You can then print that variable to see the result, just like we did in steps 1 and 2 of Part III.
4. Apply the not equal operator to x and y:
x != y
That should print True since x=10 and y=15.
5. Let us apply the AND logic operator to variables a and b. This is done in python by typing:
a and b
Notice that &quot; **and**&quot; should all be typed in lowercase letters.
6. Now apply the OR logic operator to variables a and b. Also use lowercase letters to type &quot; **or**&quot;.
7. Create a variable na to store the negation of a:
na = not a
8. Print na
That should print False since a is True.

**Lab Deliverables:**
You need to deliver a single doc/docx/pdf file that contains

1. Your name
2. Screen shots to show all your work in Parts I, II and III. If you are using another IDE, make sure that you show your code and the obtained output.
