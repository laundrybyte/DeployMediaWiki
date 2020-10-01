# DeployMediaWiki
Ansible YAML playbook for automated deployment of MediaWiki

Requires the following Ansible packages: community.mysql and posix. Install these by running "ansible-galaxy collection install community.mysql" and "ansible-galaxy collection install ansible.posix" on the control node.

After running playbook, open web browser and go to IP address(es) of managed nodes (in this instance, group "server") and proceed through final installation steps. Scp downloaded files to <Managed Node>:/var/www/mediawiki.
