testing both 1 of 10
testing both 2 of 10
testing both 3 of 10
testing both 4 of 10
testing both 5 of 10

the last test (a succes):

C:\Users\user\Desktop\bothtest>git init
Initialized empty Git repository in C:/Users/user/Desktop/bothtest/.git/

C:\Users\user\Desktop\bothtest>git add .   

C:\Users\user\Desktop\bothtest>git commit -m "test 1 of 5" 
[main (root-commit) 758e53d] test 1 of 5
 1 file changed, 1 insertion(+)
 create mode 100644 testboth.md

C:\Users\user\Desktop\bothtest>git remote add origin-ik git@github-ik:Islam-Khan001/test5.git  

C:\Users\user\Desktop\bothtest>git remote add origin-ff git@github-ff:FazeFlynn/test4.git  

C:\Users\user\Desktop\bothtest>git push origin-ik main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 235 bytes | 58.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ik:Islam-Khan001/test5.git
 * [new branch]      main -> main

C:\Users\user\Desktop\bothtest>git push origin-ff main 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ff:FazeFlynn/test4.git
 * [new branch]      main -> main

C:\Users\user\Desktop\bothtest>git add . 

C:\Users\user\Desktop\bothtest>git commit -m "test 2 of 5" 
[main fa01e2b] test 2 of 5
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\user\Desktop\bothtest>git push origin-ik main 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 270 bytes | 135.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ik:Islam-Khan001/test5.git
   758e53d..fa01e2b  main -> main

C:\Users\user\Desktop\bothtest>git push origin-ff main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 270 bytes | 270.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ff:FazeFlynn/test4.git
   758e53d..fa01e2b  main -> main

C:\Users\user\Desktop\bothtest>git add . 

C:\Users\user\Desktop\bothtest>git commit -m "test 3 of 5" 
[main 6491ca6] test 3 of 5
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\user\Desktop\bothtest>git push origin-ik main 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 274 bytes | 137.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ik:Islam-Khan001/test5.git
   fa01e2b..6491ca6  main -> main

C:\Users\user\Desktop\bothtest>git push origin-ff main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 274 bytes | 68.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ff:FazeFlynn/test4.git
   fa01e2b..6491ca6  main -> main

C:\Users\user\Desktop\bothtest>git add . 

C:\Users\user\Desktop\bothtest>git commit -m "test 4 of 5" 
[main dbd1be8] test 4 of 5
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\user\Desktop\bothtest>git push origin-ik main     
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 92.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ik:Islam-Khan001/test5.git
   6491ca6..dbd1be8  main -> main

C:\Users\user\Desktop\bothtest>git push origin-ff main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 277.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github-ff:FazeFlynn/test4.git
   6491ca6..dbd1be8  main -> main

C:\Users\user\Desktop\bothtest>git add .

C:\Users\user\Desktop\bothtest>git commit -m "test 5 of 5" 
[main f49be30] test 5 of 5
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\user\Desktop\bothtest>git push origin-ik main 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 96.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github-ik:Islam-Khan001/test5.git
   dbd1be8..f49be30  main -> main

C:\Users\user\Desktop\bothtest>git push origin-ff main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github-ff:FazeFlynn/test4.git
   dbd1be8..f49be30  main -> main