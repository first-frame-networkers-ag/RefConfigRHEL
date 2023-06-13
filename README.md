# RHEL RefConfig Playbook

## About

This Playbook configures and checks the OS Base Configuration according to the "Referenzarchitektur RHEL" of first frame networkers ag.

## OS Base Configuration

Bevore using this Playbook, please read at least Chapter 2.1 "Pre-Configuration" from Referenzkonfiguration RHEL in qWiki.

Before applying this Playbook make sure you've checked the `inventory` file for hosts and varibles.

Apply Playbook:

```bash
ansible-playbook apply.yml
```
