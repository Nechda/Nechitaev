1. Creating a new branch
    1.1. Clone the repository if necessary. Enter repository on your device using the cd command.
    1.2. Run:
        git branch branchname
        in order to initialize a new branch.
    1.3. Run:
        git checkout branchname
        to switch to another branch. commit hashes can also be passed as argument.

2. Pushing branch changes
    2.1. Use
        git add filename
        or
        git add . (add all files except for listed in .gitignore)
        to add changes to the commit
    2.2. Run
        git commit -m "text"
    2.3. Run
        git push
        to upload changes to server.