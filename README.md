# github-team-checklist


One person on each team
Create a new repo on gitHub
clone it to your local computer
Create the base files for your application (if you are creating an express app, run the generator and follow that checklist before add/commit/pushing to gitHub)
Add each team member as a collaborator to the repo on GitHub
Each person on the team
clone the repo (do NOT fork it)
create your own branch git checkout -b YOURBRANCHNAME
When you are working on your own branch:
git add -A (or the appropriate command to commit the files you intend to commit)
git commit -m "commit message"
git pull origin master This step allows you to retrieve any new code that has been added to master by your teammates. To avoid large, difficult merge conflicts, do this step fairly frequently
Fix any merge conflicts
git push origin YOURBRANCHNAME
If the feature is done and tested and and all of the above steps have been followed:
Go to GitHub and submit a pull request from your branch to master
Wait for team members to approve the pull request and merge it into master
