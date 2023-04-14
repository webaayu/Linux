# disable root login
#### login with server
```s
ssh username@ip
```
#### install vim
CentOS
```s
yum install vim
```
#### Open the file 
```s
vim /etc/ssh/sshd_cnfig
```
#### change permission
```s
PermitRootLogin no
```
#### save
```s
:wq!
```
#### restart service
```s
sudo systemctl restart sshd
```
#### Done
