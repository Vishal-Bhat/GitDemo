# GitDemo
Git commands and their usage

The basic Git commands


1) $git init 

git init initializes an empty repository (or) creates a new repository.
By default, the Git configuration can be added to the .git subdirectory path.

$git init <directory_name>

git clone versus git init : At a high level, both the git clone and git init can be used to initialize a new repository. 

working of git clone -> 1) git clone initially calls the git init to initialize a new repository -> then will copy the data from existing repository and checks out a new set of working files. For more details on git clone : https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone

2) $git diff

git diff is used to note the differences between the previous commit and the new modifications that are made to the existing file(s)

$git diff <commit_hash1> <commit_hash2> - compares the commit hashes of the respective commits that were being made.

3) $git log

git log is used to note down the various info and timestamps about the commits that are being made into the repository.

4) $git diff HEAD~1 HEAD
5) $git diff @~

Instead of using the commit hashes, we can use the HEAD and TAIL pointers respectively.

5) $git add <filename(s)>(optional) (.)

Adds the changes into the staging area.

6) $git commit -m "message string"

7) $git push -u origin master
8) $git status
9) $git checkout <filename(s)> - reverts back to the previous state - this is a file command. Reverts back the changes made to a file.
10) $git revert HEAD
11) $git reset
12) $git reset <reset_hash> / $git reset HEAD~1 
13) $
