# VMware_ISO_Provision
Configure Vm provision in role

Ensure pyvmomi is installed. example: pip or pip3 install pyvmomi

Configure and add more hosts to deploy in the roles/vmware_provision/vars/main.yml

Run Playbook with extra vars example:

ansible-playbook vsphere.yml -e "vcenter_hostname= vcenter_username= vcenter_password= vm_datastore= "
