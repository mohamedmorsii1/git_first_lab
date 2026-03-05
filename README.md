# Git Lab 1
# commands i used 
```bash
mkdir lab1_git
cd lab1_git
git init 
echo "Mohamed Morsi" >> file.txt
git add file.txt
git commit -m "first commint: writing full name"
git branch -M main 
git remote add origin git@github.com:mohamedmorsii1/git_first_lab.git
# this part is for creating file and make the first commit and make the repo on github with us

echo "system admin" >> file.txt 
git add .
git commit -m "second commint"
echo "intake 46" >> file.txt 
git add .
git commit -m "third commint"
echo "2026" >> file.txt 
git add .
git commit -m "fourth commint"
#this part is for creating the rest four commits

git reset --hard HEAD^^
#deleting the last two commits

echo "new commit" >> file.txt 
git add .
git commit -m "commit after deletion"
echo "Lab done" >> file.txt 
git add .
git commit --amend -m "finish"
#make a commit after deletion then replace it with another one

git revert b59d683
#revert the last commit 
