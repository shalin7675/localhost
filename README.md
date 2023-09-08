# this is my localhost

 # How to create a project  and push the same to new repo
 <br>
 Step 1: Set up Git on your local machine:
 <br>
--> git config --global user.name "Your Name"<br>
--> git config --global user.email "youremail@example.com"

Step 2: Create a new project:<br>
--> mkdir my_project<br>
--> cd my_project

Step 3: Initialize a Git repository:<br>
--> git init

Step 4: Add and commit your project files:<br>
--> git add .<br>
--> git commit -m "Initial commit"

Step 5: Create a new repository on the Git hosting service:

Step 6: Link your local repository to the remote repository:<br>
--> git remote add origin <repository_url><br>
--> git branch -M main  


Step 7: Push your project to the remote repository:<br>
--> git push -u origin main 

# Create new file in project and push individual files to git hub <br>

Step 1: file that we want to push<br>
--> git add filename

Step 2: commit the file<br>
--> git commit -m "Initial commit" 

Step 3: push the individual files<br>
--> git push -u origin main

# Revert the repo to the old commit to rollback changes

Case 1: staged changes<br>
--> git reset filename<br>
--> git reset 

Case 2: commited changes(for one commit)<br>
--> git reset HEAD~1

Case 3: commited changes(for many commits)<br>
--> git reset commit hash<br>
--> git reset --hard commit hash


