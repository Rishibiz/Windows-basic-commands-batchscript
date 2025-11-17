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

## COMMAND AND OUTPUT

<img width="818" height="122" alt="image" src="https://github.com/user-attachments/assets/05988e6e-95c9-492d-a84a-ee29326d343d" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="900" height="119" alt="image" src="https://github.com/user-attachments/assets/ffa52147-b4c6-48e0-9423-e94af61da84d" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="862" height="423" alt="image" src="https://github.com/user-attachments/assets/3adb5584-d241-411b-ae39-a60e31348edb" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="974" height="136" alt="image" src="https://github.com/user-attachments/assets/a587f775-ee42-47c6-87f4-6901e05ada9f" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="922" height="174" alt="image" src="https://github.com/user-attachments/assets/525347c9-3434-46bc-8841-917695401713" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="763" height="181" alt="image" src="https://github.com/user-attachments/assets/50f13484-8209-469c-9695-1b9104371b5e" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="715" height="918" alt="image" src="https://github.com/user-attachments/assets/3bcb5121-62b0-43be-b73f-ea2e143ea30d" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="715" height="918" alt="image" src="https://github.com/user-attachments/assets/6ed0f3be-33ad-4ef6-896f-e94edda3496e" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="879" height="227" alt="image" src="https://github.com/user-attachments/assets/9c95ce1e-e455-4933-bc6c-4ac25d58dc66" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="873" height="117" alt="image" src="https://github.com/user-attachments/assets/806df6b4-21da-4ddb-b8fb-79e4e317fa58" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="1246" height="929" alt="image" src="https://github.com/user-attachments/assets/59200c60-7d98-4574-9bfa-38e9fcbd4188" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="746" height="177" alt="image" src="https://github.com/user-attachments/assets/2dbc3758-a89b-4137-a219-0e35c57596fb" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="634" height="100" alt="image" src="https://github.com/user-attachments/assets/1f0765ea-b2df-4cfe-8c99-a3921e547450" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
 
<img width="593" height="312" alt="image" src="https://github.com/user-attachments/assets/a273e064-7347-4b40-9377-95e8075d5c1a" />


# RESULT:
The commands/batch files are executed successfully.

