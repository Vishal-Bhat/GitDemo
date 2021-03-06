# GitDemo
Git commands and their usage

The basic Git commands


1) $git init 

git init initializes an empty repository (or) creates a new repository.
By default, the Git configuration can be added to the .git subdirectory path.

$git init <directory_name>

git clone versus git init : At a high level, both the git clone and git init can be used to initialize a new repository. 

working of git clone -> 1) git clone initially calls the git init to initialize a new repository -> then will copy the data from existing repository and checks out a new set of working files. For more details on git clone : https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone

