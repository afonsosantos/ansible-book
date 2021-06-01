# Chapter 2 - Vagrant and Ansible

## Commands

To create a new box (VM):

```bash
vagrant box add geerlingguy/centos7
vagrant init geerlingguy/centos7
vagrant up
```
To shutdown the box:

```bash
vagrant halt
```

To destroy (delete):

```bash
vagrant destroy
```
To run a playbook on the box:

```bash
vagrant provision
```
