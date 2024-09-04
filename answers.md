Answer 1: 
git version 2.34.1
Answer 2: 
user.name=draden-mccullough
user.email=dm310223@ohio.edu
Answer 3:
 GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.
Answer 4:
 On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)
Answer 5:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md
Answer 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md
Answer 7:
[master (root-commit) e3c511b] Initial commit
 2 files changed, 45 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
Answer 8:
commit e3c511b30637c0a5dc0b5439930f01de1f30a664 (HEAD -> master)
Author: draden-mccullough <dm310223@ohio.edu>
Date:   Wed Sep 4 17:04:20 2024 -0400

    Initial commit
Answer 9:
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1010 bytes | 1010.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/draden-mccullough/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
Answer 10:
No
Answer 11:
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/draden-mccullough/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer 12:
Yes
Answer 13:
.  ..  .git  .gitignore  README.md

