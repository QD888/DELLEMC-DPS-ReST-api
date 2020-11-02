# DELLEMC-DPS-Postman-Collections-RESTAPI for PowerProtect
Download or clone the repo and import PowerProtect 19.5 Environment.postman_environment.json and PowerProtect 19.5.postman_collection.json files into Postman.

## Power Protect Data Manager (PPDM) 19.6
Once you import collections and environment variables (both are JSON), you need to modify the following environment variables.

```
ppdmsrv - enter your PPDM server or ip
ppdmuser - PPDM admin user id
ppdmpasswd - Password

vcenter-host - vcenter host/ip, only needed when you want to perform image restore of a VM
vcenter-username - vcenter username only needed when you want to perform image restore of a VM
vcenter-password - vcenter password only needed when you want to perform image restore of a VM
```
We started here with postman path variables which you should use and change for individual IDs int the gui
![](images/postnamepathvar.PNG)
The rest of the variables will be updated automatically based on the API response.

![](images/ppdm.PNG)
