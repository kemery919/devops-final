# Initialize the folder
git init

# Add / Commit
git add .
git commit -m "Some descriptive text of the changes here"

# Link to a repository on GitHub
git remote add origin "insert link here from github and remove the quotes"

# Change from VSCode master to GitHub main for the default branch
git branch -M main

# Push changes to repo
git push -u origin main