# RHEL RefConfig Playbook

## About

This Playbook configures and checks the OS Base Configuration according to the "Referenzarchitektur RHEL" of first frame networkers ag.

## OS Base Configuration

Bevore using this Playbook, please read at least Chapter 2.1 "Pre-Configuration" from Referenzkonfiguration RHEL in qWiki.

1. Modify the `inventory` file
2. Apply Playbook:

```bash
# Ausführung mit den Hosts aus Datei "inventory"
ansible-playbook apply.yml

# adhoc Ausführung auf localhost
ansible-playbook -i localhost, -c local apply.yml
```
