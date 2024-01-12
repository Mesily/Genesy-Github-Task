# Genesy-Github-Task

**VERSION CONTROL**<br> 
Version Control is a system that manages changes to a file or project over time. It is used for tracking changes as well as who made the changes, the time it was made and also gives a little information regarding the change. 

Version control promotes collaboration by allowing different individuals work on a particular project concurrently, after which they merge their individual inputs to form a whole. It can also be said to be a form of backup, where past versions of a project are preserved and easily recovered on ocassions of loss.

**DIFFERENCE BETWEEN GIT AND GITHUB**<br>
**Git** is a distributed Version Control System that is used for tracking changes in a source code during software development. it is used locally on a developers device. With git, developers work independently on their local device and push their code to a central platform.<br>
**GitHub** on the other hand is a web-based hosting platform/service for git folders /repositories. It is the central platform to which developers push their source codes for the sake of collaboration, review, sharing and management. 

**THREE GITHUB ALTERNATIVES**<br>1. GitLab<br>
2. Gitea<br>
3. Bitbucket<br>

**DIFFERENCE BETWEEN GIT FETCH AND GIT PULL**<br>
**Git fetch** is a command used to retrieve/download the changes made in the remote repository to the current working repository or branch. Git fetch does not merge the changes retrieved with the content of the working branch/repository, it simply allows you view the changes. To merge the remote changes, one would have to run the "git merge" command.<br>
**Git pull** on the other hand is a command that fetches and merges the changes from the remote repository with the current working branch at the same time. 

**GIT REBASE AND ITS COMMAND**
Git rebase is used to integrate changes from one branch into another by combining commits from one branch unto another branch in chronological order. It is used to append changes from a feature or private branch to the main branch. Git rebase is basically used to maintain a cleaner and more linear project history by applying the local changes on top of the latest changes from the target branch in the order of commits occurence.<br>
Assuming one is on a feature branch, the command to rebase onto the main branch is ***git rebase main***

**GIT CHERRY-PICK**
Git cherry-pick is a command that allows one to apply specific changes or commits from one branch to another branch. For instance, where several changes are committed in say, a features branch; and one wants to select just some specific changes and merge them with the contents of the main branch, the command to use is git cherry-pick followed by the commit hash of the commit you want to apply. The command is ***git cherry-pick < command hash >***
