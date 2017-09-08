#
git config --global user.name "<User name>" // To set user name of git
git config --global user.email "<Email>" // What do you think?

git init // Initiate empty git repo
git status // Will show me the status of any pending changes
git add --all // Will add all changes in the currect directory to the repo
git commit -am '<Comment>' // Will add pending changes with comment
git log <file.ext> -p // Will get repo log of file with content (-p)
git checkout <file-id filename.ext> // Will checkout file for use
git checkout <branch-name> // Switch to branch
git checkout -b <branch-name> // Create and switch to new branch
git branch // View all branches
git branch -D <branch-name> // Delete branch
git merge <branch-name> // Merge selected branch in to active branch

git remote add origin git@github.com:<User-name>/<Repo-name>.git // Add new repo address to git repository
git push origin <branch-name> // Push git to online repo
#
