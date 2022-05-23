# Documentation on the manageiq-providers-cisco_intersight

Documentation for the `manageiq-providers-cisco_intersight` provider.

 
 ### As a user I need to be able to review all the available details about the servers, racks, …

 ### As a user I need to be able to review networking information.

 ### As a user I need to be able to check the (health) status of the server running in the data centre.

### (Not supported) As a user I need to be ablet to verify the status of the BeraMetal agent. 

### (Not supported) As a user I need to be able to view server logs in ManageIQ

### As a user I need to be able to specify appropriate RBAC rules for the Client to access the environment.

### As a user I should be able to view a list of server profiles  (SPs)available in the system indicating which all are associated with servers and which are not so that I get a 
 full view of the inventory
 
### (Not supported) As a user I need to be able to boot a specific bootable image managed by ManageIQ
 
### (Not supported) As a user I need to be able to boot a specific bootable image for the server from the portal
 
### (Not supported) As a user I need to be able to open a remote console to the server through MIQ portal leveraging tunneled KVM of intersight
 
### As a user I need to be able to get alerts and notifications from the Intersight system
 
### Service Now Integration
 
### Data Backup and Restore
 
 ## As a user I should be able to view a list of server profiles (SPs) available in the system indicating which all are associated with servers and which are not so that I get a full view of the inventory
 
### As a user I should be able to associate or assign free Server Profile to a blade or server that does not have any SP’s currently assigned so that I can deploy workloads on them
 
### As a user I should be able to unassign a server profile associated with a server so that the server is not used for any workloads
 
### As a user I should be able to decommission a server so that the server usage is not charged to us
 
User with a specific role can decomission a server with an action from the `Lifecycle` menu. Selected servers can be decomissioned.

![Diagnostics Server](../figures/comission_decomission_server.png)

### As a user I should be able to commission a server that is in decommissioned status so that I can associate SPs for usage
 
User with a specific role can comission a server with an action from the `Lifecycle` menu. Selected servers can be comissioned. It is important to note that as soon the server is decomissioned it takes some time for Intersight to aggregates all the data.

### As a user I should be able to view the Chassis inventory to view a list of servers that are currently available in the chassis with their status
