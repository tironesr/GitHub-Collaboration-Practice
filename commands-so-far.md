Last login: Thu Sep 15 10:23:31 on ttys000
(base) devonsandel@MacBook-Pro-2 project_1 % pwd
/Users/devonsandel/Dropbox/github/project_1
(base) devonsandel@MacBook-Pro-2 project_1 % cd github
cd: no such file or directory: github
(base) devonsandel@MacBook-Pro-2 project_1 % git clone 
https://github.com/devonsandel/Computational-Social-Science-Projects.git
Cloning into 'Computational-Social-Science-Projects'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
(base) devonsandel@MacBook-Pro-2 project_1 % pwd
/Users/devonsandel/Dropbox/github/project_1
(base) devonsandel@MacBook-Pro-2 project_1 % cd /Users/devonsandel/Dropbox/github
(base) devonsandel@MacBook-Pro-2 github % git clone 
https://github.com/devonsandel/Computational-Social-Science-Projects.git
Cloning into 'Computational-Social-Science-Projects'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
(base) devonsandel@MacBook-Pro-2 github % cd Computational-Social-Science-Projects
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % mkdir "Project 1"
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % touch commands-so-far
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % nano commands-so-far.md
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % nano commands-so-far.md
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git add *
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git commit -m "add to readme"
[main c592ee2] add to readme
 2 files changed, 33 insertions(+)
 create mode 100644 commands-so-far
 create mode 100644 commands-so-far.md
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 676 bytes | 676.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/devonsandel/Computational-Social-Science-Projects.git
   24be4c2..c592ee2  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git clone 
https://github.com/tironesr/GitHub-Collaboration-Practice.git
Cloning into 'GitHub-Collaboration-Practice'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git switch -c devon
Switched to a new branch 'devon'
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git branch
* devon
  main
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % nano names.md
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % git branch main
fatal: A branch named 'main' already exists.
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % nano names.md  
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % ls
GitHub-Collaboration-Practice	README.md			commands-so-far.md
Project 1			commands-so-far
(base) devonsandel@MacBook-Pro-2 Computational-Social-Science-Projects % cd GitHub-Collaboration-Practice 
(base) devonsandel@MacBook-Pro-2 GitHub-Collaboration-Practice % nano names.md
(base) devonsandel@MacBook-Pro-2 GitHub-Collaboration-Practice % nano names.md
(base) devonsandel@MacBook-Pro-2 GitHub-Collaboration-Practice % touch commands-so-far.md
