# VMware_ISO_Provision
Configure Vm provision in role

Ensure pyvmomi is installed. example: pip or pip3 install pyvmomi

Run Playbook with extra vars example:

ansible-playbook vsphere.yml -e "vcenter_hostname= vcenter_username= vcenter_password= vm_datastore= "

