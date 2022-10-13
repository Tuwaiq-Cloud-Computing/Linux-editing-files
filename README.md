# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt 
----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot 

the number and the size are changed 
- use the find command to find yourname.txt in your environment 
- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output   
- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
