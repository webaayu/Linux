# Linux File Permissions (set executable permission to the given file ) 
#### check file with permissions  
```s
ls -l
```
#### All permissions denied
```s
chmod a+rx
```
or
```s
chmod 555
```
#### Check the permissions
```s
ls -l
```
### NOTE: Without read permission one can not get execulatable permission. it looks it gets permission but actually can't execute. 
