# Learn-git-and-github
Authon by - Rohit Mahajan
1. create repository using github and edit redime file and commit the fist
2. then install git and use it
3. apply the config command
4. git config --global user.name "rohit mahajan"
5. git config --globale usee.email "rohitmahajan123bca@gmail.com"
6. git congit --list     # it is show the confit information
cd ~  # it has to change directory into main directory
clone - cloning a repository on  our local machine
git clone <project link>

PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git add index.html
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git status        
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
        modified:   README.md

PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git add .
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git status
On branch main

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html

PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git commit -m "add index.html file"
[main f7ee0ac] add index.html file
 2 files changed, 1 insertion(+)
 create mode 100644 index.html
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git push origin main
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 357 bytes | 357.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Rohitmahajan004/Learn-git-and-github.git
   8c168d0..f7ee0ac  main -> main
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> git push origin main
Everything up-to-date
PS C:\Users\ROHIT\Desktop\git demo\Learn-git-and-github> 


