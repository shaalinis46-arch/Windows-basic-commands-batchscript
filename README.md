<img width="438" height="422" alt="image" src="https://github.com/user-attachments/assets/5ee3a8f0-3729-4bf0-b0a5-b98f089be734" /># Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations


Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="447" height="100" alt="image" src="https://github.com/user-attachments/assets/9afb67f7-41a8-4c68-a77e-e8b4e2909d2a" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT





Create the file Rose.txt

## COMMAND AND OUTPUT


<img width="605" height="117" alt="image" src="https://github.com/user-attachments/assets/9fc8ac23-2e8f-4072-b782-48fc83e2d7d1" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="507" height="82" alt="image" src="https://github.com/user-attachments/assets/5dfc7b9d-8c68-4b23-a27b-c9207de0f72b" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="381" height="41" alt="image" src="https://github.com/user-attachments/assets/6549bbeb-7209-48aa-bcce-a2e2c03dd1ec" />


Remove the file hello1.txt

## COMMAND AND OUTPUT



List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="535" height="207" alt="image" src="https://github.com/user-attachments/assets/81201bc6-50d9-4be5-9883-f195f545b02a" />




List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="637" height="357" alt="image" src="https://github.com/user-attachments/assets/3fe92a68-f0b5-481d-ad95-5b98aa4f3fee" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="610" height="297" alt="image" src="https://github.com/user-attachments/assets/509f8664-a9bd-4484-86db-eec6152f9d77" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="432" height="95" alt="image" src="https://github.com/user-attachments/assets/544533c8-beaf-4e66-99d2-bfcd332db19d" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="420" height="185" alt="image" src="https://github.com/user-attachments/assets/bea76b82-b62e-4d2e-9a9d-74de50d144d4" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="438" height="422" alt="image" src="https://github.com/user-attachments/assets/a3b60c05-330c-45a6-85b2-a53a4ef1ca42" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="405" height="83" alt="image" src="https://github.com/user-attachments/assets/34f5f685-0935-4001-a8ed-ea6f221f41ea" />



# RESULT:
The commands/batch files are executed successfully.

