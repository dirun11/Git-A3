# Git-A3


Task: 

Create a Git working dir, with branches Develop, f1,f2
In the master branch, commit main.txt file
Put develop.txt in develop branch, f1.txt and f2.txt in f1 and f2 respectively
Push all these branches to GitHub
On local delete f2 branch, On local delete f2 branch


   64  touch main.tx
   65  ls
   66  rm main.tx
   67  ls
   68  touch main.txt
   69  ls
   70  git init
   71  git add main.txt
   72  git commit -m "commiting main.txt"
   73  git branch
   74  git branch develop
   75  git branch f1
   76  git branch f2
   77  git branch
   78  git checkout develop
   79  touch develop.txt
   80  git commit -m "commiting develop.txt"
   81  git checkout f1
   82  touch f1.txt
   83  git commit -m "commiting f1.txt"
   84  git checkout f2
   85  touch f2.txt
   86  git add f2.txt 
   87  git commit -m "commiting f2.txt"
   88  ls
   89  git branch
   90  git remote add origin https://github.com/dirun11/Git-A3.git
   91  git push origin master
   92  git push origin --all
   93  git branch
   94  git branch -D f2
   95  git checkout master
   96  git branch -D f2
   97  git branch
   98  git push origin --delete f2
   99  history
