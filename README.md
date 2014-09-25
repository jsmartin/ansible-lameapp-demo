Spin up the VMs:

    vagrant up node-1 node-2 node-3 haproxy

Add the vagrant key to your keyring:

    ssh-add ~/.vagrant.d/insecure_private_key


Run ansible:

    ansible-playbook -v site.yml
