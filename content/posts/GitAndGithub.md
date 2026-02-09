+++
title = 'GIT AND GITHUB GUIDE'
date = '2026-02-03T12:33:47+05:00'
draft = false
+++
## VERSION CONTROL SYSTEM (VCS) :
A Version Control System (VCS) is a tool that tracks changes made to files or source code over time.
VCS allows you to :

1. Save versions(snapshots of your projects) of your project or code at any time.
2. Compare changes between different versions.
3. Undo mistakes by restoring older versions.
4. Collaborate with other developers without overwriting each others work.

## DISTRIBUTED VERSION CONTROL SYSTEM (DVCS) :
A Distributed Version Control System (DVCS) is a type of version control system where every developer in the team has a complete local copy of the entire project repository including its history

### AFTER THIS YOU MUST BE WONDERING THAT WHAT IS GIT AND GITHUB:

## GIT :
Git is a version control system.It help us to track changes in code and also to track changes made by various developers(e.g commit helps us to do this) , history of code and also in collaboration(e.g working with a team on a project).

1. It is popular,free and open source.
2. It is fast and scalable(it can efficiently handle large as well as small projects without any performance issues).

## GITHUB :
A cloud based platform (A cloud-based platform is a service or software that runs on the internet instead of your local computer. You access it through a web browser or an app, and your data and applications are stored on remote servers(computers that are located somewhere else instead of your local computer) managed by a company.) for hosting git repositories .
### IN SIMPLE WORDS :
A website that allows developers to store,share and manage their code using git and collaborate on code over the internet.It is widely used for collaboration and open source projects.

[Github](https://github.com)

## BASIC TERMINOLOGIES:

### Repository (Repo) :
A repo is a project folder that Git tracks. It stores your files and their history.

### Commit :
A commit is like saving your work with a message explaining what you changed.

### Staging Area :
Before committing, files go to a staging area ,a temporary space.

### Clone :
Copying a GitHub repo to your computer.

### Push :
Sending your files from your computer → GitHub.

### Pull :
Getting the latest files from GitHub → your computer.

### Branch :
A separate version of your project. Main branch = main or master.
Branches help you test changes without breaking the main project.

### README file :
A file that explains your project. GitHub shows it on your repo home page.

## INSTALLATION OF GIT IN UBUNTU :

### STEP 1 :
Open your terminal in Ubuntu and enter command **git** to see if GIT is already installed or not.

![Alt text for the image](/images/T1.png)

### STEP 2 :
Enter command **sudo apt update** to check for new versions of software(apps,programs) on your PC or to tell your Linux computer to look for the new updates for the apps and programs it can install.

![Alt text for the image](/images/T2.png)

After this , enter the password of your ubuntu and after this clear your terminal by entering this command **clear**.

### STEP 3 :
Now enter command **sudo apt install git** and after that enter **y** for the continuation of installing GIT.

![Alt text for the image](/images/T3.png)

### STEP 4 :
Now again clear your terminal by **clear** command and once GIT is completely installed enter command **git --version** to check the version of your installed git.

![Alt text for the image](/images/T4.png)

Now the git installation is completely done.

### STEP 5 :
### CONFIGURING GIT :

### WHAT IS CONFIGURATION :

Generally , it refers to the process of defining settings and parameters that controls how a system software or tools should behave.

In case of GIT,Configuring Git means creating settings (Key_Value pairs) that tells Git who you are and how it should work.

1. Key(Name or Label) —> user.name,user.email.
2. Value(Information stored for that label or name) —> your name,your email.
3. Together they create a Key-Value pair.
4. Enter these commands.

![Alt text for the image](/images/T5.png)

The Git is successfully installed and configured.

### STEP 6 :

### INTEGRATING GIT WITH GITHUB :
### FOLLOW THE GIVEN STEPS:

1. Sign in to your GITHUB account.
2. Create new repository by clicking on + icon.
3. Now add name and description.
4. Turn on the READme file.
5. Now click on create it.
**FINALLY** , You’ll see that a new repository is created.

![Alt text for the image](/images/T6.png)

### STEP 7 :
Now go back to terminal and enter command **pwd**.

### STEP 8 :
Enter command **mkdir your folder name**.It’ll create a folder and enter command **cd your folder name**.

**e.g** Here **project** is my folder,likewise you can add yours.

![Alt text for the image](/images/T7.png)

### STEP 9 : CLONING OF REPOSITORY
Follow the given steps :

1. Click on the repository.
2. After this, click on code and then click on HTTPS and copy that url.
3. Now enter command **git clone** and here paste (ctrl+shift+v) your url.
4. Press enter which is going to clone your repository.
5. Enter command **ls**.
6. You’ll see your cloned repository there.

![Alt text for the image](/images/T8.png)

7. Enter command **touch file name** for creating a file and enter command **ls file name**.
8. Now enter ls file name.
9. Enter command **nano file name**.
10. Now enter whatever you want in that repository and then save it through ctrl+o.
11. File name to write : your file name and exit by ctrl+x.

![Alt text for the image](/images/T9.png)

### STEP 10 :
### PUSHING FILE FROM GIT TO REPOSITORY IN GITHUB:

Enter command **git status**.
It’ll show untracked files(which means these files are not tracked by git till now).

![Alt text for the image](/images/T10.png)

To add this to your GIT , enter command **git add file name**
To commit , enter command **git commit -m any name**

![Alt text for the image](/images/T11.png)

###Why we have used this commit ? So that we should remember what changes have we made in our file.

![Alt text for the image](/images/T12.png)

This means that you are now good to go with pushing your your local commits to remote repository in GitHub.

After this enter command **git push main origin**.

### STEP 11 :

After that enter your username and password but it doesnot accept your ubuntu password.Instead, GitHub requires a Personal Access Token (PAT). This token acts like your “GitHub password for terminal”.

Follow these steps :

1. Open GitHub.
2. Click your profile picture (top-right).
3. Go to Settings.
4. Scroll to the bottom → Developer settings.
5. Click Personal access tokens.
6. Select Tokens (classic).
7. Click Generate new token
8. Enter note (any name).
9. Select time.
10. Select all the boxes.
11. Scroll down → click Generate token.
12. Copy the token.

![Alt text for the image](/images/T13.png)

**NOW** When terminal asks for password → paste this token.
The password will not appear and you have to press enter.
After this appears, this means that your file has now successfully pushed into remote repository.

As i click on c programming code , my file appears.

![Alt text for the image](/images/T14.png)
![Alt text for the image](/images/T15.png)

**GOOD LUCK**
