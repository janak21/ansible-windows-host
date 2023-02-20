# ansible-windows-host
## Manage windows nodes using Ansible

The win group in the inventory file contains the IP address of a local Windows virtual machine. The aws_win group is the Windows server running on AWS.</br>

To run the playbook simply run the following command.</br>

`ansible-playbook playbook.yml`

</br>
If you want to run the iis_install.yml playbook on on aws_win group then run the following command.
</br>

`ansible-playbook --limit aws_win iis_install.yml`

