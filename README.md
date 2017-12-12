# Move-Full-Git-Repository
How to move a full Git repository

git clone --mirror <old-repo URI> temp-folder
cd temp-folder
git remote rm origin
git remote add origin <new-repo URL>
git push origin --all
git push --tags
