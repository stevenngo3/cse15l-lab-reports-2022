# Lab Report 1
**1. Installing VSCode**
* Went to the Visual Studio Code website and followed the instructions to install VSCode
* After it was done installing, I opened it up

[Link to Visual Studio Code website](https://code.visualstudio.com/)

[Here is what VSCode looks like opened up.](https://1drv.ms/u/s!Al3nbU1sQBD-kzSMtUHNh1s69XSl?e=CjLU2o)

**2. Remotely Connecting**
* Installed a program called OpenSSH, which is a program that connected my computer to other computers that have this kind of account
* Connected to the remote computer in VSCode with its terminal

[This is what it looks like after being connected.](https://1drv.ms/u/s!Al3nbU1sQBD-kzWxVWPIENxmcvqV?e=6Mn8ea)

**3. Trying Some Commands**
* Ran some commands such as cd, ls, cp /home/linux/ieng6/cs15lsp22/public/hello.txt ~/, etc.
* Looked like most commands worked as there were no errors showing up
* Got denied permission from the following commands: "cp /home/linux/ieng6/cs15lsp22/public/hello.txt ~/" and "cat /home/linux/ieng6/cs15lsp22/public/hello.txt"

[This is what happened after running some commands.](https://1drv.ms/u/s!Al3nbU1sQBD-kzOzqiRvrotsBRUm?e=RqyltQ)

**4. Moving Files with scp**
* Created a file in VSCode called "WhereAmI.java"
* Ran the scp command in the terminal and then logged into ieng6 with ssh
* Ran the ls command in the terminal and saw the "WhereAmI.java" file in my home directory
* Ran the javac and java command in the terminal, the OS and directory were different (Linus)

[This is what the file WhereAmI.java looks like.](https://1drv.ms/u/s!Al3nbU1sQBD-kzKdSLU9jVpnqjO8?e=N7XOiT)

[This is the outcome of running these commands.](https://1drv.ms/u/s!Al3nbU1sQBD-kzEVTZimvmCFFEcW?e=JZty0H)

**5. Setting an SSH Key**
* Ran the ssh-keygen command in the terminal to create a pair of files (public key and private key)
* Entered (/Users/<user-name>/.ssh/id_rsa): /Users/<user-name>/.ssh/id_rsa to save the key
* Asked me to enter a passphrase (entered nothing to continue)

[This is the outcome of running ssh-keygen.](https://1drv.ms/u/s!Al3nbU1sQBD-kzCFL39k-g0HfRaq?e=Rz8dYb)

**6. Optimizing Remote Running**
* Ran the command ssh cs15lsp22zz@ieng6.ucsd.edu "ls" in the terminal
* Ran the command cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI in the terminal

[This is the outcome of running these commands.](https://1drv.ms/u/s!Al3nbU1sQBD-ky817zUJmetEJLaJ?e=MfSvyX)
