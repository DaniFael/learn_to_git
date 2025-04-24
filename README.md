# learn_to_git
this repository was made for the purposes of learning how to work with git:
that is, learn how to clone, push, pull...

<ins>how to clone a github repository:</ins>
1) in the online git repository, press on the green code button, and copy the URL link under HTTPS
2) open command prompt
3) using **cd**, navigate to the directory where you want to save the copy (clone) of this repository
4) in the command prompt write:
   
   **git clone the_URL_of_the_repository_that_you_coppied_in_step_1**


<ins>how to pull changes made to the github repository to your local version oon your computer:</ins>
1) open command prompt
2) using **cd**, navigate to the directory of the cloned copy of this repository
3) there write:

   **git pull origin branch_name**
   
   where branch_name is usualy called main.

<ins>how to add a new file to the locan version github repository:</ins>

you can simply add new files to cloned repository in the file explorer or in any other known way.

<ins>how to push changes made in your local version of the reposutory to the online repository:</ins>
1) open command prompt
2) using **cd**, navigate to the directory of the cloned copy of this repository
3) there write:
   
   **git status**
   
   this command will show if there are some changes in you local version that are not commited.
4) write:
   
   **git add the_name_of_the_file_that_has_been_added_or_changed**
   
   or:
   
   **git add .**
   
   where the . signifies "all"
5) write:
   
   **git commit -m "some_meaningfull_message_that_explains_the_changes_that_we_have_made_in_this_commit"**
6) write:
    
   **git push**
   
   or:
   
   **git push origin branch_name**
   
   if you want to push this to a specific branch.
   
   the default branch is usualy called main.
7) than a window will pop up and you will be asked to sign in to your github account.
   
<ins>more commands worth knowing:</ins>

**git brach** - 

this command shows all the branches of this project with an * next to the branch you are currently in.

**git branch new_branch_name**

this command creates a new branch with the name new_branch_name.

* note that to see this new branch online you will have to swich to this new branch using **git checkout new_branch_name** and than commit and push the changes from the new branch using git **push origin new_branch_name**.

**git checkout name_of_branch_you_want_to_move_to**

this command moves you from the branh you were in to the branch named name_of_branch_you_want_to_move_to. 

**link to a usefull youtube tutorial:**

https://www.youtube.com/watch?v=xnR0dlOqNVE
