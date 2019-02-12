Git Quick Start Commands

git version
git config --global user.name "Abe Lincoln"
git config --global user.email "mrabe@git.training"
git config --global --list
git clone github-https-url  # paste in your GitHub HTTPS clone URL

git status
echo "Test Git Quick Start demo" >> start.txt
git add start.txt
git status
git commit -m "Adding start text file"
git status
git push origin master

git config --global core.editor "notepad++.exe -multiInst -nosession"

git config --global credential.helper 'store'

git rebase <merged branch>
git rebase --abort
 
