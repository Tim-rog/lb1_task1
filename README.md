git commit -am "Initional commit"
git tag v1.0
git commit -am "new knot"

git tag v1.1
git branch feat-auth
git checkout feat-auth
git commit -am "New branch"

git tag merge-1
git commit -am
git checkout master
git commit -am "back"

git tag hotfix
git merge --no-ff feat-auth 

git tag merge-merged
git commit -am "Back"
git tag v1.2