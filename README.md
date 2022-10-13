# Linux-editing-working-with-files

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/syslog   ~/mydir/securecopy.txt 
Answer:
<img width="398" alt="first#3-Taska" src="https://user-images.githubusercontent.com/114053471/195597732-1f8d62a0-6d7d-4bdb-980d-a0795ae4e244.PNG">

----------------------------------------------------------------
- cksum securecopy.txt and save the output as screen shot
<img width="363" alt="output-of-checksum" src="https://user-images.githubusercontent.com/114053471/195597990-3c8a6ba9-f740-43b9-8fee-e7a3450bbcf2.PNG">

- open  ~/mydir/securecopy.txt with nano editor and replace all "root" keywords with yourname and exit the nano

<img width="304" alt="nano-Rawan" src="https://user-images.githubusercontent.com/114053471/195598061-7c909292-a92c-4c61-bf39-7397afe55f41.PNG">

- again cksum securecopy.txt and save the output as screen shot and write your observation
my observation : the number of charcactrs have been reduced & the clc has been changed as well.
screenshot: 
<img width="269" alt="cksum-second-try" src="https://user-images.githubusercontent.com/114053471/195598312-6906a087-9352-45ba-87be-6d811ffd07d4.PNG">

- use the find command to find yourname.txt in your environment 
<img width="217" alt="find-comm" src="https://user-images.githubusercontent.com/114053471/195598373-a251a6d2-0434-4f4c-a1e0-7b2a4596ae3f.PNG">

- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output   
<img width="500" alt="grep-command" src="https://user-images.githubusercontent.com/114053471/195598504-8291f60e-4da2-418c-9a67-f606439eee3c.PNG">


- use the diff command on /var/log/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot
<img width="500" alt="diff-comm" src="https://user-images.githubusercontent.com/114053471/195598548-2ae056b4-ad2e-4621-bda4-c712747e4e7c.PNG">
