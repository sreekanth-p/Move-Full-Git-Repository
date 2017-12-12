# Move-Full-Git-Repository
---How to move a full Git repository---

Step 1: git clone --mirror <old-repo URI> temp-folder

Step 2: cd temp-folder

Step 3: git remote rm origin

Step 4: git remote add origin <new-repo URL>

Step 5: git push origin --all

Step 6: git push --tags
