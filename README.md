# Packer Debian 7 template

## Instructions

```
packer build -only=virtualbox-iso template.json
vagrant box add wheezy64 packer_virtualbox-iso_virtualbox.box
```
