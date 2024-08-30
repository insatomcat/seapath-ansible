# Debian Hypervisor Role

This role apply the hypervisor specific configurations (virtualisation, realtime...)

## Requirements

no requirement.

## Role Variables

- isolcpus
- vhost_vsock
- sriov_driver
- sriov
- cpusystem
- cpuuser
- cpumachines
- cpumachinesrt
- cpumachinesnort
- cpuovs
- custom_tuned_profile_path

## Example Playbook

```yaml
- hosts: cluster_machines
  roles:
    - { role: seapath_ansible.debian_hypervisor }
```
