## env Setup
`xcode-select --install`
`ssh-keygen -t rsa`

## Install HomeBrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

## Install Ansible
`brew install ansible`

## Install git
`brew install git`

## Clone 
`git clone git@github.com:k-youki/macos-playbook.git`

## ansible Setup
`ansible-playbook -vvvv macos.yml -K`

## mackup restore
- Login Dropbox
`mackup restore`
