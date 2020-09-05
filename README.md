# web-blocker
Python Script that blocks distracting websites. 


# Deploying the Script

First of all, we need to configure the entry in the 
**contrab** schedule.

### Step 1
Open the contab with the -e flag. Run the following
command 
```
$ sudo crontab -e
```
Select your favorite text editor, if you did not already selected. 

### Step 2
Add the follwing the line to the file and save it. 
```
@reboot python3 /home/username/path_of_the_script/web-blocker.py
```
And, we are basically done. On system restart the script we just made, is already schedule to run at system start-up. 
