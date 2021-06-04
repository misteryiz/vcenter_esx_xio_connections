# vcenter_esx_xio_connections

This is to create the XIO connections between vCenter Esxi hosts and XtremIO storage array.

1. XIO X2 - Create Initiator Groups, Initiators, Volumes and then Map Volumes to Initiator Groups.
2. Connect to vCenter and scan for the ISCSI adapters and create a corresponding Initiator in XIO.
