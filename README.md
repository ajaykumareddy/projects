# APP

### Git Commands

git init<br/>
git config --global user.name "Ajay Kumar Reddy" <br/>
git config --global user.email "[ajay@email.com](mailto:ajay@email.com)" <br/>
git status <br/>
git add filename (or) git add . <br/>
git rm --cached filename<br/>
git reset HEAD filename<br/>
git reset HEAD . <br/>
git commit->then press i for Insert Mode,type your message,press Esc to exit insert mode,press :wq and Enter <br/>
git commit -m "commit message comes here" <br/>
git reset --hard HEAD~1 (Note: All the changes of last commit gets removed.)<br/>

git branch branchname <br/>
git checkout branchname<br/>

git merge branchname(branch to be merged)<br/>

git remote git remote add origin  [https://github.com/ajaykumareddy/projects.git](https://github.com/ajaykumareddy/projects.git)  <br/>
git push -u origin master (or) git push --set-upstream origin master<br/>
git pull<br/>

git branch -d master -> delete branch locally
git branch -d -r origin/master -> delete branch remote

git clone clone/to/path foldername(if particular folder required)<br/>

touch .gitignore -> creates a .gitignore file and add *.extension<br/>

### DOCUMENTATION  
[https://devdocs.io/git/](https://devdocs.io/git/)<br/>