# biaobaio

$ git checkout -b dev
Switched to a new branch 'dev'

$ git branch
* dev
  master
  
  Creating a new branch is quick
  
$ git add readme.txt 
$ git commit -m "branch test"
[dev fec145a] branch test
 1 file changed, 1 insertion(+)
 
 $ git checkout master
Switched to branch 'master'

$ git merge dev
Updating d17efd8..fec145a
Fast-forward
 readme.txt |    1 +
 1 file changed, 1 insertion(+)
