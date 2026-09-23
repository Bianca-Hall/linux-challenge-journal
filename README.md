# linux-challenge-journal
# My Linux Upskill Challenge Journal
BITA Kernel Crew · Cohort 1 · Sept 2026

## Day 0
- Set up my server (DigitalOcean) — it's alive 🐧
- Problems I hit and how I fixed them: I had an issue where I was stuck trying to retrieve my public key
- The way I was able to retrieve it was by following the path to where it was saved on my laptop and opening it it notepad then I pasted it to key my SSH Key

## Day 1 Get to know your server
- Logged into server using (Killercoda) in the browser 
# Commands
- lsb_release -a view the linux distro and server in use
- cat /etc/os-release to check what is is displayed from the previous command
- uname -a displays system information
- uptime shows how long the system has been running
- whoaami will print the username
- who - didn't show who was logged in because I am using a server on the browser
- w didn't show anything
- lshw displays detailed information on the hardware configuration
- lscpu displayed the CPU Architecture
- lsblk was to list blocked devices- which I didn't have any
- lspci to list pci devices there weren't any
- lsusb to list usb devices; there were none
- free -h to show memory used
- vmstat- showed memory stats
- top (taskamanager for linux) command ran continuously  ctrl + C stopped the command from running
- htop displayed the interactive version of task manager
- df-h showed disk space usage
- du -h estimated the size of folders
- ifconfig displayed the network interfaces information
- netstat -i showed a static view of bandwidth usage 
- ifstat showed bandwidth usage continuous; ctrl + c stopped it
- sudo iftop -i enp1s0 displayed an error- Displayed traffic
- I got an error in the previous command but the issue was I had a o instead of a 0


# Day 2 Basic Navigation 
-  Logged into server using (Killercoda) in the browser
-  Also explored the challenge in DigitalOcean
-  This one was fun making directories and removing them
-  No issues 

# Day 3 Power Trip 
- Logged into DigitalOcean
- No issues with this challenge

# Day 4 Installing Software, exploring the file structure 
- Challenge done using DigitalOcean
- No issues here 
<img width="581" height="275" alt="image" src="https://github.com/user-attachments/assets/fe5b71f6-29e5-4d04-a411-2b32ba1ebe9f" />
<img width="315" height="133" alt="image" src="https://github.com/user-attachments/assets/47e59ecb-4978-414a-a98d-387b3040e53b" />

# Day 5 More or Less 
- Learned to use the tab feature, more adding lines and less removing entries
- Used the history command to view the history of all the commands I've entered


# Day 6 Editing with VIM 
No issues here; notes for myself below 
- Vim Terminology
- Vim uses different names for copy, cut, and paste operations:
- Yank (y) - Copy text
- Delete (d) - Cut text (removes it and stores it in a register)
- Put (p) - Paste text from a register
- dd - Delete the entire current line
- diw - Delete the current word
- x - Delete the character under the cursor
- :q! to quit 

# Day 7 The server and its services 



