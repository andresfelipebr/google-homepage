google project
repository in git hub
copy ssh
git bash
MANUELL@MANUEL MINGW64 ~
$ git clone git@github.com:andresfelipebr/google-homepage.git
Cloning into 'google-homepage'...
Warning: Permanently added the RSA host key for IP address '140.82.114.4' to the list of known hosts.
warning: You appear to have cloned an empty repository.

MANUELL@MANUEL MINGW64 ~
$ cd google-homepage

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ git remote -v
origin  git@github.com:andresfelipebr/google-homepage.git (fetch)
origin  git@github.com:andresfelipebr/google-homepage.git (push)

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ touch README.md

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ git add README.md

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ git commit -m "add README.md"
[master (root-commit) 5564623] add README.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ git status
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ touch google.txt

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
$ git status
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        google.txt

nothing added to commit but untracked files present (use "git add" to track)

MANUELL@MANUEL MINGW64 ~/google-homepage (master)
