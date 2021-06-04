# vcenter_esx_xio_connections

This is to create the XIO connections between vCenter Esxi hosts and XtremIO storage array.

1. XIO X2 - Create Initiator Groups, Initiators, Volumes and then Map Volumes to Initiator Groups.
2. Connect to vCenter and scan for the ISCSI adapters and create a corresponding Initiator in XIO.

You can comment/uncomment the roles in the playbook - add_vcenter_xio_roles.yml

the playbook can be invoked using ansible-playbook -i esx_idrac_10_235_44.hosts add_vcenter_xio_roles.yml
