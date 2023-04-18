# simulator
command line program  that receives commands that run traffic from the host
usage:
   This executable file runs a command line program which recives one of these commands: add, change, delete, traffic, stop, gui,download.
   The traffic commands will prompt a message asking the user to enter an application (zoom/facebook/youtube) and run traffic of that application.
   The gui command openes a gui window that recieves commands.
   The add, change, delete commands execute linux tc  commands (https://man7.org/linux/man-pages/man8/tc.8.html) on a appliance, the simulator retrieves the IP address and credentials
   from the configuraion file config.ini attached - config.ini file should be edited to contain the ip and credentials of the appliance you wish to execute these commands on
   (the file should be placed in the same folder of the executable file).
   The download commands downloads a file.
   The stop commands stops all traffic from being generated/downloaded. 
   
   
   
