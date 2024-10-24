# Cybersecurity
Notes      
For Cybersecurity

1: Binary Numbers
Computers didn’t use words like us, instead, they used 0s and 1s! Those are computer languages. For example, there is a picture shown below: 

Convert the binary number into decimals:
10101100     means 128+0+32+0+8+4+0+0=172
10110111      means 128+0+32+16+8+4+2+1=191

2. Memory systems
There are two types of memory systems: Volatile and Non-volatile memory. Here are some explanations for both.

Volatile Memory: Volatile memory is a type of computer memory that requires power to maintain stored information actively. When 
power is turned off or lost, the data stored in volatile memory is erased or lost. It only retains information in the presence of electrical power.

Non-Volatile Memory: Non-volatile memory is a type of computer memory that retains stored information even when the power is turned off. 
Unlike volatile memory, non-volatile memory retains data even with no electrical power. It is designed for long-term storage of information.

3. Parts of a Virtual Machine
A Virtual Machine is made out of many small parts. Here are some major parts of Virtual Machine hardware:

CPU: A CPU, or Central Processing Unit, is the primary component of a computer that performs most 
of the processing and executes instructions of a computer program. It can be considered as the "brain" of the computer.

GPU: A GPU, or Graphics Processing Unit, is a specialized electronic circuit that accelerates the processing of images and videos. 
They were originally designed to handle graphics rendering tasks.

Motherboard: A motherboard is a computer's main printed circuit board (PCB). It is a fundamental component that 
serves as a central hub, connecting various hardware components and allowing them to communicate with each other. The motherboard 
provides the physical and electrical connections for the CPU.

RAM: RAM, or Random Access Memory, is a volatile computer memory used to store data and machine code currently being 
used and processed by a computer. Unlike permanent storage devices such as hard drives or SSDs, RAM is temporary and 
loses its content when the power is turned off.

4. Basic Commands
gci: get child-item is used to retrieve the child items (files and directories) within a specified directory. It functions 
similarly to the "ls" command in Unix-like operating systems.
mkdir: makes a directory/file 
rmdir: deletes a directory/file
Stop-computer: shut down your computer
mv: move files/directory
Restart-computer: restart your computer
Dir: same with gci, to check files and directories
rename "current_filename.ext" "new_filename.ext" this command lets you to rename files 
rename "current_directory_name" "new_directory_name" this command lets you rename your directory
5. Basic linux command
Linux and Windows use different systems. This is why the computer's commands are divided into parts. On section five, 
are some commands about linux operating systems.
sudo apt-get install This command means that it lets sudo temporarily allow users to download and install.
ls-I This command lets the system display the files and directories in the current directory. 
cd /path/to/directory This command lets you move to another directory
mv /path/to/source/file /path/to/destination this command lets you move to another file. 
mkdir new_folder This command will make a new file. The term new_folder is technically the name of the new folder/directory.
rm file.txt Opposite of the previous command, this command will remove a file/directory. IF REMOVING A DIRECTORY, YOU MUST MAKE SURE
IT WAS EMPTY OR THE COMMAND WON’T WORK
rm -rf directory/ WARNING: THIS COMMAND MEAN DELETE BY FORCE AND IT IS A DANGEROUS COMMAND. IF YOU ACCIDENTALLY USED THIS COMMAND TO 
DELETE ANY ESSENTIAL PART OF THE VIRTUAL MACHINE YOU WILL ACTUALLY DESTROY IT. SO BE VERY CAREFUL!!!!!
ls /path/to/ this command lets you check to see if a directory exists. 
ls /path/to/file this command lets you check to see if a file exists or not.
cp file.txt /destination/folder This command will copy a file and directory from the system. The term destination
means where the folder is going to get copied to.
mv file.txt /new/location/
mv oldname.txt newname.txt
These two commands technically both mean “move” but the first one means you are moving a file/directory 
somewhere else. The term new/location/  indicates where you are moving your new file/ directory.
The second command, means you are renaming your file/ directory. The term old name indicates which 
file’s name you’re going to change, and the term new name is what you're going to change the name into.
cat file.txt This command lets you view the contents of the files.
sudo shutdown This command lets you shutdown your system.
sudo reboot This command lets you restart your systems.
cd this command lets you change directories.
chmod this command lets you change file permissions.
Example: chmod 755 script.sh.
chown this command lets you change file owner and group.
which
whereis 
These two commands will help you to find the programs on your system. The difference between them is “which” 
command helps you find a program.
But “whereis” command did the same thing, but in more detail.
locate file This command will let you find all files/directories that got the term in there.

