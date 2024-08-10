# MariaDB-PHPMyAdmin

# How to set up a MariaDB server and connect phpMyAdmin on a Docker machine running Debian Linux:


##I am installing MariaDB, naming the instance ‘mar-Abdi,’ publishing port 3306:3306, and setting the password to ‘Abdi.’


![image](https://github.com/user-attachments/assets/0b014da1-8854-4c80-ab58-03173720861f)

 
 
## I am installing phpMyAdmin, linking it to the `mar-Abdi` container, and publishing port 8089:80.

![image](https://github.com/user-attachments/assets/afb10da8-7042-4c00-8d63-c4ed6d28ccd6)


 

##Both containers are installed in Docker, and I have started both the `mar-Abdi` and `myadmin containers.



 ![image](https://github.com/user-attachments/assets/218152ad-a39f-4244-83ce-30070ad91d67)


## Both containers are up and running.

##To view the running containers, use the command: `docker ps -a`.

![image](https://github.com/user-attachments/assets/e59d785c-d874-4667-b39c-5e1ef23d39d5)

 

## "Now, I will open my local web browser and enter my IP address along with the port number to access phpMyAdmin."

![image](https://github.com/user-attachments/assets/5d9fa9d1-cc53-4b6b-a64c-0929659f02a7)




 
##Now, I am importing the `Ziocode` database from my localhost to my VM's database server using phpMyAdmin.


![image](https://github.com/user-attachments/assets/bbceb41a-3008-42a2-a2f3-62b338ac7635)

 



##This screenshot demonstrates my access to the ZIP code database through a browser in my host OS, alongside an open terminal in my VM showing the output of `ifconfig` and `docker ps -a`, with relevant IP addresses and ports highlighted."


![image](https://github.com/user-attachments/assets/d2bef1c0-d7c0-4e34-8f1c-a293ccc261e6)



