# Description

Deploy [Cern's CVMFS prometheus exporter](https://gitlab.cern.ch/cloud/cvmfs-prometheus-exporter) to a system using ansible.

# Requirements

- Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)
- jmespath on deployer machine. If you are using Ansible from a Python virtualenv, install jmespath to the same virtualenv via pip.
- gnu-tar on Mac deployer host (brew install gnu-tar)

# Role Variables

None so far.

# Thanks!

Adapted wholesale from [Cloud Alchemy's](https://github.com/cloudalchemy) ansible roles.