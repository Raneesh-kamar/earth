git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Raneesh-kamar/earth.git
git branch -M main
git push -u origin main

git add .
git commit -m "Add Firebase hosting config and move index.html to public"
git push

firebase deploy --only hosting