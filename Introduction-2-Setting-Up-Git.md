> [Wiki](Home) ▸ Setting Up Git

# Setting up Git #

First you should head over to the [Git download page](https://git-scm.com/downloads), then download and install the **Git command line interface**.

If you really, really don't want to use the command line interface, you can get [a graphical interface for Git from GitHub](https://desktop.github.com/).<br>
[[https://desktop.github.com/images/screens/windows/main.png|alt=GitHub Desktop]]<br>
You can use this instead of the command line if you want.

Otherwise, once you've downloaded and installed Git, open up **Git Bash**.

## Git Bash ##
Now, if you've not used a command line interface before, this might look quite scary.<br>
Don't panic! This guide will walk you through the basics you need to know.

[[http://i.imgur.com/pUsKh8W.png|alt=Git Bash Window]]

When entering commands, type in the command and press **enter** to submit it.<br>
Git Bash puts a **$** at the start of each line to indicate it has finished the previous command and is ready for input.

### The basics ###
We will first need to tell Git who we are so any changes we make are attributed to us.

To configure Git, you will need to enter the following commands.<br>
**Type in one line at a time and press enter after each.**

Make sure to add YOUR_GITHUB_EMAIL_HERE and YOUR_NAME_HERE.
* git config --global user.email "YOUR_GITHUB_EMAIL_HERE"
* git config --global user.name "YOUR_NAME_HERE"
* git config --global core.askpass ''

_The last line disables a pop-up box whenever you need to enter your GitHub credentials and instead allows you to just enter it through Git Bash._

[[http://i.imgur.com/QDcG8ky.png|alt=Configure Git Bash]]
<br><br>

_If you want to use Git Bash as little as possible, you can use your operating system's native file manager (e.g. "explorer" in windows) and just use Git Bash for Git-related things._

<br>
> Next - [Git Bash Explained](/BadgerCode/HackSocGitBasics/Wiki/Introduction-3-Git-Bash-Explained.md)