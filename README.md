To add project

go to project directory
echo "# comment" >> README.md
git init
git add .
// adds all files
git commit -m "first commit"
git remote add origin gitRepositoryUrl
git push -u origin master

--------------------------------------

To remove folder

git rm -r folder_name
git commit -m "your commit"
git push origin master

---------------------------------------

To edit your configuration file:

git config --global --edit

After doing this, you may fix the identity used for this commit with:
git commit --amend --reset-author   
