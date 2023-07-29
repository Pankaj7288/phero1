# Git turotial

## This is Git & Github Tutorial

1. The First think we need to do, is to check if Git is properly installed.

   `Git --Version`

## Configure Git

1. Now let Git know who you are. This is important for version control systems, as each Git commit uses this information:

   `git config --global user.name 'YourName'`
   `git config -- global user.email 'YourEmail@mail.com'`

2. Use **--global** to set User Name and Email for **every repository** on yout computer.
3. If you want to set the User Name and Eamil to current repository, you can remove **--global**.

## Initilize Git

1. You have navigated to the correct folder, You can Initilize Git to the on the folder:

   `Git init`

2. You Just Create Yout first repository.

## Git Adding New Files

1. You can going to use a simple HTML File like **Index.html**
2. Now we can chech Git **Status** and see it is a part of our repo.

   `git status`

3. File in a git repository folder can be in one of two status: **Tracked** & **Untracked**

## Git Staging Environment

1. We can add our file to the Staging Environment:

   `git add Index.html`

2. The file to be **Staged**. Let's Check the status:

   `git status`

3. Now the fiel has been added to the staging enviroment.
4. **Add More Than One File**: You can also add more than one file at a time.
5. Now we can add another file **style.css** & and update **Index.html** to include _stylesheet_
6. Now add all file in the current directory to the Staging Environment:

   `git add --all`

7. Now all 2 files are added to the Staging Environment.
8. Tho short hand commant for **git add --all**:

   `git add -A`
   `git add .`

9. You can use **git add .**.
10. Let's Check the status:

    `git status`

11. Now all file are added to the Staging Environment and we are ready to our first _comit_.
