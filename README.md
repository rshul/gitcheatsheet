# gitcheatsheet

# make directory a git repository
$ git init


# To stage a specific file:
$ git add <file or directory name>


# Adding a commit with message
$ git commit -m "Commit message in quotes"

# Message when files have not been staged (git add)
$ git status

# Running git config globally
$ git config --global user.email "my@emailaddress.com"
$ git config --global user.name "Brian Kerr"

# Running git config on the current repository settings
$ git config user.email "my@emailaddress.com"
$ git config user.name "Brian Kerr"

# Create a new branch
$ git branch <branch_name>

# List all remote or local branches
$ git branch -a

# Delete a branch
$ git branch -d <branch_name>

# Checkout an existing branch
$ git checkout <branch_name>

# Checkout and create a new branch with that name
$ git checkout -b <new_branch>

# Merge changes into current branch
$ git merge <branch_name>

# Adding a remote repository with the name of beanstalk
$ git remote add origin git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git

# List named remote repositories
$ git remote -v
origin git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git (fetch)
origin git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git (push)

# create a local working copy of an existing remote repository
$ git clone git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git

#To get the latest version of a repository
$ git pull origin staging

# Push a specific branch to a remote with named remote
$ git push origin staging

# Show entire git log
$ git log

# Show git log with date pameters
$ git log --<after/before/since/until>=<date>

# Show git log based on commit author
$ git log --<author>="Author Name"
  
  # To remove a file from the working index (cached):
$ git rm --cached <file name>

# To delete a file (force):
$ git rm -f <file name>

# To remove an entire directory from the working index (cached):
$ git rm -r --cached <directory name>

# To delete an entire directory (force):
$ git rm -r -f <file name>
  
 # Store current work with untracked files
$ git stash -u

# Bring stashed work back to the working directory
$ git stash pop


 
