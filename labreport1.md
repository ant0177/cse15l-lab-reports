# Lab Report 1: Remote Access 


## Step 1: Installing IDE
For step one, we need to install our IDE , which in this case we will be using VS Code. 

![vscode](https://user-images.githubusercontent.com/103216296/162666060-451f410a-b47f-41da-b249-86c1e9fa429d.png)

1. Go to the VS Code website here: [VS Code](https://code.visualstudio.com)
2. Click download
3. Run the installer file on your computer and follow the instructions
4. Open VS Code!

---

## Step #2: Remotely Connecting
We will be remotely connecting from our computer to a server using SSH (Secure Socket Shell) To do this we will be using the terminal in VS Code. 

1. Open a new terminal in VS Code, click "Terminal" on the top bar and then "New Terminal" 
2. Use the SSH command with your personal account information and enter your password.
```
ssh cs15lspaqx@ieng6@ucsd.edu
```
3. If it is your first time connecting you will likely see a message and in return just type yes.
4. After, a message will be displayed saying your are logged in.


![step2](https://user-images.githubusercontent.com/103216296/162666119-b5bca7c9-e97f-4bb4-9071-fdcb3ac7f0db.png)

---
## Step #3: Commands 
I then tried some commands while I was remotely connected.

* ls - lists the files
* cp - copy file
* mv - move
* cd - change directory
* touch - make file

![step 3](https://user-images.githubusercontent.com/103216296/162666192-a594bafc-e6db-4ffc-b98f-afa241b49123.png)

---
## Step 4: Moving Files Using SCP
1. Change the local directory to where the file you want to copy is located
2. Then follow the instructions from step 2 to remotely connect
3. After you are remotely connected run the scp command to copy the file
```
scp WehreAmI.java cs15lsp22aqx@ieng6.ucsd.edu
```
4. You will be prompted to log in again 
5. Your file will be copied and you can use ls to view the file


![scp](https://user-images.githubusercontent.com/103216296/162666247-517aceb1-4a3a-4e7e-b6ef-1cd07670960b.png)

---
## Step 5: Setting an SSH Key:
1. On your computer, run the command 
```
ssh-keygen
```
2. A prompt will pop up and respond with yes, then you will provide a password, but you can leave that empty for no password. 
3. We then need to copy the public ssh directory to the server.
4. Connect to the server using the SSH command and once your on the server run this command.
```
mkdir .ssh
```
5. After, logout and run this command scp /Users/<user-name>/.ssh/id_rsa.pub
cs15lsp22aqx@ieng6.ucsd.edu:~/.ssh/authorized_keys

6. You should now be able to run ssh and scp commands without using a password.
---

![move](https://user-images.githubusercontent.com/103216296/162666322-2de8433b-0b9f-44b2-93af-564db48585bb.png)
![loged in](https://user-images.githubusercontent.com/103216296/162666331-fefa9bdc-b99d-4ac3-9b6b-7eaae5beb350.png)

  
## Step 6: Optimize Remote Running
We can now do many different commands such as 
```
ssh cs15lsp22aqx@ieng6.ucsd.edu "ls"
```
This allows us to connect remotely and list all the files inside. We can also use semi colons to run many different comamnds at once using this method. 

  ![optimize](https://user-images.githubusercontent.com/103216296/162666373-87d59694-d3b8-4df1-adc7-a62e8711e200.png)

