## Navigation
--------------------------------------------------------------------------------------------------
Command	          Meaning
ls		          List
pwd		          Print Working Directory
cd		          Change Directory
cp		          Copy
mv		          Move
rm		          Remove
mkdir		      Make Directory
rmdir		      Remove Directory
cat		          Concatenate (commonly used to display a file)
man		          Manual
sudo		      Super User Do

--------------------------------------------------------------------------------------------------
ls -l                 Show detailed file permissions
chmod +x file         Add execute permission
chmod -x file         Remove execute permission
chmod -w file         Remove write permission
chown user file       Change owner

## Linux Permission Symbols

d = Directory

- = File

r = Read

w = Write

x = Execute

Owner = First three permissions

Group = Middle three permissions

Others = Last three permissions

--------------------------------------------------------------------------------------------------

whoami          Show current username

id              Show user ID and groups

groups          Show the groups you belong to

echo $HOME      Show your home directory

echo $USER      Show current username

sudo command    Run a command as administrator

-------------------------------------------------------------------------------------------------
ps          Show running processes

ps -e       Show all processes

top         Live process monitor

jobs        Show background jobs

bg          Continue a job in the background

kill PID    Stop a process

CTRL + Z    Pause the current process