Video that can watch: https://youtu.be/s3ii48qYBxA?si=a0ucM3_dCaWg2vWD

6. Os layers
The layers are: 
Hardware
Firmware
BIOS
Kernal
Shell
File Systems
All of those things above make up an operating system.

7. Networking
-Ethical Hacking This simply means you are breaking into systems legally to discover and report any safety weaknesses 
or things to know before a real hacker breaks into your system illegally. 
-Internet: The Internet is a global network of interconnected computers and other electronic 
devices that communicate with each other using standardized protocols. It is a vast network infrastructure 
that enables the exchange of data and information across geographical distances, connecting billions of devices worldwide.
-Networks: Networking connects computers, devices, or people to share resources, information, or services.
It involves the interconnection of various nodes (such as computers, servers, routers, and switches) using physical or wireless
connections, enabling communication and data exchange between them.
-Firewall A network security system that monitors and controls incoming/outgoing networks based on security rules.
-IP Address This is a unique “Address” that can be identified for a device on the network.
-DDOS Attack This is a type of cyber attack in which multiple systems, often compromised through malware or controlled by a 
malicious actor, flood a targeted server, network, or website with excessive traffic. The goal is to overwhelm the target, 
causing it to become slow, unresponsive, or completely unavailable to legitimate users.
-PWD PWD stands for Present Working Directory. It is a command used in various command-line interfaces, such as Linux, macOS, and other 
Unix-like operating systems, to display the full path of the directory that the user is currently in. 
8. Bash scripting
Comments (#):
In the script, anything written after a # The symbol is ignored by the computer. It’s called a comment. 
Comments are used to explain the code to anyone reading it, so they know what each part does. 
Comments are important to help you understand what you are working on or are trying to do in your code and act as reminders. 
There is no limit to the amount of comments or their detail you should or could have.
echo:
The echo command is used to display a message on the screen. It's like making the computer "say" something to the user. These are 
useful for displaying prompts, comments or instructions to the user.
The echo command is also a useful tool to test your code. Putting in an echo both inside and outside an if block can help you see 
what is working in your code or what is broken. echo statements used for troubleshooting should always be removed
when troubleshooting is complete.
Variables:
Variables are like containers that store values. In this script, age_years and age_days are variables.
read -p "Enter your age in years: " age_years takes the user's input and stores it in the age_years variable.
Tip: you can use an echo to display the value of a variable for troubleshooting purposes.
if Statement:
The if statement is used to check if something is true. It helps us control which parts of the script run based on a condition.
For example, we use if to make sure the user’s input is valid.
Regex (^[0-9]+$):
This part is a pattern used to match text. It’s called a "regular expression" (or regex).
^[0-9]+$ means that the input must be made up of digits (0-9), and nothing else. This makes sure the user only types numbers.
^ means "start of input" and $ means "end of input". [0-9] means any digit, and + means "at least one or more".
Resource to learning more about Regex: regexlearn.com/learn/regex101
Tip: Once you have typed or followed the instructions - hit the enter key to progress.
Resource for testing and playing with Regex: regex101.com/
[[ ]] and !~:
[[ ]] is used to test conditions in Bash. It helps make the script safer and easier to write.
!~ means "does not match". In this script, [[ ! $age_years =~ ^[0-9]+$ ]] checks if the input does not match the pattern
 (meaning it’s not a number).
Tip: Other symbols you may want to explore are ==, |&nbsp;, &nbsp;&gt;&nbsp;, &nbsp;&lt;&nbsp;, -eq, -ne, -gt.
We refer to these symbols as "Conditionals" and there are many more conditionals than what I have listed here.
 Arithmetic Calculation ($(( ))):
$(( )) is used to do math calculations in Bash.
age_days=$((age_years * 365)) calculates how many days are in the given number of years. It multiplies age_years by 365.
Exit Code (exit 1):
exit 1 ends the script. The number 1 is an error code, which means something went wrong.
If the user types something that’s not a valid number, the script stops here.
Tip: use an echo statement to give a clear message to yourself, and your user about what happened.

9. System monitoring
10. System security
