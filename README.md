# learn_to_git
this repository was made for the purposes of learning how to work with git:
that is, learn how to clone, push, pull...

<ins>how to clone a github repository:</ins>
1) in the online git repository, press on the green code button, and copy the URL link under HTTPS
2) open command prompt
3) using cd, navigate to the directory where you want to save the copy (clone) of this repository
4) inthe command prompt write:
   **git clone** the_URL_of_the_repository_that_you_coppied_in_step_1

<ins>how to add a new file to the locan version github repository:</ins>
* you can simply add new files to cloned repository in the file explorer or in any other known way.

<ins>how to push changes made in your local version of the reposutory to the online repository:</ins>
1) open command prompt
2) using cd, navigate to the directory of the cloned copy of this repository
3) there write:
   git status
   this command will show if there are some changes in you local version that are not commited.
4) write:
   git add the_name_of_the_file_that_has_been_added_or_changed
   or:
   git add .
   where the . signifies "all"
5) write:
   git commit -m "some_meaningfull_message_that_explains_the_changes_that_we_have_made_in_this_commit"
6) write:
   git push
   

<ins>how to pull changes made to the github repository to your local version oon your computer:</ins>

