# portfolio-project
master=production
single feature branch
don't use 'git push' any more; use git push origin <branch-name> (git push origin master OR git push origin my-cool-new-feature)

new project checklist
create project folder in kabob case
create git-repo with same name as folder
enter project folder
copy and execute github instructions with username and pwd

feature branch
git checkout -b <feature-name>
confirm with git branch
make some changes..
commit changes... then push changes on feature branch to remote
git push origin <feature-name>
complete the feature
switch to master branch
git checkout master
git merge <feature-name>
... now we have a feature branch that is done... let's get clean up..
first push master to github to save our changes
git push origin master
now delete the feature branch local
git branch -d <feature-name>
delete the feature branch remote
git push origin --delete <branch_name>

