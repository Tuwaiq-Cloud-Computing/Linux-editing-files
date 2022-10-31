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


#ANSWER

![Screenshot from 2022-10-31 08-06-18](https://user-images.githubusercontent.com/50146073/199042507-ee68697e-ee18-49f7-be98-3f5d7ad2d98e.png)
![Screenshot from 2022-10-31 08-07-30](https://user-images.githubusercontent.com/50146073/199042521-ab5a5b8a-1454-42e0-b916-91c967c5e9a0.png)
![Screenshot from 2022-10-31 08-09-44](https://user-images.githubusercontent.com/50146073/199042535-daf5e7ef-e61c-48b4-a918-1ae2fd223f3c.png)
![Screenshot from 2022-10-31 08-13-54](https://user-images.githubusercontent.com/50146073/199042546-82987c49-fe71-4291-a815-10d5cb0c0355.png)
