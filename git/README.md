# **Follow these steps to configure your git repository:**
##    - Navigate to the folder where you want to create a git repository and open git bash
##    - Initialize a new Git repository: 
###        `git init`
##    - Show all git configurations: 
###        `git config -l`
##    - Set local user.name and user.email(if you want to set the global configurations you can can use the `global` keyword instead of local):
###        `git config --local user.name "<name>"`
###        `git config --local user.email "<emailid>"`
##    - Generate SSH key pair: 
###        `ssh-keygen`
##    - Add the generated public key to GitHub:
###        GitHub > Settings > Manage SSH & GPG Keys > Add new key > Add Public Key
##    - Test the SSH connection to GitHub:
###        `ssh -T git@github.com` --> This will give error: git@github.com: Permission denied (publickey). 
###        (Why? often happens when the SSH key is not correctly set up or not associated with your GitHub account)
###        - Solution: 
####            Start the SSH agent: `eval "$(ssh-agent -s)"`
##    - Add your private key to the SSH agent:
###        `ssh-add ~/.ssh/your_private_key`
##    - Now Test the SSH connection to GitHub
###        Hi X! You've successfully authenticated, but GitHub does not provide shell access.
##    - Once the connection is succcessful create a repo in Github and clone the repo:
###        `git clone git@github.com:sovank/DevOpsPortfolio.git`
##    - Now you have the clone of the remote  configured with local. You can now push your changes. Enjoy!
![#f03c15] //hrkejhre
![#f03c15]
