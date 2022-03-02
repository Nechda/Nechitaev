# Shh connection
1. Generate ssh code into folder `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
2. Copy pubic part of key and configure github settings with it.
3. Add via ssh-agent new ssh key.

# Cloning repo
Firstly type `eval $(shh-agent -s)`, then use command `git clone <ssh-addr>`.

