# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt
----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
<img width="346" alt="ck-command" src="https://user-images.githubusercontent.com/114076124/196025726-73f0af2a-766f-45c9-ba12-405a9e595ab6.PNG">

- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot and write your observation - the CRA its changed and byte.
<img width="225" alt="ck1 command" src="https://user-images.githubusercontent.com/114076124/196025807-ede7560c-2adc-497b-ad60-b651688cc203.PNG">

- use the find command to find yourname.txt in your environment and save the output as screen shot 
- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output  
<img width="899" alt="findPassword" src="https://user-images.githubusercontent.com/114076124/196025834-20b3e93f-012a-4baf-8ed5-8eb3ed590768.PNG">

- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
<img width="696" alt="diff-command" src="https://user-images.githubusercontent.com/114076124/196025843-0b39d298-aebf-40bd-9995-97caf6ed8171.PNG">

