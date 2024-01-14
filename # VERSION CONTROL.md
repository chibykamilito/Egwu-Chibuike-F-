# VERSION CONTROL
######  Version control systems are software tools that help software teams manage changes to source code

## DIFFERENCES BETWEEN GIT AND GITHUB
- Git is a version control system that allows developers to track changes in their code.
- GitHub is a web-based hosting service for git repositories.
- In simple terms, you can use git without Github
- You cannot use GitHub without git
- Git is installed locall
- GitHub is cloud based

## LIST THREE GITHUB ALTERNATIVE
- Gitlab
- JIRA Software.
- Azure Boards
- Asana

## DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
- Git Fetch command fetches all the changes from the remote repository to the local repository
- Git Pull on the other hand brings the copy of the remote directory changes into the working directory.
- Git fetch Repository data is updated in the .git directory
- Git pull The working directory is updated directly
- Git fetch Review of commits and changes can be done
- Git pull Updates the changes to the local repository immediately
- Git fetch there's no possibility of merge conflict
- Git pull there's possibility of merge conflict

## GIT REBASE MEANING 
###### Git Rebasing is the process of moving a commit to a new base commit
##### The syntax of git rebase is:
git rebase <branch>
<branch> represents the branch that you want to rebase onto your current branch.

# GIT CHERRY PICK
###### The git cherry command is used to identify commits that have not yet been merged or applied to another branch.

## COMMAND
The basic syntax of git cherry is:
git cherry <target-branch>