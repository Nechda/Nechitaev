# Shh connection
1. Generate ssh code into folder `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
2. Copy pubic part of key and configure github settings with it.
3. Add via ssh-agent new ssh key.

# Cloning repo
Firstly type `eval $(shh-agent -s)`, then use command `git clone <ssh-addr>`

#Branches
1. Creating branch: `git branch <name>`
2. Choose branch: `git checkout <branch-name>`.
3. Send new branch to server: `git push --set-upstream origin <sended-branch>`

#Branch merging
1. Use `git fetch` for getting actual versions of branches
2. Use `git branch --all` to see all branches in repo
3. Merging of two branches can be achieved by the command `git merge <another-branch-name>`

