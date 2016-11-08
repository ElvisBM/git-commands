# git-commands

git init
- Initialize a new git repository

git gui
- Open git's GUI interface

git branch -D <branchname>
- Delete branch

git push origin :<branchname>
- Warning this deletes the remote branch

git checkout -b <newbranchname>
- Create new branch and check it out

git push -u origin <branchname>
- Pushes the current branch to the remote server and links the local branch to the remote so next time you can do.
 **git pull** or **git push**
-Without specifying remote and branch names

git mergetool
- lista Merging

git merge --squash <private_feature_branch>
- Merge all comments from a branch into your current branch squashing the commits into one commit.

git cherry-pick <sh1>
- Apply the changes introduced by an commit into your current branch

git add .
- Add all 

git commit -am "commit message"
- git add and commit all

git reset --hard
- Reverts any tracked files back to the last commit

git clean -dxf
- Deletes any untracked files so will clear out obj/bin etc as well which is handy for finding bad references

git commit --amend -m "new commit message"
- Change the commit message of the last committed changeset

git rm --cached -rm
- git rm --cached -r .
- git reset --hard origin/develop

git checkout master
- Checkout

git status
- Shows what's changed

git log
- View the git history

git difftoll


git gc 







