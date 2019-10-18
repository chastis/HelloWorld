# Hello World!

// create rep

git clone https://github.com/user/title-repository
cd title-repository/ 

// create subrep

git submodule add https://github.com/user/module-repository Module

// main operations

git add . 
git commit -m "update" 
git push -f


// deleting rep

git reset --hard a3775a5485af0af20375cedf46112db5f813322a 
git push --force
