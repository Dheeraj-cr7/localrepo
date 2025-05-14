# Here we learned about
<br>
some basic terminal commands like: 
<br>
cd .. to bounce back to the parent folder, 
<br>
mkdir directory_name to create new directory
<br>
<br><br>
some additional git commands: 
<br>
git init - to initialize, 
<br>
git remote add origin <link> - to target the repository in which we want to add files from local to remote, 
<br>
git remote -v - to check remote version/status, 
<br>
git branch - to check for branch, 
<br>
git branch -M main - to rename branch, 
<br>
git push origin main OR git push -u origin main - to tell the system that we will make changes to this file for a period of time so the -u creates an upstream link.

<br><br><br><br><br><br>
# Add new feature
<br>
to create new feature: use: git checkout -b featureName
<br>
to jump onto a feature: use: git checkout featureName
<br>
to delete a feature:
<br>
step 1:  jump onto a different feature
<br>
step 2: then write this command: git branch -d featureName.
<br>
add the feature => commit and then
<br>
push that feature using command: git push origin featureName.
<br>