# 3scale-install-playbooks

## Prequisities:
* Ansible
* OpenShift CLI

## Steps: 

1. Login into OpenShift cluster from the CLI using `oc login`

2. Clone the repository
```
git clone https://github.com/rpscodes/3scale-install-playbooks.git
```
3. Navigate to the right directory
```
cd 3scale-install-playbooks/ansible
```
4. Run the install playbook
```
ansible-playbook playbooks/install.yml -e"ACTION=install"
```
