
# 1. Local Repository
    1. Set up git-scm : https://git-scm.com/download/

    2. Config github: synchronize with github account
      + git config -global user.name = "" 
      + git config -global user.email = ""

    3. Create local repository
      + Create folder to store repository
      + Git Bash here (inside folder created) => Git init

    4. Get status
      + git status
      + git diff : show the different

    5. Update
      + git add filename (.) : add new filde
      + git rm . : rm file


    6. Commit to local respository 
      + git commit -m"some messages"

    *** 5+6 : git commit -a -m"some messages"
    7. Push to remote Repository
      + git remote add projectfile url(of repository in remotegithub): only the first time
      + git push (--set-upstream projectfile master)

    8. Back up 
      + git log : history of commit to local respository (with id)
      + git revert id : to back up
      + Esc => :d => enter: to escape

# 2. Remote Repository
    1. Clone github
      + git clone url
    2. Pull
      + git pull
