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
cd -> change directory <br>
1. cd (name of the folder)

ls -la or la -> list everything in the directory including hidden folders

clone -> bring a repository to the local machine from the GitHub <br>
1. git clone (repositor url/ssh)

add -> track your file and changes in git <br>
1. git add . // keep track all of the files <br>
2. git add (name of the file) // keep track of a single file <br>
3. git add (name of the folder) // keep track of a folder <br>
4. git add -A // add all files and folders <br>
generally we use the dot (.) to add all files<br>
After using the add all the changes have been tracked and are ready to be comitted to the repository

commit -> save file in git <br>
1. git commit -m "message" // used to add messages. Messages are needed to commit.messsage generally includes what and a why is the commit necessary<br>
2. git commit -m "message" -m "description" // used to add a message or a description <br>
This makes the code save locally

push -> upload files to the repository from the device being used <br> 
1. git push origin main // used to upload files to the repository<br>
origin -> name of the repository<br>
main -> name of the branch <br>

pull -> bringing changes from the repository to the device being used <br>

git status -> shows all of the files that were updated, created, or deleted but havent been saved in a commit yet

git init -> creates a new repository in the current directory
