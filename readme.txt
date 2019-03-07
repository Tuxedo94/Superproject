Clone repository as submodule: git submodule add

Clone repository with submodules:
  git submodule init
  git submodule update
  
Update submodules within superprojects:
  change to submodule directory
  git checkout master
  git pull
  change to superproject directory
  git add .
  git commit -m "commit message"