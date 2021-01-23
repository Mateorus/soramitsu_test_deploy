Simple ansible playbook to install and deploy simple app.

PREREQUISITE:

You need `ansible cli` to be installed.
Repository path which is used for docker container is hardcoded in deploy role.

RUN:

$ ansible-playbook -i <your_hosts_file> -u root playbook.yaml
