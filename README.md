
There are different ways and techniques of backing up your files; this is one method for programmers using CENTOS.

Setting up the backup script involves a few basic steps.

Step one: create the script that will create a compressed file containing all your targeted backup files.  The script also needs to create a new, time-stamped directory on the external mounted media (flash drive or other), and then the script must move the new, compressed file to that media.  

Step two: Navigate to the /etc/ directory and update crontab by entering the following terminal command:
crontab -e

Step three: Set the timing and the command you wish to run. 
To learn about how to set the time, refer here to a third-party site: https://crontab.guru/  

The command(s) after the indicated timing should trigger the script that handles the backup process for the files.

