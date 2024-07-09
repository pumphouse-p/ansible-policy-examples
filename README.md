# Ansible Policybook Examples

## Prerequisites

* [Ansible Policy CLI](https://github.com/ansible/ansible-policy)
* [Open Policy Agent (OPA) CLI](https://github.com/open-policy-agent/opa#want-to-download-opa)

## Usage

For Linux-centric policies:

```bash
ansible-policy -p playbooks/linux/<playbook>.yml --policy-dir policy/linux
```

For OpenShift Virtualization policies:

```bash
ansible-policy -p playbooks/ocp_virt/<playbook>.yml --policy-dir policy/ocp_virt
```