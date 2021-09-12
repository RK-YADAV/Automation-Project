# Automation-Project
Jenkins + Git + Ansible.

PROJECT KEY SUMMARY:

1. Create 3 Nodes (Used Digital Ocean Droplets).

2. In node 1, install Jenkins and make it Master Node.
   In node 2, install ansible on it and a user named ansible.

3. Make an SSH Keys for Node 1 and 2.
   Make an password less authentication for all three nodes. Jenkins -> Ansible -> Node 3

4. Add node 3 to Node 2 Ansible list of known hosts under webservers.

5. Add a worker node, to Jenkins main server.
