program: Answers.md

Name:   Avery Hauser
Date:   9/7/2023
Email:   ah236122@ohio.edu

Description:   Is the Answers for lab 2

Answer 1:
git version 2.39.2 (Apple Git-143)

Answer 2:
credential.helper=osxkeychain
init.defaultbranch=main
user.name=Avery_Hauser
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true

Answer 3:
averyhauser@Averys-MacBook-Air-8 git-lab % git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
averyhauser@Averys-MacBook-Air-8 git-lab % 

Answer 4:
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Answer 5:
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	answers.md

Answer 6:
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   answers.md

Answer 7:
On branch main
nothing to commit, working tree clean

Answer 8:
commit 9660a6803e8a8e13c46c3ecfa99640cd6c2fbba1 (HEAD -> main)
Author: Avery_Hauser <averyhauser@Averys-MacBook-Air-8.local>
Date:   Thu Sep 7 15:58:01 2023 -0400

Answer 9:
Both files have been moved into the git-lab repository

Answer 10:
Yes it was changed 

Answer 11:
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/AveryHauser/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12:
averyhauser@Averys-MacBook-Air-8 git-lab % git pull
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 12 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (12/12), 4.19 KiB | 390.00 KiB/s, done.
From https://github.com/AveryHauser/git-lab
   9660a68..e47631e  main       -> origin/main
Updating 9660a68..e47631e
Fast-forward
 README.md  |   4 ++++
 answers.md | 114 +++++++++++++++++++++++++++++++++++++++++++++++++++

 Answer 13:
 .		..		git-lab-2
