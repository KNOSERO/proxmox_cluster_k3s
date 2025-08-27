# Proxmox Cluster K3s
Configurable process for managing a K3s cluster on Proxmox

## How To Run 
The project needs to be run in Jenkins as a parameterized job.

It can be executed in two modes: apply / destroy.

## Module
* [Terraform Proxmox](https://github.com/KNOSERO/proxmox_teraform_vm)
* [Ansible K3s](https://github.com/KNOSERO/ansible_k3s)
* [Ansible Docker](https://github.com/KNOSERO/ansible_docker)
* [Ansible Keepalived](https://github.com/KNOSERO/ansible_keepalived)
* [Ansible Gluster](https://github.com/KNOSERO/ansible_gluster)
* [Ansible NFS](https://github.com/KNOSERO/ansible_nfs)