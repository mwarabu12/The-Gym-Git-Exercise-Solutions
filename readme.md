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

### Exercise 2
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "Added readme file"
[dev 9491e26] Added readme file
 1 file changed, 85 insertions(+)
 create mode 100644 readme.md
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.
]
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push --set-upstream origin dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.16 KiB | 1.16 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions/pull/new/dev
remote: 
To https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
 *  History restored 

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
 *  History restored 

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git --version
git version 2.48.1
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ apt-get install git
E: Could not open lock file /var/lib/dpkg/lock-frontend - open (13: Permission denied)
E: Unable to acquire the dpkg frontend lock (/var/lib/dpkg/lock-frontend), are you root?
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ Y
Y: command not found
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ apt-get install git
E: Could not open lock file /var/lib/dpkg/lock-frontend - open (13: Permission denied)
E: Unable to acquire the dpkg frontend lock (/var/lib/dpkg/lock-frontend), are you root?
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash save "Added home.html, connected it with style.css, and a
pplied some styles."
Saved working directory and index state On dev: Added home.html, connected it with style.css, and applied some styles.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add home.html 
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash save "Added home.html, connected it with style.css, and applied some styles."
Saved working directory and index state On dev: Added home.html, connected it with style.css, and applied some styles.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash list
stash@{0}: On dev: Added home.html, connected it with style.css, and applied some styles.
stash@{1}: On dev: Added home.html, connected it with style.css, and applied some styles.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash show
 home.html | 16 ++++++++++++++++
 1 file changed, 16 insertions(+)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash show -p
diff --git a/home.html b/home.html
new file mode 100644
index 0000000..86851e6
--- /dev/null
+++ b/home.html
@@ -0,0 +1,16 @@
+<!DOCTYPE html>
+<html lang="en">
+<head>
+    <meta charset="UTF-8">
+    <meta name="viewport" content="width=device-width, initial-scale=1.0">
+    <title>Home Page</title>
+    <link rel="stylesheet" href="style.css">
+    <link rel="stylesheet" href="style.css">
+    <link rel="stylesheet" href="style.css">
diff --git a/home.html b/home.html
new file mode 100644
index 0000000..86851e6
--- /dev/null
diff --git a/home.html b/home.html
new file mode 100644
index 0000000..86851e6
--- /dev/null
diff --git a/home.html b/home.html
new file mode 100644
diff --git a/home.html b/home.html
new file mode 100644
index 0000000..86851e6
--- /dev/null
+++ b/home.html
@@ -0,0 +1,16 @@
+<!DOCTYPE html>
+<html lang="en">
+<head>
+    <meta charset="UTF-8">
+    <meta name="viewport" content="width=device-width, initial-scale=1.0">
:
 *  History restored 

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash save "Added about page but haven't applied any css styles"
Saved working directory and index state On dev: Added about page but haven't applied any css styles
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash save "Added Our Team page"
Saved working directory and index state On dev: Added Our Team page
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash list
stash@{0}: On dev: Added Our Team page
stash@{1}: On dev: Added about page but haven't applied any css styles
stash@{2}: On dev: Added home.html, connected it with style.css, and applied some styles.
stash@{3}: On dev: Added home.html, connected it with style.css, and applied some styles.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop @{1}
fatal: '@{1}' is not a stash-like commit
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Dropped stash@{1} (a2ab9a8b7fe10abb740f3d95beaf414de72422d7)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop {2}
error: {2} is not a valid reference
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop{2}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'pop{2}'
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Soluti
                                                                        ^C
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash@{2}
git: 'stash@{2}' is not a git command. See 'git --help'.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop stash@{2}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

Dropped stash@{2} (8c887e1b0bd5ab6e42810461c45d6d56b100fafb)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop stash@{3}
fatal: log for 'stash' only has 2 entries
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash list
stash@{0}: On dev: Added Our Team page
stash@{1}: On dev: Added home.html, connected it with style.css, and applied some styles.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   african-employee-talking-female-colleague-sitting-together-workplace-workmates-discuss-new-project-focus-black-worker-147366346.webp
        new file:   portrait-happy-african-american-female-company-leader-ceo-boss-executive-standing-front-company-building-copy-spac-167982879.webp
        new file:   portrait-male-african-american-professional-possibly-business-executive-corporate-ceo-finance-attorney-lawyer-sales-stylish-155546880.webp
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

Dropped stash@{0} (df6cb8edb7f06105a64a35fdd1570744e02a43ce)
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "Used git stash pop to bring back about and team pages to be commited and pushed"
[dev 47dcaaf] Used git stash pop to bring back about and team pages to be commited and pushed
 5 files changed, 134 insertions(+)
 create mode 100644 about.html
 create mode 100644 african-employee-talking-female-colleague-sitting-together-workplace-workmates-discuss-new-project-focus-black-worker-147366346.webp
 create mode 100644 portrait-happy-african-american-female-company-leader-ceo-boss-executive-standing-front-company-building-copy-spac-167982879.webp
 create mode 100644 portrait-male-african-american-professional-possibly-business-executive-corporate-ceo-finance-attorney-lawyer-sales-stylish-155546880.webp
 create mode 100644 team.html
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 48.59 KiB | 2.56 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions.git
   9491e26..47dcaaf  dev -> dev
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git restore --staged about.html
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git restore index.htm
error: pathspec 'index.htm' did not match any file(s) known to git
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git restore index.html
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 

## Bundle 2
### Exercise 1
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch ft/team-page
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
* dev
  ft/team-page
  main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch -d ft/team-page
Deleted branch ft/team-page (was 4a4d9e0).
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
* dev
  main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch ft/bundle-2
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
* dev
  ft/bundle-2
  main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch <!DOCTYPE html>
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch ft/bundle 2
fatal: only one reference expected
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch ft/bundle-2
fatal: a branch named 'ft/bundle-2' already exists
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git branch
* dev
  ft/bundle-2
  main
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch ft/bundle-2
M       readme.md
Switched to branch 'ft/bundle-2'
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "Added services.html file with some changes"
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

no changes added to commit (use "git add" and/or "git commit -a")
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git add .
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git commit -m "Added services.html file with some changes"
[ft/bundle-2 c622e2f] Added services.html file with some changes
 2 files changed, 56 insertions(+), 1 deletion(-)
 create mode 100644 services.html
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git switch ft/bundle-2 
Switched to branch 'ft/bundle-2'
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.10 KiB | 562.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote: 
To https://github.com/mwarabu12/The-Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
eric-mwarabu@eric-mwarabu:~/Desktop/The Gym/Gym Git Exercise Solutions$ 
```