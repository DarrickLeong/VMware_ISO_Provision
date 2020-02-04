# VMware_ISO_Provision

**Configuration**

Ensure pyvmomi is installed. example: pip or pip3 install pyvmomi

Configure and add more hosts to deploy in the roles/vmware_provision/vars/main.yml

**Running Playbook**

Run the playbook:

```
ansible-playbook <playbook> -e <extravars>
```
Example:
```
ansible-playbook vsphere.yml -e "vcenter_hostname= vcenter_username= vcenter_password= vm_datastore= "
```
