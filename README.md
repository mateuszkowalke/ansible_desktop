# ansible_desktop
Ansible config for desktops and laptops

## Install
Requires ansible to be installed on the system already, so as usuall:
```sh
sudo apt update && sudo apt upgrade -y
sudo apt install ansible
```
And then:
```sh
sudo ansible-pull U https://github.com/mateuszkowalke/ansible_desktop.git
```

## Post Install
Change the origin of the .dotfiles repo to your own fork.
