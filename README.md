## Nexus Server

This playbook will install the sonatype/nexus3 docker version server

## Install

```
ansible-playbook -i inventory site-common.yml
ansible-playbook -i inventory site.yml
```

## Demo

[![asciicast](https://asciinema.org/a/a0vgjZ4IwWiD2W6jR5et1MRDg.svg)](https://asciinema.org/a/a0vgjZ4IwWiD2W6jR5et1MRDg)

Then, you need to enter via this URL: https://nexus.enciso.website

User is `admin` and the password will be the string auto-generated located here:
```
ssh centos@nexus.enciso.website
cat /data/nexus/data/admin.password
```
