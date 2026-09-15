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
  
