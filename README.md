# cpnt-201-project

## Cloning the repo

**STEPS**

- First Go to [Github](https://github.com/)
- Select the Repository you have created for that project
- - Go to Code section on left side of the webpage
- Copy the https link for that repository
- Go to Visual studio clone and write below command to clone
- git clone [repo name](https://github.com/chai-py/cpnt-201-project.git)

## Create a new branch

- there are 2 ways to create new branch

  1. git branch (name of branch you want to create) - this will create only new branch and not checking out from current branch
  2. git checkout -b (name of branch) - this will create new branch and check out from current branch

## Make Changes

- When you make any changes to to your code you need to make sure you are making changes in correct branch
- When you make any changes you need to write below command to update changes in your local repo

1. git add . (to add your changes)
2. git commit -m "write comment of cahnges"( used to commit your changes)
3. git push (to push changes to your remote repo)

## Submit a pull request

- When you need to pull code from remote repo to local repo , you need to use below command
- When multiple team member collobrate & working on same code, git pull is used to pull changes made by other team members

**NOTE** : Make sure your you have created and connected to remote repository to pull

- git pull
