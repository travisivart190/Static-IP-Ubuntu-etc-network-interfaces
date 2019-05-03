# Static-IP-Ubuntu-etc-network-interfaces
How to Assign IP Addresses in /etc/network/interfaces and Add static route to 10.0.0.x 

Use these files as a template for editing your /etc/network/interfaces file. 

Use vim or nano to open /etc/network/interfaces. 
Make sure that the file looks similar to the example I've given, but make sure your IP addresses don't clash with others (Replace the X in the Address Field) .
After you do this, save and close vim by typing:
  :wq 
  
 
Once you've done that, make sure you reboot your machine. You should see the IP you configured when you run ifconfig
and should be able to ping 10.0.0.239.  

Thanks for reading, and browsing my Github!

TRiley
