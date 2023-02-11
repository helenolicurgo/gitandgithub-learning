# Git and GitHub: The full CURSE!

Let's get in to the Git and GitHub to brush of my skills in collaboration!

- :cactus: You need to understand Git as a tree with trunk and branchs.
- :evergreen_tree: The trunk is the main path of the application under development
- :palm_tree: The branches are the paths of development that each team and/or developer is following and making changes
- :deciduous_tree: After some time in development (after verification and testing) we can merge the branchs back together in the trunk.
- :cactus: And come back to "branching" again as development cicle request until the next merge...
- 

:construction_worker: ToDo List: :running:

- ⭐ git init
- ⭐ Configure the git config file
- ⭐ create and edit (if needed) the .gitignore file
- ⭐ If you just need to do a quick fix on your code, hit the "period key" in your keybord to open the file in the GitHub.dev Codespace, which is a simple version of the VS Code on your browser.
- ⭐ Attention: with the GitHub.dev Codespace, you will not be abble to use terminal. And please, stay at the free level of use...

:star2: Git Commands :star2:

- ⭐ git init

- ⭐ git config --list

- ⭐ git config --global init.defaultBranch "trunk"

- ⭐ git config --global user.name "Your Name"

- ⭐ git config --global user.email "you@email.com"

- ⭐ git remote (See all the remote repositories that you have connected)

- ⭐ git remote -v (Retrurn the URL of the remote repositories)

- ⭐ git remote add alias-4-remote-repository https://github.com/your-login/your-repo.git (To add a remote repository)

- ⭐ git remote show alias-4-remote-repository (Retrurn more information about a specific remote repositorie)

- ⭐ git status : current status of the project

- ⭐ git add . (add ALL files to the staging area)

- ⭐ git add <filename> (add ONE SPECIFIC file to the staging area)

- ⭐ git commit -a -m "Message for this Commit" (Commit all files)

- ⭐ git push alias-4-remote-repository name-of-the-branch -u (Push updated files to a specific branch of a named remote repository and with -u making this repository the upstream remote at the git config file - if it's the final source of thruth for your code)

- ⭐ git push (if you used -u at the last push, it's a direct aproach to PUSH your files in to the configured remote repository)

- ⭐ git log (will return log information use Ctrl+Z to exit log)

- ⭐ git fetch (FETCH the changes from the remote repository to your local repository)

- ⭐ git merge name-of-the-branch/branch-name (MERGE your branches in to the trunck back together)

- ⭐ git merge --abort (will abort the merge attempt and keep things as they was before the merge)

- ⭐ git pull (Will FETCH and MERGE files from your git remote repository in your local repository)

- ⭐ git clone remote_repository_address optional_directory_to_save_remote_repository (Will COPY all the remote repository in to your local machine)

- ⭐ git branch (to show all branches in the project folder)

- ⭐ git branch <new_branch_name> (to create a new branch from the trunk)

- ⭐ git branch -M <new_name> (to rename the "main" or "master" branch/trunk)

- ⭐ git branch -d <branch_name> (to safe delete the branch if it's have not been merged with the trunk)

- ⭐ git branch -D <branch_name> (to delete the branch no matter this situation)

- ⭐ git checkout <branch_name> (to move to the chosed branch)

- ⭐ git checkout -b <branch_name> (to create a new branch and move to that one)

- ⭐ git checkout - (will take you back to your previous branch)

- ⭐ git diff (will return the difference bettween two commits in conflict)

