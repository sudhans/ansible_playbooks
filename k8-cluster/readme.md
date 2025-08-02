This playbook is for setting up K8 cluster with kubeadm for a single master node + worker node(s) configuration.

Prerequisites:
 - host machine is online
 - host machine has python3 installed
 - you can ssh into the host machine
 - host machine has ubuntu desktop or server. Other skinned/slim debian variants might need additional packages to be installed.


To run this playbook,
 - cd k8-cluster
 - ansible-playbook -i inventory.yml playbook.yml --ask-become-pass

if the ansible_user is already part of passwordless sudo users on the remote machine, --ask-become-pass can be skipped.


Sample Output:
➜  

