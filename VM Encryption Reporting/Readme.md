# VM Encryption Reporting Dashboard

This dashboard utilizes a VM property to report on VM encryption status.  This property is not enabled by default and must be enabled.

# How to install this dashboard

* Enable Encryption Status Property

Edit your monitoring policy to enable the Virtual Machine | Properties | Virtual Disk | Encryption Status

* Install and enable supermetric

Install the VM encryption supermetric.  This supermetric loops through all virtual disk sections of the VM and aggregate the encryption status of them to create a "VM encryption value"

* Install the view and dashboard

Install the view and dashboard to the appropriate section

# What next?

Wait a few collection cycles and see what happens!


# Questions, Comments?
    
Feel free to submit an issue or contact me @ scott.bowe@broadcom.com