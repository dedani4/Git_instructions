# Instruction for git using

Git is application for version control

* ## New repository creation

To initialize a new repository, enter the command:

    git init


* ## Show the working tree status

To check for changes that need to be commited enter command:

    git status

* ## Add file content to index

To update the index using current content for preparing content to commit, enter command:

    git add <file name>

* ## Record changes to the repository

To commit changes in current content of the index (that was added) and create log message in pop up window (ctrl+s), enter command:

    git commit

To commit changes in current content of the index (that was added) and create log message in terminal, enter command:

    git commit -m "log massage"

To update the index and commit changes at the same time, enter command

    git commit -am "log message"

* ## Changes presentation

To compare index content and Head commit, enter comand:

    git diff

To compare any two commits, enter command:

    git diff <commitX> <commitY>

* ## Commit logs

To show commit logs, enter command:

    git log

To show all commits (even older from Head), enter command:

    git log --all

To show commits logs line by line, enter command:

    git log --oneline

To show all commits (even older from Head) line by line, enter command: 

    git log --all --oneline


