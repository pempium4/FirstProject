…or create a new repository on the command line
echo "# fghfhfg" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/pempium4/fghfhfg.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/pempium4/fghfhfg.git
git branch -M master
git push -u origin master
