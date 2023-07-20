# GITProject
This is my GIT project.

# ENG :
# Generation ok key
gpg --full-generate-key
1 - 4096 - 0 - y - <name.surname> - - Auto-sign - O - Ignore passphrase > yes no need protection

#SHow GPG keys list
gpg --list-keys

#Export public key
gpg --armor --export <key ID>

#Set-up GIT to use GPG
git config --global user.signingkey <key ID> git config --global commit.gpgsign true

#Set-up GIT to use SSH
ssh-keygen -t ed25519 -C " " cat /home/marco/.ssh/id_ed25519.pub\n git clone git@github.com:BoujbiriMahmoud/GITProject.git

#To create a brench and move to it directly
git checkout -b Branch-Created git push <- To keep a clean git

#Use of gh
We will be using gh to create issues

$sudo apt install gh
$gh issue create --title "My new issue" --body "More details."
$gh issue create --title "My new issue" --body "More details." --assignee @me,vd17 --label "bug,enhancement" --project onboarding --milestone "creation of to-do list"


