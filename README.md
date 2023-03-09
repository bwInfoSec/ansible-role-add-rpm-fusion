[![Molecule Test](https://github.com/bwInfoSec/ansible-role-add-rpm-fusion/actions/workflows/molecule-test.yml/badge.svg)](https://github.com/bwInfoSec/ansible-role-add-rpm-fusion/actions/workflows/molecule-test.yml)

# bwinfosec.add_rpm_fusion
This role adds the [RPM Fusion](https://rpmfusion.org/) repository to RHEL.


## Platforms

- RHEL 8

## Install

``` sh
ansible-galaxy install bwinfosec.add_epel && ansible-galaxy install bwinfosec.add_rpm_fusion
```

## Example Playbook

```yml
- name: Add RPM Fusion (and EPEL) to RHEL hosts
  become: true
  hosts: rhel

  roles:
    - bwinfosec.add_epel
    - bwinfosec.add_rpm_fusion
```

## Requirements
- EPEL, e.g. [bwinfosec.add_epel](https://github.com/bwInfoSec/ansible-role-add-epel)

## Local Development

This role includes a *molecule* test to execute on RHEL 8.

## Licensing

This work is licensed under the [EUPL 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

## Contribution
If you want to contribute feel free to do so by creating a pull request on [github](https://github.com/bwInfoSec/ansible-role-add-rpm_fusion).


