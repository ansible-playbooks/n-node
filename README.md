Ansible / n-node
================

This is an ansible playbook to install [n](https://github.com/visionmedia/n)(Node.js version manager) and the latest stable version of Node.js on your server(s).


Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

    ansible-playbook -i inventory-file -u root main.yml


License
-------

MIT/X11