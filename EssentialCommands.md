# List of essential commands

## Basic setups

* `git --version` to check whether git has been installed
* `git config --global user.name NAME` (replace `NAME` with your name)
* `git config --global user.email your.email@yourmailserver.com` 

## Set up git in a local folder

* `git init` to set up git in a local folder; just need to do it once, in the main project folder
* `git status` to check status
* `git add .` or `git add FILENAME` to add all or certain files into tracking
* `git commit -m MESSAGE` to commit the tracked changes
* `git log` to see list of past git commits; type `q` to quit and go back to terminal
* `git checkout ID` to go back to a previous commit
* `git checkout main` (or `git checkout master`, depending on how you name the branch) to go to latest commit

## Connect with Github

* `git pull` to sync Github changes to your local computer
* `git push` to sync your local changes to Github
