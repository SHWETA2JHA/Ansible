## To set up the web server using Ansible, follow these steps:

### Clone the repository:

git clone https://github.com/SHWETA2JHA/ansible.git

### Navigate to the project directory:

cd ansible-automation/server-setup

### Update the inventory/hosts file with the IP addresses of your servers.

### Run the Ansible playbook:

ansible-playbook -i inventory/hosts playbook.yml

This will install Nginx, configure it, and deploy a simple static web page.
