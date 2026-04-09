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
| Level 2-3  | Completed | Worked with special dash file names -                 |
| Level 3-4 | Completed | Worked with spaces in a filename                       |
| Level 4-5 | Completed | Worked with human readable files                       |
| Level 5-6 | Completed | How to find human readable and a specific sized file   |
| Level 6-7 | Completed | How to find human readable and a specific sized file   |
| Level 7-8 | Completed | How to finf and search in a .txt file                  |
| Level 8-9 | Completed | How to search for a unique string in a .txt file       |
| Level 9-10 | Completed | How to search for a file with a "="                   |


## Key Lessons Learnt

### Level 0-1
#### Handeling basic commands
How to use ssh to connect to a remote server, Learning that ls helps you get lists and folders, and adding that file to cat will open the folder context.

**INCORRECT**

ls readme

**CORRECT**

Cat readme

'ls' can only give you a list

'cat' opens the file for you to read

'ssh' connects to a remote server



### Level 1-2
#### Handeling special file names

Some files begin with a ('-') and are treated as a command options.

**INCORRECT**

Cat -

**CORRECT**

Cat ./-

'./' tells Linux it is a file in the current directory

'-' Can also be used to stop option parsing

### Level 2-3
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

### Level 3-4
#### Worked with hidden human readable file in the inhere directory.

Some data are stored in specific files. To get into any file in linux use cd and then to open this file I used la and cat commands.

**INCORRECT**
 
cd -/ inhere - tries to interpret both - and / inhere which does not make sense for cd
cd inhere - go into a directory 
ls - shows visible files only

**CORRECT**

Cat ./"...hiding-From-You  - correct data from the file
Cat - View or read content of the specific file 
ls - see what files are inside 
la {ls-la} - reaveals hidden files starting with '.'

la is a alias for ls-a or ls - la



### Level 4-5
#### How to find human readable and a specific sized file

Some data are stored in specific files. To navigate, use cd, and to inspect contents use ls and cat. In this level, I worked with human-readable data.

**INCORRECT**

Nothing incorrect just finding the right file.

**CORRECT**

The correct file was 07.

### Level 5-6
#### How to find human readable and a specific sized file





## Screenshots
<img width="779" height="557" alt="First Lab, #Bandit-Overthewire" src="https://github.com/user-attachments/assets/1b794157-fb90-4f94-ac4f-b02f04ff3523" />  Level 0-1
<img width="732" height="545" alt="Second Lab # Bandit- Overthewire" src="https://github.com/user-attachments/assets/f2600c3d-ef89-4ac7-92ef-b009482fcf71" />  Level 1-2
<img width="468" height="418" alt="Bandit 2 Password Lab" src="https://github.com/user-attachments/assets/24c6e104-8967-49c7-b662-0f40cd72c05d" />  Level 2-3
<img width="445" height="230" alt="Bandit 3 Password  Lab" src="https://github.com/user-attachments/assets/d9b964ee-e87a-48aa-b01d-20f1241a4034" /> Level 3-4
l<img width="677" height="192" alt="Bandit 4 Password Lab" src="https://github.com/user-attachments/assets/e32c26f3-82c2-4914-93a7-07cbbe6ee820" /> Level 4-5
<img width="724" height="498" alt="Bandit 5 Password Lab" src="https://github.com/user-attachments/assets/761e3d69-088e-48d7-a406-5c275b02baf2" /> Level 5-6
<img width="633" height="361" alt="Bandit 6 Password Lab" src="https://github.com/user-attachments/assets/93d77e26-221a-4e1e-94b4-3914c58dbafc" /> Level 6-7
<img width="595" height="483" alt="Bandit7 Password Lab" src="https://github.com/user-attachments/assets/1660e976-8e13-4d83-b284-8cefe4f0fdf8" /> Level 7-8
<img width="380" height="127" alt="Bandit8 Password Lab" src="https://github.com/user-attachments/assets/3c59794e-aca6-4835-a50f-4ac923df134c" /> Level 8-9
<img width="535" height="504" alt="bANDIT9 Password Lab" src="https://github.com/user-attachments/assets/df1aa127-f8dd-4524-82b8-fb099c71f3c3" /> Level 9-10


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

