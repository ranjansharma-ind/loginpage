touch .gitignore
git config --global user.name Harry
git config --global user.email youremail@example.com
git init
git add .
git commit -m "Initial Commit"
git status # Just to see
ssh-keygen -t rsa -b 4096 -C "youremail@example.com"
tail <path to id_rsa.pub> # Add this key to your GitHub account
git remote add orign <https://github.com/Ranjansharma123/loginpage.git>
git push origin master
