1. git version 2.17.1
2. user.name=Roksolana Vovshchuk
user.email=rv941820@ohio.edu
3. The Git Manual pops up. It includes the name, synopsis, description, options, and other. 
4. On branch master

No commits yet

Untracked files: 
	(use "git add <file>..." to include in what will be committed) 

		README.md
		answers.md

nothing added to commit but untracked files present (use "git add" to track)
5. On branch master

No commits yet

Changes to be committed: 
	(use "git rm ==cached <file>..." to unstage)

		new file:   README.md

Untracked files: 
	(use "git add <file>..." to include in what will be committed)

		answers.md
6. On branch master

No commits yet

Changes to be committed: 
	(use "git rm ==cached <file>..." to unstage)

		new file:     README.md
		new file:     answers.md
7. On branch master

No commits yet

Changes to be committed: 
	(use "git rm ==cached <file>..." to unstage)
8. On branch master

No commits yet

Changes to be committed: 
	(use "git rm ==cached <file>..." to unstage)
9. On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
rvovshch@odd23:~/git-lab$ ^C
rvovshch@odd23:~/git-lab$ git log
commit 596a3291f3d515352f6a7abb843fec5f52f7e43a (HEAD -> master)
Author: Roksolana Vovshchuk <rv941820@ohio.edu>
Date:   Fri Sep 3 15:39:03 2021 -0400

    Initial commit
rvovshch@odd23:~/git-lab$ ^C
rvovshch@odd23:~/git-lab$ git remote add origin https://github.com/roksolanavovs/git-lab.git
rvovshch@odd23:~/git-lab$ git branch -M main
rvovshch@odd23:~/git-lab$ git push -u origin main
Username for 'https://github.com': roksolanavovs
Password for 'https://roksolanavovs@github.com': 
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 631 bytes | 45.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/roksolanavovs/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
rvovshch@odd23:~/git-lab$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
10. The changes I made online were reflected in my locaL COPY. 
11. Username for 'https://github.com': roksolanavovs
Password for 'https://roksolanavovs@github.com': 
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/roksolanavovs/git-lab.git/'
12. remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/roksolanavovs/git-lab
   596a329..8e5e63c  main       -> origin/main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
13. .  ..  answers.md  .git  README.md
14. 
