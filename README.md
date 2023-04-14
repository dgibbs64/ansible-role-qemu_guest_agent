# qemu_guest_agent

An [Ansible](https://www.ansible.com) role that detects QEMU and installs qemu-guest-agent on Linux when required on a qemu virtual machine.

QEMU (Quick EMUlator) is a free and open-source emulator and virtualization software. Used by many popular virtualisation platforms such as [Proxmox](https://www.proxmox.com/en/), [VirtualBox](https://www.virtualbox.org/), [KVM](https://www.linux-kvm.org/page/Main_Page), [Xen](https://xenproject.org/), [OpenStack](https://www.openstack.org/) and more.

The `qemu-guest-agent` is a helper daemon, which is installed on the guest (virtual machine). It is used to exchange information between the host and guest, and to execute commands in the guest.

Packages installed:

<p align="center">
<a href="https://app.codacy.com/gh/dgibbs64/ansible-role-qemu_guest_agent"><img src="https://img.shields.io/codacy/grade/1a892d499efd4dabb73beffa8d64ed01?logo=codacy&style=flat-square" alt="Codacy grade"></a>
<a href="https://github.com/dgibbs64/ansible-role-qemu_guest_agent/actions/workflows/molecule.yml"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/dgibbs64/ansible-role-qemu_guest_agent/molecule.yml?label=molecule&logo=ansible&style=flat-square"></a>
<a href="https://galaxy.ansible.com/dgibbs64/qemu_guest_agent"><img alt="Ansible Quality Score" src="https://img.shields.io/ansible/quality/61041?logo=ansible&style=flat-square"></a>
<a href="https://galaxy.ansible.com/dgibbs64/qemu_guest_agent"><img alt="Ansible Role" src="https://img.shields.io/ansible/role/d/61041?color=EE0000&logo=ansible&style=flat-square"></a>
<a href="https://galaxy.ansible.com/dgibbs64/qemu_guest_agent"><img alt="GitHub tag (latest by date)" src="https://img.shields.io/github/v/tag/dgibbs64/ansible-role-qemu_guest_agent?color=EE0000&label=release&logo=ansible&style=flat-square"></a>
<a href="https://github.com/dgibbs64/ansible-role-qemu_guest_agent/blob/main/LICENSE.md"><img src="https://img.shields.io/github/license/dgibbs64/ansible-role-qemu_guest_agent?style=flat-square" alt="MIT License"></a>
</p>

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
---
- name: Linux Admin Packages
  hosts: all
  roles:
    - role: "dgibbs64.qemu_guest_agent"
```

## License

MIT

## Author Information

- [Daniel Gibbs](https://danielgibbs.co.uk)
