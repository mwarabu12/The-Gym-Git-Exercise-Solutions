# The Gym Exercise
## Bundle 1
### Exercise 1
```bash
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ ls
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch -m master main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commin -m "simple html and css files"
git: 'commin' is not a git command. See 'git --help'.

The most similar command is
        commit
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "simple html and css files"
[main (root-commit) 982cae1] simple html and css files
 2 files changed, 30 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "first commit"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "first commit"
[main 006db91] first commit
 1 file changed, 3 insertions(+)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git remote add origin https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions.git
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 993 bytes | 496.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch dev
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
  dev
* main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch test
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
  dev
* main
  test
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch dev
Switched to branch 'dev'
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch -d test
Deleted branch test (was 006db91).
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
* dev
  main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
```