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


<img width="642" height="112" alt="Screenshot 2026-09-10 203616" src="https://github.com/user-attachments/assets/514ce263-de02-4a7f-9802-690d6d2a1dcb" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT



<img width="566" height="126" alt="Screenshot 2026-09-10 203705" src="https://github.com/user-attachments/assets/5c726c40-bdbc-448b-9797-8f65f5c67196" />

Create the file Rose.txt

## COMMAND AND OUTPUT


<img width="658" height="372" alt="Screenshot 2026-09-10 203908" src="https://github.com/user-attachments/assets/c9cbcbc8-24de-4fb6-ac3a-328290b5a564" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="715" height="120" alt="Screenshot 2026-09-10 204001" src="https://github.com/user-attachments/assets/07fc705e-1406-470d-be39-9ca44b7c40f2" />



Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="570" height="130" alt="Screenshot 2026-09-10 204049" src="https://github.com/user-attachments/assets/b27e6999-4006-4977-9cc5-9cf67544d6de" />



Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="503" height="192" alt="Screenshot 2026-09-10 204158" src="https://github.com/user-attachments/assets/bd271b71-11a3-454b-bd7c-14748af6299a" />



List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="508" height="545" alt="Screenshot 2026-09-10 204237" src="https://github.com/user-attachments/assets/0eeb1212-3973-40b5-b2b0-c20921f47bec" />



List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="570" height="623" alt="Screenshot 2026-09-10 204402" src="https://github.com/user-attachments/assets/aa2ff412-621e-45ab-bcdc-2ff36ef16160" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="436" height="81" alt="Screenshot 2026-09-10 204556" src="https://github.com/user-attachments/assets/7e5e7b3f-052d-4a8d-acc6-a9bf3861ee30" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="618" height="202" alt="Screenshot 2026-09-10 204650" src="https://github.com/user-attachments/assets/d38e0350-59fe-4b81-9df5-22fe7697b815" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="423" height="167" alt="Screenshot 2026-09-10 204751" src="https://github.com/user-attachments/assets/7cb662f9-6da3-4414-9adc-02c723f42073" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="562" height="228" alt="Screenshot 2026-09-10 204900" src="https://github.com/user-attachments/assets/34659a55-7b37-49bd-be64-75b6fc3938c2" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="405" height="345" alt="Screenshot 2026-09-10 204935" src="https://github.com/user-attachments/assets/2575d3e6-6546-4f0a-89b6-a2e38cb1465d" />



# RESULT:
The commands/batch files are executed successfully.

