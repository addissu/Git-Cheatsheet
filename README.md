# Git-Cheatsheet
For ITC-134

Basic Commands

    Git Help: shows list of basic available commands

    Git Clone <Repository URL>: Clone a repository to a local machine

    Git Branch: List branches. Labels currently viewed branches with green highlight and *

    Git Status: Lists the files that have been changed, added or, commited

    Git Commit -a -m "message": commit any changes made on local machine



Linux


Ls / directory listing
 git show [commit] / Outputs metadata and content changes of the specified commit
Cd / change directory
Head file / output first ten files
Man command / manual command
 git log / Lists version history for the current branch


Windows

     rmdir <repository name> /s /q: to remove working copy off local machine

    SSL Certificate error: git config --system http.sslcainfo "C:\Users\YOURUSERNAMEHERE\AppData\Local\Programs\Git\mingw64\ssl\certs\ca-bundle.crt"

Creating/Using



 git diff / Compare modified files
git push origin master / push to default
Git remote / show remote
git pull origin <branchname> / pull specific branch
Git branch -a / show all branches
Git clone + (url) / clone to local host



Collaboration

Git init / create new repository / initialize
git config --global alias.st status / Create an alias (shortcut) for git status
Which git / See where Git is located
ls -la / show folder content
git --version / get the version of git



Jargon


Functor / something that supports maps and lists
Semigroup / anything that supports appending
Applicative / extension of functor


Monad / support for bind
