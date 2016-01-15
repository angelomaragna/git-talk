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
Well... read this if you want [a wider explanation](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics).
In short, git is a VCS system, hence *GIT is a way to track your changes and cooperate with other coders* through your developing sessions. It's a software, so you install it on Linux, OSX and yes, Windows, like any other normal software (Windows will'take longer than the others as usually).
So, when you are in your *working directory*, and you want to set a, let's say, "backup point", you will *commit* your changes.
GIT is a command line tool, but many softwares can help you in a graphical and more nice way. Typing your commands is usually faster. We'll have a look later at Atlassian's [SourceTree](https://www.sourcetreeapp.com/).

### When GIT should be used?
*Always*. If you plan to code, then you do should be using GIT. You can track a whole project, or a single feature you are developing on an existing project.  
Furthermore, GIT is the most modern way to *concurrently work on a project* with your colleagues. So if you plan to work concurrently with other colleagues on the same application, do it with GIT.

### Which are the advantages?
Git represents *a complete backup of your work*, so it represent an additional way to keep your code safe from failures on the systems you are using. Plus, it is a sort of incremental backup, so you can *go back in time* to any commit you previously did, at any time.
GIT is a *faster way to deploy your project*. If you are still using ftp, you should consider switch to git. While the ftp protocol uploads every single file of your project, GIT compresses all data and transfer it in a single file, hashing it to ensure its consistency, and unpacking it to the destination. 
Finally we can say that GIT is a simple way to handle coding conflicts. For exmaple if you push your code to a common repository, and since last time you pushed your code, another colleague did some changes, you can move your work to a branch.

Let's recap:
* is a compete backup of your work
* lets you go back in time at any commit you did
* it's faster
* let's you easily handle coding conflicts with other colleagues


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
* [Tips to work better with git, by gitlab](https://about.gitlab.com/2015/02/19/8-tips-to-help-you-work-better-with-git/)
* [branch naming best practices](http://stackoverflow.com/questions/273695/git-branch-naming-best-practices)
