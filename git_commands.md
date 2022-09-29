git clone https://github.com/sagarkulkarni1989/Devops_task1.git
git branch
mkdir Tasks1
cd Tasks1/
touch README.md
git branch dev
git branch sagar-new_feature
git branch
git checkout dev
touch testfile.md
git status
git add .
git commit -m "added test file"
git push origin dev
git checkout main
touch .gitignore
cat .gitignore
git add .
git commit -m "added gitignore file"
git push origin main
git checkout sagar-new_feature
echo "Devops certification" > README.md
cat README.md
git restore README.md
git checkout main
git merge dev
git branch delete sagar-new_feature
git push origin --delete sagar-new_feature
