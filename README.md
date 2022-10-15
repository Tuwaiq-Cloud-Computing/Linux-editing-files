# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt 
----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot and write your observation
- use the find command to find yourname.txt in your environment and save the output as screen shot 
- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output   
- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
![new 1](https://user-images.githubusercontent.com/113862309/196004054-87044e65-6829-4094-80ab-e33d47a1b22c.png)
![new 2](https://user-images.githubusercontent.com/113862309/196004059-5a1a512d-fee3-402e-8608-a34a7434f28c.png)
![new 3](https://user-images.githubusercontent.com/113862309/196004061-e3193f08-ebd9-4d74-8087-9e5590fedc7d.png)
![new 4](https://user-images.githubusercontent.com/113862309/196004062-72341173-d098-410d-8ea5-2058d96f0031.png)
![new 5](https://user-images.githubusercontent.com/113862309/196004066-cdfb4c88-3bce-4a79-be36-65ec3411d3c3.png)
![new 6](https://user-images.githubusercontent.com/113862309/196004072-3d65ef03-64b5-4b0d-852c-9d929037a303.png)
