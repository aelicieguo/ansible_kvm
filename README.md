# ansible_kvm

###################################################################################################

DRAFT

###################################################################################################

#This git repository holds ansible scripts to automate the process of populating VM's on RHEL 7.4 for OpenShift 3.7 deployment.

The variable file (playbooks/prerequisites.yaml) is editable to suit different use cases. The curent cluster is of:
- 1 RH Satellite VM
- 1 Webadmin # to monitor gluster health
- 1 Gluster node # to deploy Container-Ready Storage (CRS)
- 1 Master node
- 2 Worker nodes, and
- 1 Infra node

#File description:
