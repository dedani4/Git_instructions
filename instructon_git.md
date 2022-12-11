# Instruction for git using

### **Git** is a distributed system for version control
![git logo](git_logo.jpg)
***
## [New repository creation](https://git-scm.com/docs/git-init)

* To initialize a new repository, enter the command:

    __git init__

***
## [Show the working tree status](https://git-scm.com/docs/git-status)

* To check for changes that need to be commited enter command:

    __git status__

***
## [Add file content to index](https://git-scm.com/docs/git-add)

* To update the index using current content for preparing content to commit, enter command:

    __git add [file name]__

***
## [Record changes to the repository](https://git-scm.com/docs/git-commit)

* To commit changes in current content of the index (that was added) and create log message in pop up window (ctrl+s), enter command:

    __git commit__

* To commit changes in current content of the index (that was added) and create log message in terminal, enter command:

    __git commit -m "log massage"__

* To update the index and commit changes at the same time, enter command

    __git commit -am "log message"__

***
## [Changes presentation](https://git-scm.com/docs/git-diff)

* To compare index content and Head commit, enter comand:

    __git diff__

* To compare any two commits, enter command:

    __git diff [commitX] [commitY]__

***
## [Commit logs](https://git-scm.com/docs/git-log)

* To show commit logs, enter command:

    __git log__

* To show all commits (even older from Head), enter command:

    __git log --all__

* To show commits logs line by line, enter command:

    __git log --oneline__

* To show all commits (even older from Head) line by line, enter command: 

    __git log --all --oneline__

* To show all commits (even older from Head) line by line with branches graphic view, enter command: 

    __git log --all --oneline --graph__

***
## [Switch between commits](https://git-scm.com/docs/git-checkout)

* To update Head to match the specific commit, enter command:

    __git checkout [commit]__

* To update Head to match the latest commit, enter command:

    __git checkout master__

* To update Head to match the latest commit of special branch (switch between branches), enter command:

    __git checkout [branch name]__ 


***
***
## [_**Branching**_](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
*allows you diverge from the main line of development and continue to do work without messing with that main line.* 

*Git encourages workflows that branch and merge often*

*The __“master”__ branch in Git is not a special branch. It is exactly like any other branch. The only reason nearly every repository has one is that the* **git init** *command creates it by default and most people don’t bother to change it.*

***
## [Create, list, delete branches](https://git-scm.com/docs/git-branch)

* To show all branches, enter command:

    __git branch__  
    *(Current branch will be green highlghted)*

* To create new branch, enter command:

    __git branch [new branch name]__

* To delete branch that was *__fully merged in its upstream branch or in HEAD__*, enter command: 

    __git branch -d [branch name]__

* To force to delete branch, *__that wasn't merged in its upstream branch, or in HEAD__*, enter command:

    __git branch -D [branch name]__

***
## [Join two branches](https://git-scm.com/docs/git-merge)

* To incorporates changes from other branch into the current branch.

    __git merge [other branch name]__

