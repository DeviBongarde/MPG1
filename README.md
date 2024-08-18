# MPG1
Megaproject Group 1;
Members: Devika, Vinayak, Avadhoot, Shivraj; 
Title: OpenEyeAlert Safety Band
----------------------------------------------------
## Before making any changes into the files in file explorer make sure you're in your own branch and not in main.
Check in gitbash
#### To change branch:

      git checkout branch-name

  example: git checkout devika 
#### Check Status:
  
      git status
   
make sure it is upto date
if not then
#### To get all from main and update your branch
   
      git checkout main
      git pull origin main
      git merge your branch-name
      git push origin main
  
now that your branch is updated make sure to again checkout to your branch using
   
      git checkout your-branch-name
     
now you can make whatever changes in your files
after the changes are done to commit:
#### To commit changes:
    
      git add .
      git commit -m "your message"
      git pull origin your-branch-name
      git push origin your-branch-name
   
now that you have commited the changes to merge them into the main branch open a PR(Pull Request)
#### Opening a PR
  open github
  in your branch you'll see a green button saying contribute
  create pull request
  ask another group member to approve and merge the pull request.
There you go!! Your block of work is now added to the main.
Whenever a new PR is approved make sure the othr group members update thier branch by using the update your branch commands above.
