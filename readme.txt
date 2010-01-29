
Global setup:

  Download and install Git
  git config --global user.name "Dmitriy Kovalenko"
  git config --global user.email runningmaster.gmail.com
  Add your public key
        

Next steps:

  mkdir sandbox
  cd sandbox
  git init
  touch README
  git add README
  git commit -m 'first commit'
  git remote add origin git@github.com:runningmaster/sandbox.git
  git push origin master
      

Existing Git Repo?

  cd existing_git_repo
  git remote add origin git@github.com:runningmaster/sandbox.git
  git push origin master
   


