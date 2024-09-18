## To set up Docker and run a Nginx container using Ansible:

Clone the repository:

git clone https://github.com/SHWETA2JHA/ansible.git

Navigate to the project directory:

cd ansible-automation/docker-setup

Update the inventory/hosts file with the IP addresses of your servers.

Run the Ansible playbook:

ansible-playbook -i inventory/hosts playbook.yml

This will install Docker, pull the Nginx image, and start an Nginx container.
