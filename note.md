What is git?
- SCM -> Source control management

Install git
- Done.

git config --global user.name "me.maeself"
git config --global user.email me.maeself@gmail.com
git config --global init.default main

git config -help
git help config

cd ......
git init
git status

git add <filename>

git add -A
git add --all
git add .

- [] TODO: Look at how to .gitignore

commit:
- Commit is taking a snapshot of your current file

git commit - m "<message>"

git diff

git add <filename>

- working files
- staging
- commit

git restore --staged <filename>

git commit -a -m "<message>"

git log
git log --oneline
git commit -m "<msg>" -- amend     -> To chage the previous commit

git log -p

git reset <git tag>   -> Get those in `git log --oneline`

git rebase -i --root    -> To change the whole history of the commit

# branch