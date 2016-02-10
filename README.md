# Test repository

This is a test repository for students to learn how to use git and GitHub. 

Lucy Sun - this is a test

Last login: Thu Jan 28 12:01:49 on console
Lucys-MacBook-Pro:~ Isabella$ cd Desktop/
Lucys-MacBook-Pro:Desktop Isabella$ git clone https://github.com/luciesun101/test_repo.git
Cloning into 'test_repo'...
remote: Counting objects: 9, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 2), reused 9 (delta 2), pack-reused 0
Unpacking objects: 100% (9/9), done.
Checking connectivity... done.
Lucys-MacBook-Pro:Desktop Isabella$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/Isabella/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/Isabella/.ssh/id_rsa.
Your public key has been saved in /Users/Isabella/.ssh/id_rsa.pub.
The key fingerprint is:
a1:e3:c8:ff:ff:01:85:b2:dd:22:d9:a5:ae:82:83:c0 Isabella@Lucys-MacBook-Pro.local
The key's randomart image is:
+--[ RSA 2048]----+
|                 |
|           .     |
|        o . o    |
|       . B =     |
|.     o S * .    |
|.E . o . o o     |
| . .o..   . .    |
|  . o..  .   .   |
|     ..oo....    |
+-----------------+
Lucys-MacBook-Pro:Desktop Isabella$ cd 
.DS_Store
.localized
Bio503_CourseManual_2015_submittedVersion.pdf
CHW_Extraction Final.xlsx
DeskTop/
Lucy Sun_Course Schedule.xlsx
Pictures to Print/
R files Practice/
Screen Shot 2016-02-09 at 4.14.09 PM.png
Summer Internship Application.xlsx
Symphony Projects/
Lucys-MacBook-Pro:Desktop Isabella$ cd 
.DS_Store
.localized
Bio503_CourseManual_2015_submittedVersion.pdf
CHW_Extraction Final.xlsx
DeskTop/
Lucy Sun_Course Schedule.xlsx
Pictures to Print/
R files Practice/
Screen Shot 2016-02-09 at 4.14.09 PM.png
Summer Internship Application.xlsx
Symphony Projects/
Lucys-MacBook-Pro:Desktop Isabella$ cd Desktop/
Lucys-MacBook-Pro:Desktop Isabella$ pwd
/Users/Isabella/Desktop/Desktop
Lucys-MacBook-Pro:Desktop Isabella$ cd iCloud Drive
-bash: cd: iCloud: No such file or directory
Lucys-MacBook-Pro:Desktop Isabella$ cd Bio260 Data Science
-bash: cd: Bio260: No such file or directory
Lucys-MacBook-Pro:Desktop Isabella$ cd..
-bash: cd..: command not found
Lucys-MacBook-Pro:Desktop Isabella$ pwd
/Users/Isabella/Desktop/Desktop
Lucys-MacBook-Pro:Desktop Isabella$ cd..
-bash: cd..: command not found
Lucys-MacBook-Pro:Desktop Isabella$ cd ..
Lucys-MacBook-Pro:Desktop Isabella$ pwd
/Users/Isabella/Desktop
Lucys-MacBook-Pro:Desktop Isabella$ cd
Lucys-MacBook-Pro:~ Isabella$ ls
Applications		Library			ibt_application.log
Bio260 Data Science	Movies			ibtsa.log
Desktop			Music			oasys.log
Documents		Pictures		summary.txt
Downloads		Project1
Dropbox			Public
Lucys-MacBook-Pro:~ Isabella$ cd Bio260\ Data\ Science/https://github.com/luciesun101/test_repo.git
-bash: cd: Bio260 Data Science/https://github.com/luciesun101/test_repo.git: No such file or directory
Lucys-MacBook-Pro:~ Isabella$ Bio260\ Data\ Science/test_repo/
-bash: Bio260 Data Science/test_repo/: is a directory
Lucys-MacBook-Pro:~ Isabella$ pwd
/Users/Isabella
Lucys-MacBook-Pro:~ Isabella$ cd Bio260\ Data\ Science/test_repo/
Lucys-MacBook-Pro:test_repo Isabella$ gitlog
-bash: gitlog: command not found
Lucys-MacBook-Pro:test_repo Isabella$ git log
commit 751015868461dc29b1b313c17a97e4d2fa3da896
Author: Stephanie Hicks <statisticalscientist@gmail.com>
Date:   Tue Feb 9 11:39:57 2016 -0500

    added summary statistics of faithful data set

