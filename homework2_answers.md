What command do you use to setup a git repository inside of your folder? 
 -git init
What command do you use to ask git to start tracking a file? -git add
What command do you use to ask git to move your file from the staging area to the repository? -git commit -m ''

What command do you use to pull any changes from the master repository into your local repository?
-git pull 
What command do you use to unstage a file?
 - git reset [file]
What command do you use to change your files back to how they were after a commit? $ git reset [commit]
Why is it important to use -- when changing files back to a previous state? $ git reset --hard [commit] // it is for a Discards all history and changes back to the specified commit
Why might you want to reset your files back to a previous commit? If the previous commit was in a more functional state

What command do you use to create a branch? $ git branch [branch-name]
What command do you use to use a different branch? $ git checkout [branch-name]
Why would you want to use a branch other than the default master?  The alternate branch allows for changes to take place without affecting the master branchs code.

Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged.
If you were managing a project and there are two versions of the same file that have changes that work. 
You should make a pull request if you are working on someone elses code and are requesting a merge. 

What command do you use to send all of the work that you've done locally to your remote repository? $ git push [remote] [branch]


