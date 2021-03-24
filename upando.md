# create a new repository on the command line
git init
git add README.md
git status
git add *
git commit -m "script vps"
git branch -M main
git remote add origin https://github.com/Antonilson-b/SSHPLUS.git
git push -u origin main



# push an existing repository from the command line
git remote add origin https://github.com/Antonilson-b/SSHPLUS.git
git branch -M main
git push -u origin main


# If you have a local clone, you can update it by running:
git branch -m main master
git fetch origin
git branch -u origin/master master
1