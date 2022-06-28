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
ansible-pull -U https://github.com/mateuszkowalke/ansible_desktop.git
```

If you get an error: "Could not get lock /var/lib/apt/lists/lock. It is held by process 1751 (packagekitd) - open (11: Resource temporarily unavailable)" it means that systems auto update process is holding the lock. It'll be released after it's finished (5 mins or so).

## Post Install
Change the origin of the .dotfiles repo to your own fork.
