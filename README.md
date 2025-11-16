# Windows-basic-commands-batchscript
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

<img width="514" height="89" alt="image" src="https://github.com/user-attachments/assets/311ad070-8e86-4ac1-bed6-85776c16a0b8" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="591" height="43" alt="image" src="https://github.com/user-attachments/assets/6d29fe9f-564b-422e-bfc3-5f9892dad8bf" />


## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="713" height="112" alt="image" src="https://github.com/user-attachments/assets/14a76068-3785-4622-acde-5388c048334d" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="721" height="48" alt="image" src="https://github.com/user-attachments/assets/1cc3478d-f1b7-421e-a74c-7100fad8f4ac" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


<img width="704" height="93" alt="image" src="https://github.com/user-attachments/assets/a7121621-57d7-4fff-9041-c1d338b9b057" />




## COMMAND AND OUTPUT

Remove the file hello1.txt


<img width="516" height="49" alt="image" src="https://github.com/user-attachments/assets/0d6bad7c-9632-44aa-b394-6d5c0ddd5da5" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="689" height="187" alt="image" src="https://github.com/user-attachments/assets/61fca618-0d36-41ca-8f3c-29d212b2a89a" />


## COMMAND AND OUTPUT

List out all the associated file extensions 


<img width="692" height="1136" alt="image" src="https://github.com/user-attachments/assets/82baaf95-7985-426d-8701-575ea52757dc" />



## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt


<img width="743" height="200" alt="image" src="https://github.com/user-attachments/assets/9b60f8ef-30e2-45d6-845a-81bc39fdea0a" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT


<img width="774" height="87" alt="image" src="https://github.com/user-attachments/assets/caf704cf-54dc-45b4-a71f-a288f3d70dca" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT



<img width="953" height="193" alt="image" src="https://github.com/user-attachments/assets/fe6c4519-2b2b-4a71-86ae-6328211394fe" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="837" height="183" alt="image" src="https://github.com/user-attachments/assets/34d82b8f-fd4a-4cb5-948b-1f48c0a529b9" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="914" height="251" alt="image" src="https://github.com/user-attachments/assets/2f9f50d9-9ba8-41e9-be0e-179fe9bf9766" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT


<img width="814" height="190" alt="image" src="https://github.com/user-attachments/assets/63129f85-bb8e-467f-9308-60a965ac77b0" />



# RESULT:
The commands/batch files are executed successfully.

