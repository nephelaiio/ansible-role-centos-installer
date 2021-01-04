# nephelaiio.centos-installer

[![Build Status](https://github.com/nephelaiio/ansible-role-centos-installer/workflows/CI/badge.svg)](https://github.com/nephelaiio/ansible-role-centos-installer/actions)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nephelaiio.centos--installer-blue.svg)](https://galaxy.ansible.com/nephelaiio/centos-installer/)

An [ansible role](https://galaxy.ansible.com/nephelaiio/centos-installer) to produce CentOS autoinstall isos


## Role Variables

Please refer to the [defaults file](/defaults/main.yml) for an up to date list of input parameters.

## Example Playbook

```
- hosts: servers
  roles:
     - role: nephelaiio.centos_installer
```

## Testing

Please make sure your environment has [docker](https://www.docker.com) installed in order to run role validation tests. Python dependencies are listed in the [requirements file](https://raw.githubusercontent.com/nephelaiio/ansible-role-requirements/master/requirements.txt), you can install them with

```
pip install -r https://raw.githubusercontent.com/nephelaiio/ansible-role-requirements/master/requirements.txt
```

Role is tested against the following distributions (docker images):
  * Ubuntu Xenial
  * Ubuntu Bionic

You can test the role directly from sources using command `molecule test`

## License

This project is licensed under the terms of the [MIT License](/LICENSE)
