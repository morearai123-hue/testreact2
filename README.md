#get repo
git clone repo url


#git init
git init
git add .
git commit -m "test"
git branch -M main
git remote add origin url
git push -u origin main

#get code
git pull

#git push again
git add .
git commit -m "test"
git push


#merge branches
git branch #check brach
git checkout main #switch to main
git pull origin main #latest pull
git merge branch_name #merge to main
git push origin main #push merged code

