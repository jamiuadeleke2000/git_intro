                        ALL ABOUT GIT & GITHUB
                    ================================


* HOW GIT WORKS
-----------------------------

                         Add file                   Commit file
==> "Working Directory" ===========> "Staging Area" ===========> ".Git Directory"
          /\                                                            |
           |                                                            |
           |                                                            |
           |                                                            |
           |----------------------- CHECKOUT ---------------------------|


* BASIC COMMANDS IN GIT
-----------------------------
S/N|Git Basics |                   Purpose                           |Git Command
=================================================================================
1. |Git Init   |To initialize or start Git terminal/command          |git init
---------------------------------------------------------------------------------
2. |Git Add    |To add a file from working directory to staging area |git add <file_name_to_add>
---------------------------------------------------------------------------------
3. |Git Commit |To move file added, frm staging area to git directory|git commit -m "your present tense message goes here"
---------------------------------------------------------------------------------
4. |Git Status |To check the current status of the git terminal      |git status
---------------------------------------------------------------------------------
5. |Git Log    |To check Histories of the git terminal               |git log
---------------------------------------------------------------------------------


* GIT WORKING SYSTEM
-----------------------------
S/N|     Git System           |             Purpose                 |Command
=================================================================================
1. |Add Certain type of files |To add files with the same extension |git add *.<extension e.g html> i.e git add *.html
---------------------------------------------------------------------------------
2. |Add multiple files(only)  |To add more than one file at once    |git Add .-------------------------------------------------------------------------------
3. |Add all files & folders   |To add files & folders at once       |git add -A
---------------------------------------------------------------------------------
4. |Remove files from stage   |To remove files from staging area    |git rm --cached <file_name_to_remove> or git reset HEAD -- <file_name_to_remove>
--------------------------------------------------------------------------------
5. |Ignore file in working dir|To prevent file(s) from being stage  |create a    .gitignore file, then open it and type the file (with d extension) to ignore
--------------------------------------------------------------------------------


* GIT BRANCH
-----------------------------
S/N|     Git Branch           |             Purpose                 |Command
=================================================================================
1. |Check current branch |To list current branch(s) in the git dir. |git branch
---------------------------------------------------------------------------------
2. |Add another branch   |To add more branch to the git directory   |git checkout -b <branch_name> -------------------------------------------------------------------------------
3. |Change/Switch branch |To switch from one branch to another      |git checkout <branch_name>
---------------------------------------------------------------------------------
4. |Merge branches       |To merge one branch with another          |git merge <branch_name>
--------------------------------------------------------------------------------
5. |Remove branch        |To remove a branch from the git directoy  |git branch -d <branch_name>
--------------------------------------------------------------------------------
6. |Change branch name   |To edit a brnch name to new name of choice|git branch -m <current_branch_name> <branch_name_to_change_to>
--------------------------------------------------------------------------------

