# plasm-node

Plasm node setup using ansible.
First set the ansible, and clone the repo

```sh
sudo apt update -y
sudo apt install ansible git -y
git clone https://github.com/1-macros/plasm-node.git
```

Run the ansible-playbook, replace the node_name accordingly.

```sh
ansible-playbook plasm-node/tasks/main.yml --extra-vars "node_name=your_node_name" -vvv
```

Track the node status

```sh
supervisorctl status
```

Tail the logs

```
tail -f /var/log/plasm-node.out.log
```
