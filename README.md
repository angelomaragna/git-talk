# Notes on a Git Talk

This is a brief list of arguments to talk about on a short git conference talk.

* brief terminology explanation: branch (and tipical branch names) head checkout push pull commit staged stash merge
* [Creating a Happy Git Environment on OS X](https://gist.github.com/trey/2722934)
* gitconfig / gitexcludes
* commands: init / status / log / commit 
* advanced commands: remote / push / pull / clone / stash / checkout / reset
* 

```
git log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
```

```
git log --graph --oneline --decorate --date=relative --all
```
* branches [branch naming best practices](http://stackoverflow.com/questions/273695/git-branch-naming-best-practices)
* git remote (adding a github and a bitbucket origin)

## The talk

### What is GIT? 
Well... read this if you want [a larger explanation](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics).
In short, git is a VCS system, hence a way to track your changes through your coding session. You install it on yuor system like any other normal software. You'll want to install the client version, while if you are configuring your server to receive your coding, you'll have to install the server version.

### When GIT should be used?

### Which are the advantages?

### Begin with your new repository
* init / clone / look inside .git
* status
* add
* commit
* log

* clone a remote repo and look at a more complex git tree

### Start 
...
git stash



[wip]

### References
* [A quick GIT guide](http://rogerdudler.github.io/git-guide/)
* [Creating a Happy Git Environment on OS X](https://gist.github.com/trey/2722934)
* [Tips to work better with git]([Tips from gitlab](https://about.gitlab.com/2015/02/19/8-tips-to-help-you-work-better-with-git/))
* [branch naming best practices](http://stackoverflow.com/questions/273695/git-branch-naming-best-practices)
