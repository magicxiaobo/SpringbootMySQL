# SpringbootMySQL
#3


1. Install MySQL
(1). After install the mysql community edition in mac, its status can be checked in System Preference/MySQL.
(2). It's installation location is /usr/local/mysql, to access the MySQL from terminal, you can run below command:

/usr/local/mysql/bin/mysql -u root -p

Then enter the password for root.
You also can set the installation path to the MacOS environment, so that you don't have to enter the long path from root direcotry 
to startup MySQL.

open .bash_profile in home direcoty, add below line:

export PATH=/usr/local/mysql/bin:$PATH

save and exit, run: source .bash_profile to reload the bash profile. 

Now, you can just run the command: "mysql -u root -p" to start MySQL.

