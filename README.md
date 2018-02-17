# git_tutorial
Sushil For git tutorial


# HTTPS

- echo "# git_tutorial" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/sushildangi/git_tutorial.git
- git push -u origin master

# SSH

- echo "# git_tutorial" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin git@github.com:sushildangi/git_tutorial.git
- git push -u origin master




# Add Account in git

	- git config --global user.name "Sushil Dangi"
	- git config --global user.email "dangi.sushil5@gmail.com"

# List all Setting

	- git config --list
	- git config user.email

# Start new project

	- git init

# Add made changes
	
	- git add .

# Commit changes

	- git commit -m "commit message"

# commit history

	- git log

 ## list of commit to specific user

		- git log --author="name"

# track Changing commited or not 

	- git status

# Check Difference working copy and staging

	- git diff

# Check Difference Staging and commit

	- git diff --staged

# Remove files
	
	- git rm filename

# Renaming File

	- git mv old_file_name new_file_name

# Move file in folder and rename 

	- git mv old_file_name folder_name/new_file_name

# Shortcut for add and commiting 

	- git commit -am "Message"

# Set to repository copy

	- git checkout -- filename

# Remove files from Staging Area

	- git reset HEAD filename

# Getting Old Version from Repository

	- git checkout <version No> -- filename

## Create Branch

	- git branch branch_name

## See all Branches 
	- git branch

## Change Branch

	- git checkout branch_name




