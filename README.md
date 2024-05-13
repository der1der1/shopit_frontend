git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/der1der1/shopit_frontend.git
git push -u origin main

git branch [Name for branch]
git add -A  (For all)
git commit -m "[first] commit" 
git push -u origin [Name for branch]

git checkout [Branch name]  (切換到那個分之名稱底下)

合併
git checkout [主分支] (要先回到主分之)
git merge [Branch name]  (再把新創立的分支合併上去)