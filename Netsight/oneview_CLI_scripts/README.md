# How To
* Import the sctript = In the Extreme Management Center -> Administration -> Scripting  -> Import...
* Execute the script =  In the Extreme Management Center -> Network -> Devices -> choose group -> select more devices -> Right click -> Scripts -> ...


# Extreme Management Center version 8.0+ Scripts
| Script name   | Description   |
| ------------- |:-------------:|
|[Configure Vlan on the Port Cisco-Extreme](xml/Configure_Vlan_on_the_Port-Cisco-Extreme.xml)|Configure vlan on ports - tagged or untagged based on request. The script check if the VLAN exists. If the vlan does not exist then the script does create the vlan. Tested on EXOS 15.3 and newer. Tested on Catalyst 12.2|
|[Create EAPS protected VLAN](xml/Create_EAPS_protected_VLAN.xml)|Add Vlan to the EAPS as protected. If the vlan does not exits then it creates it. Selected ports are added as tagged or untagged. If there is only one EAPS ring then you do not need to specify the EAPS ring name. Ring ports are added as tagged automatically.|

>Be Extreme