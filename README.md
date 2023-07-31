# Attendance
This project was created to help you learn the basics of Git. Through this project, you learn how to perform essential Git operations, such as cloning a project, pulling changes, branching out, committing your changes, and pushing them to a remote repository.

### Prerequisites 
Before running the project, make sure you have installed [Git](https://github.com/git-guides/install-git) on your machine. 

To check if Git is installed run the following command:
`git --version`

## Cloning the project
- Above the list of files, click the green `<> Code` button.
- Copy the URL for the repository.
- Open the Terminal on your computer.
- Change the current directory to the location where you want the cloned directory to be placed.
- Type `git clone`, followed by the URL you copied earlier.

## Creating a new branch
- Check your current branch: Use the command `git branch` to see which branch you are currently on. If you are already on the main branch, you can skip the next step.

- Checkout to the main branch: use the command `git checkout main` to switch to the main branch.

- Pull the latest changes: Once you are on the main branch, use the command `git pull origin main` to fetch and merge the latest changes from the remote repository's main branch into your local main branch. Note: `origin` is the name of the remote repository. In most cases, `origin` is the default name given to the remote repository where the local repository was cloned from. However, it's possible to have multiple remotes, each with a different name.

- Now you have the latest changes from the main branch, and you can proceed to create a new branch using the `git checkout -b new_branch_name` command. `new_branch_name` should be replaced with the actual name of your branch (e.g. christy-antoun) 

## Add your changes
Inside the Attendance folder, create a new file and name it using this format: `christy-antoun.txt` 
Use the command `git add` followed by your file name to move it to the staging area. Note: `git add .` moves all files containing changes to the staging area.

## Committing your changes
A commit is accompanied by a commit message that describes the changes you made. To create a commit, use the following command:
`git commit -m "Your commit message here"`
The commit message should be in the present tense and explain the purpose of the changes.

## Pushing your changes
Use the following command to push your changes `git push origin new_branch_name`


## Creating a pull request
- Go to the original repository's page on GitHub.
- You should see a banner indicating that you've recently pushed a new branch. Click on the "Compare & pull request" button. Otherwise, go to pull requests and click on New Pull Request. 
- Select `main` as your base branch and compare your branch to it.
- Create the pull request and add Christy Antoun as a reviewer