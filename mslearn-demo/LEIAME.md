# My GitHub Project

This is my GitHub project. I published it directly from Visual Studio Code.

# The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.
git init

# A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server. In contrast to a local repository, a remote typically does not provide a file tree of the project's current state.
git remote add origin https://github.com/miabrandao/PDS.git

# Discovery the remote version
git remote -v

# Add the file to be commited
git add <nome-do-arquivo>

# Make a commit
git commit -m 'Mensagem do commit'

# More info about the commit
git status
git log

# The git set-upstream allows you to set the default remote branch for your current local branch. By default, every pull command sets the master as your default remote branch.
git push --set-upstream origin master

# The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.
git pull

# Changing to main branch
git checkout main

# Merging the master branch in the main branch
git merge master