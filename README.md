# VMware_ISO_Provision

**Configuration**

Ensure pyvmomi is installed. example: pip or pip3 install pyvmomi

Configure and add more hosts to deploy in the inventory.yml file

**Running Playbook**

Run the playbook:

```
ansible-playbook -i <inventory_file> <playbook> -e <extravars>
```
Example:
```
ansible-playbook -i inventory.yml vsphere.yml -e "vcenter_hostname= vcenter_username= vcenter_password= vm_datastore= "
```
