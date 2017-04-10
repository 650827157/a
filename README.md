git clone git@github.com:650827157/a.git
.ssh/config
host github , user git ,hostname github.com ,port 22 ,identityfile ~/gh6

git clone gh6:650827157/a.git
git add . -f
git commit --amend --author='Your Name'
git push

