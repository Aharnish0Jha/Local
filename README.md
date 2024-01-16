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