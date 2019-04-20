# delivery-sop

##Contribution Git Work Flow
fork this repo to your repo
In your development environment: git clone -UrlToForkedRepo 
git remote add upstream -UrlToThisRepo

git checkout master
git pull --rebase upstream master
git checkout -b feature-branch

After edit
git commit -a -m'your comment'
git pull --rebase upstream master
git push origin feature-branch

On your github cloned repo, click submit pull request
If PR merged:
delete feature-branch on your forked
git checkout master
git pull --rebase upstream master
If PR not merged:
make more commits to your feature-branch
pit pull --rebase upstream master
git push origin feature-branch

