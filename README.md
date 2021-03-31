![git](https://www.codematters.online/wp-content/uploads/2019/09/Git-Logo-2Color.png)





# **What is git and why do you need it?**

Git is one of the most popular version control systems and it helps software developing teams manage changes to their source code over time. In other words, version control keeps track of every change in your code and it allows you to go back in time when something goes wrong.

![git1](https://res.cloudinary.com/practicaldev/image/fetch/s--Dilp_rhi--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/yi9n7h1klm5m6e3odcsa.png)

Also, it is really helpful to prevent concurrent work from conflicting when multiple people are working in the same project. An individual may be working on the sidebar navigation while another one is simultaneously updating the header.

![git2](https://res.cloudinary.com/practicaldev/image/fetch/s--pfmhZlvH--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/8ito8dl7a62luwhp18xv.png)

Version control systems facilitate the work of multiple individuals by allowing them to use different branches as part of one “file tree” and merge their updated code to one source of truth when it's ready.

![git3](https://res.cloudinary.com/practicaldev/image/fetch/s--QuGbH66H--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/3n38o2kxyjai6ophizhw.png)

# **Git branch**

Lists all your project branches and highlights your current branch. If you just cloned a project, you are going to be in the master branch (your source of truth). It is not advised to work directly on the master branch because there is a big chance you would have a broken project while you are adding some progress. Instead, you want to create a different branch, work on your changes or new feature and when you are done and everything is working as expected, merge that branch into master.

# **Git checkout**

Selects the branch you want to work on.

If the branch already exists:
git checkout *[branch-name]*

If you want to create a new branch:
git checkout -b *[branch-name]*

# **Git pull**

Pulls recent changes from the remote repository to your local files. If one of your team members merged a new feature into master, you need to pull the recent code added to master to keep your local files up to date.

# **Git status**

Lists all the files that you have worked on and have not been saved in a commit yet.

# **Git add**
Stages file that you would like to commit.

If you want to stage all the files that you have worked on: git add .

If you want to stage only one particular file: git add *[file-name]*

# **Git commit**

Saves the group of changes you staged to your local repository. Add a comment with each commit that summarizes the change.
git commit -m “commit message”

# **Git stash**

Saves any changes you have made locally and it reverts the working directory to match the HEAD of your last commit.

See a list of all the changes you have stashed: git stash list

Bring back the last changes you stashed: git stash pop

Clear all your stashed entries: git stash clear

# **Git push**

Saves your local committed changes into the remote repository so everybody else has access to your work.
git push origin *[branch-name]*