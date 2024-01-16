# Creating respository from System
we can use 'git push -u origin main', the -u signifies that we will push all the code in the origin main only so -u is a shortcut 
<h2>WORKFLOW</h2>
GitHub -> Clone -> changes -> add -> commit -> push
<h2>Git Branches</h2>
git branch -M [branch name] : to rename branch
<br>
git checkout [branch name] : to navigate
<br>
git checkout -b [new branch name] : to cretae a new branch
<br>
git branch -d [branch name] : to delete branch 
<h2>MERGE</h2>
We can merge our feature(branch1) code with our main code through two ways:
<br>
1. git merge [branch name]
<br>
2. Create a PR(Pull Request). When ur a working on a project with many developers, and edit a feature then through PR u make a request to edit ur code into the main code, u send ur request to senior dev. of the main code. He checks ur code,reviews our PR, if it's wrong the developer can comment on ur PR to make changes.
<br>
3.'git pull origin main' : connects the code of branch1 and main 
<h2> Undoing Changes </h2>
Case 1: Staged changes: changes which have been added but not committed : git reset [file name] or git reset , when we have to reset multiple files
<br>
Case 2: Commited changes(for one commit): git reset HEAD~1, in git the latest git is stored with the name HEAD, so by HEAD~1 we mean that we want to go to the previous HEAD i.e., previous commit 
<br>
Case 3: Commited changes(for many commit): git reset [commit hash], to get commit hash, frist write 'git log' this gives hostory of all commits in this the hash is the numberical line writtern in yellow, this only reset's in git
git reset --hard [commit hash], this resets both in git and VSC 
<h2>FORK</h2>
A fork is a new repository that shares code and visbility settings with the original "upstream" respository. Fork is a rough copy.
Lets suppose we have to work on an open source project then first we will open that project. Then to fork there is a fork option at the right hand top corner. If it's a large project it takes time to copy i.e., fork 
