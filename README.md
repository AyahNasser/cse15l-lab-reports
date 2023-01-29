# cse15l-lab-reports
**Topic : Remote Access**
-
**Objectives:**
-
1- Installing VScode
-
2- Remotely Connecting
-
3-Trying Some Commands
-

**How to do each step**
-
1- Installing VScode : Go to VSCode_Install and follow the instructions for either installing VScode on a mac or windows. 
After you are done installing VScode, you will have something like this. 
 <img width="1440" alt="image" src="https://user-images.githubusercontent.com/122571192/212810099-f9575b01-5f4d-455c-b582-52bd69fffa99.png">
-
2- Remotely Connecting
First you need to open a terminal in either your VScode or the terminal on your mac. 
So, to open the terminal on your VScode, you need to go to (Ctrl or Command +, or use the Terminal → New Terminal menu option)
After opening the terminal successfully, you need to write ssh cs15lwi23zz@ieng6.ucsd.edu, but replace the **zz** letters with your the letters in your course-specific account.
-
Moreover, if this is your first time to connecting to this server, you will probably get a message like this:
-
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
- 
simply just type yes and press enter, then give your password and you are logged in.

After that you will get something like this, which means you logged in successfully.
<img width="598" alt="image" src="https://user-images.githubusercontent.com/122571192/212812474-1849dc87-2227-40af-b613-d6661959110b.png">
-
3- Run Some Commands
-
There are many commands you can try and run on either your computer, and on the remote computer after ssh-ing (use the terminal in VScode).
-
Here is some commands examples you can try running:
-
- cd ~
- cd
- ls -lat
- ls -a
- ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is one of the other group members’ username
- cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/
- cat /home/linux/ieng6/cs15lwi23/public/hello.txt
-
**What I learned from running some certain commands, and what I found intersting.** 
- For example, I ran cd ~ command to change the directory to Folder1 (See in the picture below).
- Another example, I ran ls command as well, which lists the contents of the current directory. 
- One more command that is not on the picture provided below, but I find it very interstring is pwd command. Pwd command prints out the current path name you are on. 

Here is an example of some commands I tried on my terminal: 
<img width="568" alt="image" src="https://user-images.githubusercontent.com/122571192/212813429-8b4ae587-0162-4017-8075-5faa83f1c449.png">
 -
Finally, in order to log out of the remote server in your terminal, you can use:     
  - Ctrl-D
  - Run the command exit

  











