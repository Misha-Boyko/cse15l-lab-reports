# CSE15L First Lab Tutorial

Hi CSE15L student! Today we're going to go over how to log into a course-specific account on ieng6.
<br />
## First we need to install VScode
We start by going to the installation page of [VScode](https://code.visualstudio.com/download)
and selecting the correct software for the machine we're working on. I work on a windows laptop so I installed the windows one.
After completing the instructions on the screen that show up for VScode 
(like selecting which path to install VScode to and default options) a screen should show up similar to
this:
![Image](_placeholder_)
<br />
## Next we will attempt to remotely connect
We need to access the accounts we have access to from our courses [found here](https://sdacs.ucsd.edu/~icc/index.php).
Once we can log in by typing our student information, we can see the accounts we have access to.
We need to change our password for our `cs15L...` account by pressing on the account and using the 
[Password Reset Tool](https://sdacs.ucsd.edu/~icc/password.php) and typing the `CS15L...` username 
when prompted. Next follow the instructions to change the password through the email and duo confirmation.
<br />
*In case of issues with this step read this:*
This step I personally had the most troubles with as my password was not working and the terminal 
kept outputting that I had put in the improper password. Even after rewriting my password in a plain text 
editor and copying it into the terminal box, I was unable to establish a connection. after about half an 
hour of waiting the terminal let me so I'd advise patience.
<br />
**Next we will use VScode to remotely connect**
Open a new terminal in VScode by navigating to the top of the window and clickling terminal->new terminal 
or the three bars->terminal->new terminal. Once the terminal opens we press the arrow done next to the + 
in the top right of the terminal screen. A drop down option should reveal bash or Git Bash if git bash 
is properly installed on your machine. Once the terminal page is open we run the command.
The `$ ssh cs15l...` where the `cs15l...` is replaced with the account username we obtained in 
the previous step followed by `@ieng6.ucsd.edu`. For example, my account username is `cs15lsp23bx`
Thus, I'd type `$ ssh cs15lsp23bx@ieng6.ucsd.edu`. After typing the command you should be prompted
with a question about the connection to which you can enter `yes`. Next, type the password
into the terminal (it will hide your typing so make sure be precise). Once connected you're
screen should look similar to mine:
![Image](_placeholder_)

<br />
## Finally, let's try a command
There are many commands to try here such as `cd` `cd ~` `ls -lat` `cat **pathname**` 
We can type any of these into the terminal (one at a time). For instance, I tried
`ls` and `cat per15` which is a path that does not exist.
![Image](_placeholder_)

