# Create a Linux User with non-interactive shell

#### Login to the server 
```s
ssh username@server_IP
```
#### Privillage the user
```s
sudo su -
```
#### Check the user
```s
id <user name>
```
#### One can create a non-interactive shell user
```s 
adduser <user_name> -s /sbin/nologin 
```
#### Check the user
```s 
id <user_name>
```
#### Check the user permissions
```s 
cat /etc/passwd | grep <user_name>
```
#### Done
