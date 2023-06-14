# Ansible-Loops-Conditionals
Usage
Make sure you have Ansible installed on your local machine.

Clone this repository to your local machine:

git clone <repository-url>
Navigate to the cloned repository:

cd ansible-playbook-docker-python-git-java
Update the inventory.yml file with the list of servers where you want to install the packages.

Review and modify the playbook variables, if needed, in the group_vars/ directory.

Run the playbook:
ansible-playbook -i inventory.yml playbook.yml

The playbook will execute the installation tasks on the specified servers.

Sit back and relax while Ansible handles the installation of Docker, Python, Git, and Java on your servers.
