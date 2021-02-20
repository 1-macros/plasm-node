# plasm-node

Plasm node setup using ansible.
First set the ansible, and clone the repo

```sh
sudo apt update -y
sudo apt install ansible git -y
git clone https://github.com/1-macros/plasm-node.git
```

Run the ansible-playbook

```sh
ansible-playbook plasm-node/tasks/main.yml -vvv
```
