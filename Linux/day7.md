## user and permission 
```
3 types of usser
1 root (0)
2 local (1000 tp 60,000+)
3 system (1-999)
```
<img width="1000" height="669" alt="Screenshot 2026-01-03 at 9 36 57 AM" src="https://github.com/user-attachments/assets/d6d4299f-39f6-4d47-972e-3bd51c7ae728" />


## add user 
- adduser ----> home and password assing 
- useradd ----> no home and password
- to user is created---->cat /etc/passwd

## sudo user 
- only root user can edit this file 
channge the configuration of etc/sudoers 
```bash
vim /etc/sudoers
```
```
%<username> ALL=(ALL)ALL
```
