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

`cd macos-playbook`

`git submodule update --init`

## chmod dotfiles/install.sh
`chmod +x roles/environment/files/dotfiles/install.sh `

## ansible Setup
`ansible-playbook -vvvv macos.yml -K`

## mackup restore
- Login Dropbox

`mackup restore`

## Setting iTerm
- Change font
- <img width="356" alt="スクリーンショット 2024-02-13 17 20 08" src="https://github.com/k-youki/macos-playbook/assets/10322951/c83b403c-77aa-48a8-b30d-bf5396790bb1">
