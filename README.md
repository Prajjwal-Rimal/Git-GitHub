# Git-GitHub
GIT - version control system <br>
Version Control - way to track code changes

Directory -> Folder <br>
Terminal or command line -> interface to type text commands<br> 
CLI -> command line interface<br>
code editor -> space to write code<br>
repository(repo) -> folder where the project is kept / project folder

git -> tracks changes in code overtime <br>
GitHub -> online space to host all of the git repositories <br>
Markdown -> what the project is about what it does 

Always write proper commit messages <br>
We can see commit history from the history, see what was added +means added, - means that was deleted, nothing means it stays the same

# After git installation
------------------------
1. Open git bash
2. $ git config --global user.name "username" <br>
3. $ git config --global user.email "email" <br>
// used to configure username and email, these details will be present in each of the commits we make <br>
4. go to code editor terminal and select it to git bash

# Commands
--------
## cd -> change directory <br>
1. cd (name of the folder)
2. cd ../foldername (to change the directory to the parent folder or other folders)


## ls -la or la -> list everything in the directory including hidden folders


## clone -> bring a repository to the local machine from the GitHub <br>
1. git clone (repositor url/ssh)


## add -> track your file and changes in git <br>
1. git add . // keep track all of the files <br>
2. git add (name of the file) // keep track of a single file <br>
3. git add (name of the folder) // keep track of a folder <br>
4. git add -A // add all files and folders <br>
generally we use the dot (.) to add all files<br>
After using the add all the changes have been tracked and are ready to be comitted to the repository


## commit -> save file in git <br>
1. git commit -m "message" // used to add messages. Messages are needed to commit.messsage generally includes what and a why is the commit necessary<br>
2. git commit -m "message" -m "description" // used to add a message or a description <br>
3. git commit -am "message" // used to add a message and add all files
This makes the code save locally


## push -> upload files to the repository from the device being used <br> 
1. git push origin main // used to upload files to the repository<br>
2. git push -u origin main // used to upload files to the repository and set the upstream. <br>
origin -> name of the repository<br>
main -> name of the branch <br>
upstream -> used to set the branch to the remote repository<br>


## pull -> bringing changes from the repository to the device being used <br>
-> pull request : request to pull code from one branch to another<br>
-> once made a pr anyone can view  the code comment on it ask us to make changes or updates<br>
-> we can also update the code as long as it on the same branch we are making PR with<br>
-> once pr is merged we genreally delete the source or feature branch <br>
-> if other changes needed repeat the cycle<br>

1. git pull origin feature-learning // used to bring changes from the repository to the device being used<br>


## status -> shows all of the files that were updated, created, or deleted but havent been saved in a commit yet
1. git status 


## init-> -> creates a new repository in the current directory
1. git init 

## remote -> used to connect to the repository
1. git remote add origin (url/ssh) -> adds a remote repository to the local repository<br>
2. git remote -v -> shows the remote repository that is connected to the local repository <br> 

## Git branch -> used to create a new branch in the repository
-> master / main branch is the main or the default branch in the repository <br>
-> we can also make another branch <br>
-> the code on master and feature will be same, changes to the created branch will be saved on the feature branch only<br>
-> branches dont know what comit have been made to them <br>
-> branches only hold the changes made to them <br> 
-> we can switch between branches <br>
-> useful for feature testing, testingg ccode is not saved in the main branch <br>
-> after testing we can merge the feature branch to the main branch<br>
-> hot fix branch is used to fix bugs in the main branch<br>

1. git branch -> shows all the branches in the repository<br>
2. git checkout -b (name of the branch) // to create a new branch<br>
3. git checkout (branch name) // switches between branches
4. git branch -d (branch name) // deletes a branch<br>
5. git merge featuere // merges the feature branch to the main branch<br>
-> merge conflicts: multiple people can change the same file <Br>

## Diff-> used to see the changes made to the code
1. git diff (branch name) // shows the changes made to the code<br>
-> its recommended to push the branch independantly before commiting changes to the main branch<br>
