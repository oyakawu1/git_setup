# VERSION CONTROL

Version control is a system that keep tracks and manages any changes made in a file.

# THE IMPORTANT OF VERSION CONTROL

Some of the importance of version control are:
1. Reduced conflict
2. Error preventing
2. File recovery
etc

# WHAT IS GIT?
Git is a distributed version control system that keep tracks versions of file.

# WHAT IS GitHub?
GitHub is a prorietary developer platform that allows developers to create, store, manage, and share their file or code among them.

# DIFFERENCE BETWEEN GIT AND GITHUB.

Git is a free, open source version control tool that developers install locally on their personal computers, while 
Github is a pay-for-use online service built to run Git in the cloud.

# COMPREHENSIVE GIT AND GITHUB SETUP FOR BEGINERS.

1. Create a GitHub Account:
Navigate to the GitHub website. 
Click "Sign up" and follow the prompts to create your account. 
Verify your email address. 
Consider setting up two-factor authentication for added security. 
2. Install Git:
Git is a version control system that GitHub uses. You'll need to install it on your computer. 
Download the appropriate installer for your operating system from the Git website. 
Follow the installation instructions. 
Verify the installation by opening a terminal or command prompt and typing git --version. 
3. Configure Git:
Open your terminal or command prompt. 
Set your Git username and email using the following commands, replacing the placeholders with your information: 
Code

        git config --global user.name "Your Name"
        git config --global user.email "your.email@example.com"
You can verify these settings by running git config --global user.name and git config --global user.email. 
1. Create a Repository:
You can create a new repository on the GitHub website. 
Click the "+" icon in the top right corner and select "New repository". 
Give your repository a name and description. 
Choose a visibility setting (public or private). 
Optionally, initialize the repository with a README file. 
Click "Create repository". 
2. Add Your Code:
Navigate to the root directory of your project in your terminal. 
Initialize the directory as a Git repository using git init. 
Add your files to the staging area using git add . (to add all files) or git add <filename>. 
Commit your changes with a descriptive message using git commit -m "Your commit message". 
3. Connect to GitHub:
Add the remote repository URL to your local repository using git remote add origin <repository URL>. 
Push your local changes to the remote repository on GitHub using git push -u origin main (if your default branch is main) or git push -u origin master (if your default branch is master)
