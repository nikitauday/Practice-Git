# GitHub
Andreessen Horowitz announced a whopping $100 million investment in GitHub this week. You can read commentary and speculation all over the web about what GitHub will do with the money, whether this was a good investment for Andreessen Horowitz and whether taking such a large investment is a good thing for GitHub.

But what the heck is GitHub and why are developers so excited about it? You may have heard that GitHub is a code sharing and publishing service, or that it’s a social networking site for programmers. Both statements are true, but neither explain exactly why GitHub is special.

At the heart of GitHub is Git, an open source project started by Linux creator Linus Torvalds. Matthew McCullough, a trainer at GitHub, explains that Git, like other version control systems, manages and stores revisions of projects. Although it’s mostly used for code, McCullough says Git could be used to manage any other type of file, such as Word documents or Final Cut projects. Think of it as a filing system for every draft of a document.

# Welcome to the tutorial of getting started with Git.

## Step 1
First and foremost, each of you will need a github account. It is fairly easy to register and similar to most of the other sites it offers login using your Gmail or other Social Network ID's.<br>
<br>
[Register Here](https://www.github.com/join) <br><br>
<img src="http://i.imgur.com/eeWND4m.png"></img>

Before continuing with the rest of the tutorial it is highly recommended that you go through the hello world tutorial offered by GitHub to get familiar with the github workflow.<br>
[Hello World Tutorial](https://guides.github.com/activities/hello-world/)


## Step 2
Before doing this step you have to install Git client in your system. 
<br>
<br>
<a href="http://git-scm.com/download/mac"><img src="http://image.prntscr.com/image/3db58348aece46f597293368e5a4bbd9.png" target="_blank"></a>
<br>
<br>
<a href="http://msysgit.github.io/"><img src="http://image.prntscr.com/image/eaafaf6722284064a1172c682ffb7466.png" target="_blank"></a>
<br>
<br>
<a href="http://git-scm.com/book/en/Getting-Started-Installing-Git"><img src="http://image.prntscr.com/image/65ba4f31800e466082d05c3aaa89bd60.png" target="_blank"></a>
<br>
For most Linux systems Git is already pre-installed.
<br>
<br>
### Now time to get your hands dirty and get into Git. 
<br> 
If you're having trouble with the names and terms used in github, go [here](https://help.github.com/articles/github-glossary/) and read through the definitions.
<br>

Submitting a pull request is the process where you send the changes you've made to the main repository so that others can view, comment, edit or give suggestion to improve the code. A pull request is finally merged to the master(or main) by one of the owners of the repository.
<br><br>
In this exercise you will be creating a file with your username as an introduction to git.<br><br>

* Firstly, you should fork this repository to your account. Press the "Fork" button on top right of the page and select your account to fork this repository.
<br>
Forks are copies of a main repository which are available for individual users to edit according to their preferences.<br>
<img src="http://i.imgur.com/Ayvkflu.png"/></img>
<br>
* Next, goto your profile and find the fork or the copy of the main repository.
* Click the clone or download green icon on your fork.
<br>
<img src="http://i.imgur.com/ywyNYpp.png"></img>
* Go to your terminal, where git is installed and paste `git clone https://github.com/<your_username>/Practice-Git`
<img src="http://i.imgur.com/iIUdqEf.png"></img>
* go into Practice-Git and go into `submit-a-pull-request` folder and make a folder with your own github username and inside make a file called `helloworld.md` and inside it add something about yourself and commit the file. More detailed instructions are given below
<br><br>
## Step 3
Next would be the turn to master the command line in Linux, because most of the time you would be accessing git and other programs through it.

It is assumed that you have a working Linux installation, either a Virtual or a normal one. If you need help with Linux installation please contact any of the Core Members and we'll be happy to help you out.


Some of the basic commands are:
* cd (Change Directory): This command is used to change the current working directory. For eg:
```
$cd directory_name
```
will change the current working directory to directory_name
<img src="http://i.imgur.com/7qvL5V8.png"></img>
* ls (List Files): This command will list you all the files in the directory.
<img src="http://i.imgur.com/e1G841o.png"></img>
* cat [filename] (Print contents): This command will print out the contents of the file into the console. Usage eg:
```
$cat filename.txt
```
* grep (Search command): grep is a powerful search tool that lets you search for a specific string in a number of files at a time. Example:
```
$grep "search_string" test_file.txt
```
grep's reach goes way beyond this and it is suggested to learn more of this command if you plan to use command line tools to continue with your programming career.
* cp(Copy) : This command let's you copy files from one location to another.
```
$cp /path/to/source_file /path/to/target_file
```
* mkdir(Make directory): A command to make a directory(folder) in the current working directory.
```
$mkdir directory_name
```
* rmdir(Remove directory): Command to remove an empty directory.
```
$rmdir directory_name
```
* touch (Create): Command to create a file.
```
$touch file.txt
```
will create file.txt in current directory.
* nano(Command line rext editor): Opens up nano, a text editor in the console to edit files. Creates a new file if the filename does not exist. Ctrl+O to save. Ctrl+X to exit.
```
$nano file.txt
```
Opens file.txt to edit. Creates file.txt if it does not exist.
* vi/vim(Command line text editor): Opens vi/vim a very popular text editor that is a little bit hard for beginners to get in touch with. It is only recommended that you use it after you have become familiarized with it's commands and shortcuts.

<br>
It is highly recommended that you check out the man pages(manual pages) of each of these commands to get a broader idea of their working. Man pages can be accessed by the following commands.<br>

```
$man command_name
```
Press q to exit the man page.

 <br>
 The shell commands are not limited to these and further reading and learning is advised.
<br>

## Step 4
In this step we will go further into the command line tools of git.

Use your package manager to install git on your system. Some systems come with git pre-installed but update it to use the latest version of it.

Use command:
```
$git --help
```
to see a list of all commands and their descriptions.

Codecademy has a really good tutorial on using the git command line.
[Codecademy Git Tutorial](https://www.codecademy.com/learn/learn-git)
git command line and linux command line
## Step 5

Once you're familiar with command line tools, it is time to get hands on approach on that as well.
Use git command line tools to do something similar as to what you've done in step 2.

* Clone your fork into a local directory. Hint:
```
git clone https://www.github.com/yourusername/yourrepo.git
```
* Add another file in the users directory named "yourusername-command_line.txt"
```
$cd users
$touch yourusername-command_line.txt
```<img src="http://i.imgur.com/3wqFmnH.png"></img>
* Edit it's contents to be "I made this with the command line."
```
$nano yourusername-command_line.txt
```<img src="http://i.imgur.com/7zP57QQ.png"></img>
* Add upstream as remote to pull from it.
```
$git remote add upstream https://www.github.com/fossmec/practice-sess.git
```
* Pull the contents to make sure your fork is up-to date.
```
$git pull upstream master
```
* If it is not, merge the upstream master to your master.
```
$git merge upstream/master
```
* Add, Commit and Push the contents to your fork.
```
$git add .
$git commit -m "Your commit message here"
$git push
```
Note: when you are asked for username and password, type in your e-mail address rather than your github username.
* Goto http://github.com/fossmec/practice-sess and submit a pull request for your fork.
Note: If you are confused with head fork and base fork, remember that merges are done from head fork to base fork so be careful with your pull requests.