commit 9a93a6364e6be0d5aa4b2a75469556b9bb4c42fe
Author: Stephanie Hicks <statisticalscientist@gmail.com>
Date:   Mon Feb 8 17:07:08 2016 -0500

    initial commit
Lucys-MacBook-Pro:test_repo Isabella$ git--help
-bash: git--help: command not found
Lucys-MacBook-Pro:test_repo Isabella$ git --help
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Forward-port local commits to the updated upstream head
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
Lucys-MacBook-Pro:test_repo Isabella$ git clone --help
Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Lucys-MacBook-Pro:test_repo Isabella$ git remote -v
origin	https://github.com/luciesun101/test_repo.git (fetch)
origin	https://github.com/luciesun101/test_repo.git (push)
Lucys-MacBook-Pro:test_repo Isabella$ ls 
README.md		old_faithful.Rmd	old_faithful.html
Lucys-MacBook-Pro:test_repo Isabella$ ls -sa
total 1792
   0 .			   0 .git		   8 old_faithful.Rmd
   0 ..			   8 .gitignore		1752 old_faithful.html
  16 .DS_Store		   8 README.md
Lucys-MacBook-Pro:test_repo Isabella$ ls
README.md		old_faithful.Rmd	old_faithful.html
Lucys-MacBook-Pro:test_repo Isabella$ open README.md
Lucys-MacBook-Pro:test_repo Isabella$ open README.md
Lucys-MacBook-Pro:test_repo Isabella$ old_faithful.Rmd
-bash: old_faithful.Rmd: command not found
Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Lucys-MacBook-Pro:test_repo Isabella$ git add README.md
Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   README.md

Lucys-MacBook-Pro:test_repo Isabella$ git add README.md
Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Lucys-MacBook-Pro:test_repo Isabella$ git commit -m "First test, added name"
[master 1674bc8] First test, added name
 Committer: Lucy Sun <Isabella@Lucys-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 insertions(+), 1 deletion(-)
Lucys-MacBook-Pro:test_repo Isabella$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean
Lucys-MacBook-Pro:test_repo Isabella$ git log
commit 1674bc81b15f2f7f04f18321f233361b990e66b9
Author: Lucy Sun <Isabella@Lucys-MacBook-Pro.local>
Date:   Wed Feb 10 10:04:05 2016 -0500

    First test, added name

commit 751015868461dc29b1b313c17a97e4d2fa3da896
Author: Stephanie Hicks <statisticalscientist@gmail.com>
Date:   Tue Feb 9 11:39:57 2016 -0500

    added summary statistics of faithful data set

commit 9a93a6364e6be0d5aa4b2a75469556b9bb4c42fe
Author: Stephanie Hicks <statisticalscientist@gmail.com>
Date:   Mon Feb 8 17:07:08 2016 -0500

    initial commit
Lucys-MacBook-Pro:test_repo Isabella$ git push
Username for 'https://github.com': 
Password for 'https://github.com': 
remote: Anonymous access to luciesun101/test_repo.git denied.
fatal: Authentication failed for 'https://github.com/luciesun101/test_repo.git/'
Lucys-MacBook-Pro:test_repo Isabella$ git push
Username for 'https://github.com': luciesun101
Password for 'https://luciesun101@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/luciesun101/test_repo.git/'
Lucys-MacBook-Pro:test_repo Isabella$ git push
Username for 'https://github.com': luciesun101
Password for 'https://luciesun101@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/luciesun101/test_repo.git/'
Lucys-MacBook-Pro:test_repo Isabella$ git push
Username for 'https://github.com': luciesun101
Password for 'https://luciesun101@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/luciesun101/test_repo.git/'
Lucys-MacBook-Pro:test_repo Isabella$ git push
Username for 'https://github.com': luciesun101
Password for 'https://luciesun101@github.com': 
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
To https://github.com/luciesun101/test_repo.git
   7510158..1674bc8  master -> master
Lucys-MacBook-Pro:test_repo Isabella$ 
