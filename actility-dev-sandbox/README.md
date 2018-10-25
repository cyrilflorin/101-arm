# Create a virtual machine from Actility image in an existing virtual network

This template creates VMs for Actility DEV platform from a custom image. red, orange, green, admin -parameters.json already filled with VMs prerequisites
for this platform.

Plese note: This deployment template does not create or attach an existing Application Security Group to the virtual machine. To be added later on.

## Prerequisites

- Actility Centos 6.9 image must be create into resource group. (imageId must be updated into *-parameters.json file)
- Virtual network must be existing, with subnets already defined. (vnet name must be updated into *-parameters.json file)
