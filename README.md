# A03

To use **Github** & **Git**:<br /><br />

**Git** is a service that **Github** utilizes.<br />
First, create a new **Repository**. A repository (or repo) is similar to a folder on your desktop.<br />
Next, you'll want to locally create the repo.<br />
Running "git clone <repository_url>" in a local folder with git installed will do the work for you.<br />
After making local changes, you'll want to **push** your changes to the **remote** server that houses our repo.<br />
Running "git add <file_or_folder_name>" will tell git to upload the changes for the targetted files.<br />
Running "git commit -m <message>" will commit the changes to a local buffer. Note that it has not yet been pushed.<br />
Running "git push origin" will push your changes to the remote server! And we're done!<br />
Next, **fetch**ing changes is a good way to continue, but "git fetch" doesn't pull the files, only checks for updates.<br />
"git pull origin" will **pull** down files from the remote server.<br />
Git **branch**es are like branches from a tree- they have a connecting point (in this case a commit), and trail off to have their own changes.<br />
Branches can be **merge**d back into the primary branch via github (called main or master).<br />
To make a new branch, run "git checkout -b <branch_name>".<br />
Pushing to the branch requires changing "git push origin" to "git push origin/<branch_name>".<br /><br />

And that's all!
