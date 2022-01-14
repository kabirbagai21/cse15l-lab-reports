

# CSE 15L Lab Report 1 #
# Kabir Bagai #

[Home](index.html)

**This is a tutorial for setting up VSCode, connecting to a remote server and running commands.**

**1. Installing VS Code**

Click on this [link](https://code.visualstudio.com/) to download VSCode for the appropriate type of operating system. When you've downloaded it sucessfully, the home screen should look something like this:

![Image](VS_Code.png)


**2. Remotely Connecting**

Now, we will remotely connect to the ieng6 server in the CS Lab. Each student is issued a course specific account to do so. To find your account, visit: [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

Once you have your account details (account name and password), 
copy the following command into the command line: 

`$ ssh cs15lwi22ajr@ieng6.ucsd.edu`

*note the account name is unique to me, place your own account name before the `@ieng6.uscd.edu`

After this, the setup should start and look something like the picture below with some additional prompts if it's your first time. 

![Image](ssh.png)


Note I have configured my ssh to not require a password, when yours starts, it will require you to enter the password associated with your account. 


**3. Trying Commands**

Next, try some different commands to navigate the filesystem. Here are some commonly used ones:

* `cd` - change directory
* `cd ~` - change to default directory
* `mkdir` - creates a new directory
* `li` - lists the contents of the directory
* `li -a` - lists the contents of the directory including hidden files
* `pwd` - prints working directory
* `cp` - copies files and directories

Here are examples of running some of these commands

![Image](samplecommands.png)

To log out of the remote server, type the command `exit`

**4. Using `scp` to Copy Files Over SSH**

