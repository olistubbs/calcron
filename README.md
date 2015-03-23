# calcron

This script will execute commands based on the name of the file they are held in.

For Example

`$ cat ~/calcron/201503231030

service httpd restart`


This will (or attempt to) restart httpd at 10:30am on 23rd March 2015

As `service httpd restart` will attempt to be ran as the user the cron is set to run as, it won't work unless ran as root, or as a user with the appropriate privileges 
