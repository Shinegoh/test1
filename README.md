# 
git branch
* main (this is the active branch)
# Making Changes on Local and push to GitHub
git checkout -b "feature-branch"
>>>"feature-branch" is added and now you are on "feature-branch"
git branch
* a-feature-branch
main
--- make some changes to the README file while on the "feature-branch" 
git status
>>> modified README.md file
git add . or git add README.md
git commit -m "add readme into main"
git diff main (the other branch)
>>> files difference is shown

### to push to github (or use git merge)
git checkout "feature-branch"
git status
>>> nothing to commit
git push / git push --set-upstream origin feature-branch / git push -u origin feature-branch
>>> it is pushed into github
# or use:
git merge feature-branch or main
