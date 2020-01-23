STEP 2:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git log
fatal: your current branch 'master' does not have any commits yet


STEP 4:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        new_file.txt

nothing added to commit but untracked files present (use "git add" to track)


STEP 6:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   new_file.txt


STEP 8:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master
nothing to commit, working tree clean


STEP 10:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   new_file.txt

no changes added to commit (use "git add" and/or "git commit -a")


STEP 12:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   new_file.txt


STEP 15:
  STATUS:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   new_file.txt

no changes added to commit (use "git add" and/or "git commit -a")

LOG:
UDIT@DESKTOP-9KH8C6J MINGW64 /c/Users/Udit/downloads/In4matx 191A/git-katas/basic-commits/exercise (master)
$ git log
commit 8c8fefce4188fb4c67435c40ffb6981fcded44ce (HEAD -> master)
Author: Udit Kaushik <ukaushik@uci.edu>
Date:   Wed Jan 22 17:52:39 2020 -0800

    Second update to file

commit ad31dda04a4860e04dacb736752146c6ebc2b604
Author: Udit Kaushik <ukaushik@uci.edu>
Date:   Wed Jan 22 17:50:45 2020 -0800

    Created new file
