# Cloud-PC
If like me, you are annoyed by the outrageous price of MS Windows 365 Cloud PC, use this script.
This script will allow you to transfor ANY modestly powerful PC (with vt-x/amd-v) into a Windows Cloud PC box.
# How to use
First, go into the BIOS of the PC and enable vt-x or amd-v.  It is reccommended to have at least 8gb ram but you can get away with less.

## Setup 

Make sure to have a windows ISO on the HDD you will be asked for the ISO path on boot
Download the script: 

wget (insert script URL)

Then run it and follow the prompts

chmod +x cloudpc.sh && ./cloudpc.sh

Remember the VNC port that you set 


Reboot

# VM Setup

By Default Only 1 VM will be Created and all the VM's that have been created will start on boot.(You can add more scroll down) 

Navigate to http://YOURMACHINEIP:8080/guacamole in any web browser 

The default username and password is Username:guacadmin Password:guacadmin you should change this

Click the User Profile in the Top Right Corner, then settings.  

Go to connections, then new connection.


## Credits

Guacamole Install Script https://github.com/MysticRyuujin/guac-install

Apache Guacamole https://guacamole.apache.org/

The Tianocore EDK Project https://github.com/tianocore/edk2

Myself









