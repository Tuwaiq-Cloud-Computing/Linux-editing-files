# Linux-editing-working-with-files

- cksum securecopy.txt and save the output as screen shot

![cksum](https://user-images.githubusercontent.com/99265180/195600218-938b93bd-872c-4d04-8453-a5e92b796f27.png)

- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano
- again cksum securecopy.txt and save the output as screen shot and write your observation

![cksum2](https://user-images.githubusercontent.com/99265180/195600618-4c0ac27b-1d7a-4cb7-bec4-b04a60a25512.png)

The CRC and size of file changed.



- use the find command to find yourname.txt in your environment 

![find](https://user-images.githubusercontent.com/99265180/195600926-6886a32f-aa65-4c27-9abf-2d7724614c65.png)



- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output   

![grep](https://user-images.githubusercontent.com/99265180/195601089-f7c72afc-607f-4d7c-9f16-381b95f89976.png)

- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
![diff](https://user-images.githubusercontent.com/99265180/195601421-ad2dc882-d3a5-47a8-a759-87aa7c8fcddc.png)
