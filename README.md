# git-commands
git --version -> For check git installed or not.
check user:
git config user.name (who commite in git)
git init (for intialize git)
check remote origin -> git remote -v
git remote add origin https://github.com/hardikchudasama/news-app.git
git remote set-url origin new.git.url/here => change remote origin of git
git add . / git add -A / git add * (for add changes in staging area)
git status (for test status of files)
git commit -m "initial commit" 
git commit --amend -m "New commit message." [For change the message of the latest commit]
(for commit changes in branch where -m is message)
git push -f origin test_branch 
(first create branch and push in branch, where -f command get commited message )
- For change branch
git branch -> For check existing branch , o/p: main or test_branch
git checkout -b(for “new branch”) non-existing-branch -> (for create new branch with -b command)
git checkout test_branch -> for change branch 
git pull origin main -> get pull from test_branch to main branch 
git log --oneline -> For check all commites
for revert commit ->
git checkout 051605c -> (051605c from git log --oneline)
than git revert 051605c
git checkout -f = restore all files with old code
ls -lart(open in gitbash) -> show hidden files
git branch -> get all branch
git branch -D new_branch -> delete branch
git diff -> compare working directory to staging area.
git rm index.html -> remove files
git rm --cached index.html -> remove file from staging area.
git remote set-url origin SSHURL -> set-url change origin (for update old URL)
git difftool oldcommitid - latestcommitid -> compare old vs new commit with ultracompare tool
git reset HEAD -- . -> unstage files after add . 
git clean -f -> remove untracked files
== remove commit from remote server ==
git reset HEAD1 -> reset last commit
git push origin branchname -f 
for check remote origin(URL) => git remote show origin
==
List all your branches (show remote or local branches) -> git branch -a

To delete last commit from remote branch
git reset --hard HEAD~1
git push -f
