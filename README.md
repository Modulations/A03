# A03

To use **Github**:

**Git** is a service that **Github** utilizes.
First, create a new **Repository**. A repository (or repo) is similar to a folder on your desktop.
Next, you'll want to locally create the repo.
Running "git clone <repository_url>" in a local folder with git installed will do the work for you.
After making local changes, you'll want to **push** your changes to the **remote** server that houses our repo.
Running "git add <file_or_folder_name>" will tell git to upload the changes for the targetted files.
Running "git commit -m <message>" will commit the changes to a local buffer. Note that it has not yet been pushed.
Running "git push origin" will push your changes to the remote server! And we're done!
Next, **fetch**ing changes is a good way to continue, but "git fetch" doesn't pull the files, only checks for updates.
"git pull origin" will **pull** down files from the remote server.
Git **branch**es are like branches from a tree- they have a connecting point (in this case a commit), and trail off to have their own changes.
Branches can be **merge**d back into the primary branch via github (called main or master).
To make a new branch, run "git checkout -b <branch_name>".
Pushing to the branch requires changing "git push origin" to "git push origin/<branch_name>".

And that's all!
