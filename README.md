## create a new repository on the command line  

git init  
git add README.md  
git commit -m "first commit"  
git remote add origin git@github.com:haohaixingyun/learnhowtousegit.git  
git push -u origin master  


## after do something change   
git stauts    
some tips help your how to do this   
{  
$ git status  
On branch master  
  
Initial commit  

Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
  
        README.md  
  
nothing added to commit but untracked files present (use "git add" to track)  
}  
git add 'the file you changed'  
git commit -m "why you want do the commit?"  
git remote add origin git@github.com:haohaixingyun/learnhowtousegit.git  
git push origin master  