# Clock-py  
This project is a clock written in python.  

## Warnings
The app is supported only in linux in a compiled executable.     
You can use this app just with the python file or compile the code yourself for your platform like with pyinstaller or cx_freeze.
## Installation  

### Manually   

Download the last package and extract it in a .clock folder in your home directory so that the path to the executable named clock-gui is   `~/.clock/clock-gui/clock-gui`.  
Download clock.desktop and type in the Downloads folder the command : `sudo mv clock.desktop /usr/share/applications/`   
Download clock.jpg and put it in this path : `~/.clock/clock-py` so that the complete path is : `~/.clock/clock-py/clock.jpg`    

### With the script (very buggy at the moment)

Put the release extracted in your home folder.   
Extract it and change the directory in the terminal to the extracted directory.   
Type the command : `chmod +x install.sh`    
Then type the command : `./install.sh`   
The script will ask you your root password.    

### Also ...

You can also use a custom desktop file to have the icon or the executable wherever you want (or you could just modify my desktop file)
