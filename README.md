# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt 
----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
<img width="865" alt="Screen Shot 2022-10-13 at 3 16 00 PM" src="https://user-images.githubusercontent.com/105993032/196023359-9b51da13-ce07-4c39-993d-ac405cee1106.png">

- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot and write your observation
 observation: the number changed after changing the root name 
 <img width="865" alt="Screen Shot 2022-10-13 at 3 28 41 PM" src="https://user-images.githubusercontent.com/105993032/196023384-cf2025e2-6e02-4f52-9850-7c223fc6d4ed.png">

- use the find command to find yourname.txt in your environment and save the output as screen shot 
<img width="865" alt="Screen Shot 2022-10-13 at 3 32 47 PM" src="https://user-images.githubusercontent.com/105993032/196023403-2c9e7398-e122-431f-9e5b-8f474d5d3be0.png">


- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output  
<img width="865" alt="Screen Shot 2022-10-13 at 3 42 26 PM" src="https://user-images.githubusercontent.com/105993032/196023416-f11bea7f-8bcf-4983-a2ca-3c6b5beb384a.png">

- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
<img width="865" alt="Screen Shot 2022-10-13 at 3 45 07 PM" src="https://user-images.githubusercontent.com/105993032/196023422-c5df76b6-c1d3-4e82-af97-ea9da9f9f8e8.png">
