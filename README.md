Git and GitHub Guide for Mr. Chen
Installing Git on Local Machine
Prerequisites
Ensure that your local machine meets the system requirements for Git.
Installation Steps
Visit the Git Website:

Go to https://git-scm.com/.
Download Git:

Click on the "Download" button and choose the installer for your operating system.
Run Installer:

Locate the downloaded installer file and run it.
Follow Installation Wizard:

Follow the instructions provided by the installation wizard.
Choose the installation directory, select components, and adjust system settings.
Verify Installation:

Open a command prompt or terminal and run git --version to verify the successful installation.
Creating a GitHub Account
Visit GitHub Website:

Go to https://github.com/.
Sign Up:

Click on the "Sign up" button and provide the required information.
Verify Email:

Verify the email address associated with your GitHub account.
Cloning Repositories to Local Machine
Open Git Bash or Terminal:

Open Git Bash (Windows) or Terminal (macOS/Linux).
Navigate to Desired Directory:

Use cd command to navigate to the directory where you want to clone the repository.
Clone Repository:

Get the repository URL from GitHub.
Run git clone <repository_url> to clone the repository.
Navigate into the Repository:

Use cd to enter the cloned repository directory: cd <repository_name>.
View Cloned Files:

Run ls (Linux/macOS) or dir (Windows) to view the files in the cloned repository.
20 Git Commands and Functions
git init:

Initializes a new Git repository.
git clone <repository_url>:

Clones a remote repository.
git add <file(s)>:

Adds file changes to the staging area.
git commit -m "Commit message":

Commits the staged changes.
git status:

Displays the status of changes.
git log:

Shows a log of commits.
git branch:

Lists all local branches.
git checkout <branch_name>:

Switches to the specified branch.
git merge <branch_name>:

Merges changes from the specified branch.
git pull:

Fetches changes from a remote repository and merges them.
git push:

Pushes local commits to a remote repository.
git remote -v:

Lists the remote repositories.
git fetch <remote_name>:

Fetches changes from a specific remote repository.
git remote add <remote_name> <repository_url>:

Adds a new remote repository.
git diff:

Shows the differences between the working directory and the last commit.
git reset <file(s)>:

Unstages changes for the specified file(s).
git revert <commit_sha>:

Creates a new commit that undoes changes of a previous commit.
git branch -d <branch_name>:

Deletes a local branch after it has been merged.
git stash:

Temporarily saves changes not ready to be committed.
git config --global user.name "Your Name" && git config --global user.email "you@example.com":

Configures your global Git user information.
Feel free to reach out if you have any questions or need further assistance! Happy coding Mr Chen.






