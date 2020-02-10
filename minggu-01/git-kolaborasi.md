C:\>git --version
git version 2.9.0.windows.1

C:\TCC>git
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
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

C:\TCC>cd C:\PraktikumTCC

C:\PraktikumTCC>dir
 Volume in drive C has no label.
 Volume Serial Number is 24D5-F0E0

 Directory of C:\PraktikumTCC

05/02/2020  14:24    <DIR>          .
05/02/2020  14:24    <DIR>          ..
               0 File(s)              0 bytes
               2 Dir(s)  677.659.414.528 bytes free

C:\PraktikumTCC>git clone https://github.com/mayamonika998/tekn-cloud-computing
Cloning into 'tekn-cloud-computing'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

C:\PraktikumTCC>dir
 Volume in drive C has no label.
 Volume Serial Number is 24D5-F0E0

 Directory of C:\PraktikumTCC

05/02/2020  14:26    <DIR>          .
05/02/2020  14:26    <DIR>          ..
05/02/2020  14:26    <DIR>          tekn-cloud-computing
               0 File(s)              0 bytes
               3 Dir(s)  677.659.234.304 bytes free

C:\PraktikumTCC>cd tekn-cloud-computing

C:\PraktikumTCC\tekn-cloud-computing>git add .

C:\PraktikumTCC\tekn-cloud-computing>git config --global user.name "mayamonika998"

C:\PraktikumTCC\tekn-cloud-computing>git config --global user.email "mayamoniika98@gmail.com"

C:\PraktikumTCC\tekn-cloud-computing>git commit -m "praktikum TCC minggu 01"
[master eb9e869] praktikum TCC minggu 01
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 minggu-01/gambar-01.PNG
 create mode 100644 minggu-01/gambar-02.PNG
 create mode 100644 minggu-01/gambar-03.PNG

C:\PraktikumTCC\tekn-cloud-computing>git push -u origin master

MELANJUTKAN DIRUMAH :
Microsoft Windows [Version 10.0.10240]
(c) 2015 Microsoft Corporation. All rights reserved.

C:\Users\mayam>cd..

C:\Users>cd..

C:\>git --version
git version 2.25.0.windows.1

C:\>cd tekn_cloud_computing

C:\tekn_cloud_computing>git
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\tekn_cloud_computing>git clone https://github.com/mayamonika998/tekn-cloud-computing
Cloning into 'tekn-cloud-computing'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 9 (delta 0), reused 6 (delta 0), pack-reused 0
Unpacking objects: 100% (9/9), 108.68 KiB | 161.00 KiB/s, done.

C:\tekn_cloud_computing>dir
 Volume in drive C has no label.
 Volume Serial Number is 7810-4CC9

 Directory of C:\tekn_cloud_computing

10/02/2020  22.09    <DIR>          .
10/02/2020  22.09    <DIR>          ..
10/02/2020  22.09    <DIR>          tekn-cloud-computing
               0 File(s)              0 bytes
               3 Dir(s)  85.031.948.288 bytes free

C:\tekn_cloud_computing>git config --global user.name "mayamonika998"

C:\tekn_cloud_computing>git config --global user.email "mayamoniika98@gmail.com"

C:\tekn_cloud_computing>git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager
user.name=mayamonika998
user.email=mayamoniika98@gmail.com

C:\tekn_cloud_computing>cd tekn-cloud-computing

C:\tekn_cloud_computing\tekn-cloud-computing>git add .

C:\tekn_cloud_computing\tekn-cloud-computing>git commit -m "praktikum TCC minggu 01"
[master 5a780d1] praktikum TCC minggu 01
 2 files changed, 35 insertions(+)
 create mode 100644 minggu-01/README.md
 create mode 100644 minggu-01/rangkuman-cloud-computing.md

C:\tekn_cloud_computing\tekn-cloud-computing>git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.53 KiB | 260.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/mayamonika998/tekn-cloud-computing
   eb9e869..5a780d1  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\tekn_cloud_computing\tekn-cloud-computing>
