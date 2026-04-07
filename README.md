# About This Repository
It is documenting my hands-on learning Journey through different labs and my findings. (Includes notes, screenshots, and detailed experiences of what I learnt)

# Lab One: Over-The-Wire Bandit


The Goal is:

-Linux Command Line.

-Problem Solving - Finding the password 

-Cybersecurity Fundamentals

## Progress

|  Level    |  Status   |  Notes                                                |
|-----------|-----------|-------------------------------------------------------|
| Level 0-1 | Completed | Learnt how to SSH into a remote server                |
| Lvel 2-3  | Completed | Worked with special dash file names -                 |


## Key Lessons Learnt

### Level Zero
#### Handeling basic commands
How to use ssh to connect to a remote server, Learning that ls helps you get lists and folders, and adding that file to cat will open the folder context.

**INCORRECT**

ls readme

**CORRECT**

Cat readme

'ls' can only give you a list

'cat' opens the file for you to read

'ssh' connects to a remote server



### Level One
#### Handeling special file names

Some files begin with a ('-') and are treated as a command options.

**INCORRECT**

Cat -

**CORRECT**

Cat ./-

'./' tells Linux it is a file in the current directory

'-' Can also be used to stop option parsing

### Level Two
#### Handeling spaces in filenames that begin with '-' or '--'

Some files have spaces and begin with special characters. They can also be found in the home directory (cd)

**INCORRECT**

Cat -
Cat -- spaces in this file--
Cat ./ --
Cat "--Spaces in this file.."

**CORRECT**

Cat ./"--spaces in the filename--"

'.' tells it that it is in the current file directory

'/"--...--"' Treated as a path


## Screenshots
<img width="779" height="557" alt="First Lab, #Bandit-Overthewire" src="https://github.com/user-attachments/assets/1b794157-fb90-4f94-ac4f-b02f04ff3523" />  Level 0-1
<img width="732" height="545" alt="Second Lab # Bandit- Overthewire" src="https://github.com/user-attachments/assets/f2600c3d-ef89-4ac7-92ef-b009482fcf71" />  Level 1-2
<img width="468" height="418" alt="Bandit 2 Password Lab" src="https://github.com/user-attachments/assets/24c6e104-8967-49c7-b662-0f40cd72c05d" />  Level 2-3

## Tools Used

- Linux Terminal
- SSH
- OverTheWire Bandit

  ## What I'm Working On
  - Continueing OverTheWire Levels
  - Improving Linux Command Knowledge
  - Building a Cybersecurity Profile

  ## Note
  Passwords and sensitive information are not included for security and integrity.

