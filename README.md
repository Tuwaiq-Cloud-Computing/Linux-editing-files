# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt 
----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot and write your observation:
This number has change after the nano-root to Ruba.txt
pic1: root pic2:Ruba.txt

- use the find command to find yourname.txt in your environment and save the output as screen shot 
- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output   
- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot

<img width="210" alt="cksum1" src="https://user-images.githubusercontent.com/113884959/196090285-cd7c063b-0116-4e74-91e2-cfabbb815d28.PNG">

<img width="209" alt="cksum2" src="https://user-images.githubusercontent.com/113884959/196090317-b06b3fb0-c90d-4010-b27e-0d40d378e7db.PNG">

<img width="175" alt="find" src="https://user-images.githubusercontent.com/113884959/196090349-1fd979b0-680a-439d-bf43-e530401764e6.PNG">

<img width="653" alt="grepasswd" src="https://user-images.githubusercontent.com/113884959/196090361-544fbe2d-2380-484b-81a8-bb89cc84426e.PNG">

<img width="754" alt="root" src="https://user-images.githubusercontent.com/113884959/196090231-a01490d6-8106-4d5b-9585-764d61e26592.PNG">

