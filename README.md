# GitHub Tutorial
GitHub is a web-based version-control repository and Internet hosting service. It works on git and contains all it's version-control and code management facilities.

## Step 1
First and foremost, each of you will need a github account. It is fairly easy to register and similar to most of the other sites it offers login using your Gmail or other Social Network ID's.<br>
[Register Here](https://www.gihtub.com/join) <br>
Before continuing with the rest of the tutorial it is highly recommended that you go through the hello world tutorial offered by GitHub.<br>
[Hello World Tutorial](https://guides.github.com/activities/hello-world/)


## Step 2
After you're done with hello world tutorial, it is time for some hands on approach to the workflow in GitHub. FOSS club has chosen a workflow known as Fork and Pull Request workflow.<br>
In this type of workflow each user creates their own fork of the repository, makes changes and submits pull requests to be reviewed and merged by others.<br>
Forks are copies of a main repository which are available for individual users to edit according to their preferences.<br>
Submitting a pull request is the process where you send the changes you've made to the main repository so that others can view, comment, edit or give suggestion to improve the code. A pull request is finally merged to the master(or main) by one of the owners of the repository.
<br><br>
In this exercise you will be creating a file with your username as an introduction to git.<br><br>

* Firstly, you should fork this repository to your account. Press the "Fork" button on top right of the page and select your account to fork this repository.
* Next, goto your profile and find the fork.
* Go into the users folder and create a new folder named "yourusername"
* Go into the that folder and create a text file named "yourusername.txt"
* Edit it to set the contents as "Hi it's me @yourusername"
<br><br>
## Step 3
Next would be the turn to master the command line in Linux, because most of the time you would be accessing git and other programs through it.

It is assumed that you have a working Linux installation, either a Virtual or a normal one. If you need help with Linux installation please contact any of the Core Members and we'll be happy to help you out.


Some of the basic commands are:
* cd (Change Directory): This command is used to change the current working directory. For eg:
'''
cd directory_name
'''
will change the current working directory to directory_name
* ls (List Files): This command will list you all the files in the directory.
* cat [filename] (Print contents): This command will print out the contents of the file into the console. Usage eg:
'''
cat filename.txt
'''
* grep (Search command): grep is a powerful search tool that lets you search for a specific string in a number of files at a time. Example:
'''
grep "search_string" test_file.txt
'''
grep's reach goes way beyond this and it is suggested to learn more of this command if you plan to use command line tools to continue with your programming career.
* cp(Copy) : This command let's you copy files from one location to another.
'''
cp /path/to/source_file /path/to/target_file
'''
* mkdir(Make directory): A command to make a directory(folder) in the current working directory.
'''
mkdir directory_name
'''
* rmdir(Remove directory): Command to remove an empty directory.
'''
rmdir directory_name
'''

<br>
<br>
It is highly recommended that you check out the man pages(manual pages) of each of these commands to get a broader idea of their working. Man pages can be accessed by the following commands:
'''
man command_name
'''
Press q to exit the man page.
 <br>
