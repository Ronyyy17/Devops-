# Devops-
Change the directory to your project using the command 'cd path/to/your/project', then initialize Git with 'git init'.
Create a text file using a text editor (e.g.,'notepad sample.txt'), add it to the staging area with 'git add sample.txt', commit the changes using git commit -m "Initial commit - added sample.txt", and view the commit history with git log.
Connect your local repository to a remote repository on GitHub by using the command 'git remote add origin <repository_url>'.
Push your changes to the remote repository's master branch with 'git push -u origin master'.
Create a new branch named 'feature' using 'git branch feature' and switch to it with 'git checkout feature'.
Make changes to the 'sample.txt' file, stage the changes with 'git add sample.txt', and commit them with 'git commit -m "Updated sample.txt in feature branch"'.
Push the changes to the remote 'feature' branch with 'git push origin feature'.
Switch back to the 'master' branch using 'git checkout master'.
Merge the changes from the 'feature' branch into the 'master' branch with the command 'git merge feature'.
Finally, push the merged changes to the remote 'master' branch using 'git push origin master'.
