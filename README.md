# Git-4-Dummies
****Git Basic Tutorial****

#####Prerequisites
- Create .ssh key and add your .ssh key into your git account.
- install git on your local machine.

#####Create instance of the project repository
- Clone : Clone operation creates the instance of the repository. Clone operation not only checks out the working copy, but it also mirrors the complete repository. 
- git clone via ****ssh_url****
ex : **git clone git@github.com:zigic88/Git-4-Dummies.git**
- then project will shown in your active directory

#####Create .git directory
- **git init** command creates .git directory to store metadata about the repository every time it reads the configuration from the .git/config file.
- go to project directory, then use command:
**git init**

#####Manage branch for development
- Branches are used to create another line of development. By default, Git has a master branch, which is same as trunk in Subversion. Usually, a branch is created to work on a new feature. Once the feature is completed, it is merged back with the master branch and we delete the branch.
- **git branch** command to get available branch in your project.
- **git branch [branch_name]** command to create new branch with name "branch_name"
- **git checkout [branch_name]** command to switch between branches.
- **git checkout -b [branch_name]** command to create and switch to new branch"
- **git branch -D [branch_name]"** command to delete branch.  
- **git branch -m [old_branch_name] [new_branch_name]** command to rename branch name.

## Commit your project changes
- After changes your project, then create staging for your changes.
- **git add . **
add all changes files
- **git add sortFields.java**
only add sortFields.java file
- **git commit -m "Add sort operation"**

### Check your git project status
- **git status -s**