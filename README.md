# this is my localhost

 # How to create a project  and push the same to new repo
 <br>
 Step 1: Set up Git on your local machine:
--> git config --global user.name "Your Name"
--> git config --global user.email "youremail@example.com"

Step 2: Create a new project:
--> mkdir my_project
--> cd my_project

Step 3: Initialize a Git repository:
--> git init

Step 4: Add and commit your project files:
--> git add .
--> git commit -m "Initial commit"

Step 5: Create a new repository on the Git hosting service:

Step 6: Link your local repository to the remote repository:
--> git remote add origin <repository_url>
--> git branch -M main  


Step 7: Push your project to the remote repository:
--> git push -u origin main 

# Create new file in project and push individual files to git hub 

Step 1: file that we want to push
--> git add filename

Step 2: commit the file
--> git commit -m "Initial commit" 

Step 3: push the individual files
--> git push -u origin main

# Revert the repo to the old commit to rollback changes

Case 1: staged changes
--> git reset filename
--> git reset 

Case 2: commited changes(for one commit)
--> git reset HEAD~1

Case 3: commited changes(for many commits)
--> git reset commit hash
--> git reset --hard commit hash


