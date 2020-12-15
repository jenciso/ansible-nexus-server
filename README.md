## Nexus Server

This playbook will install the sonatype/nexus3 docker version server

## Install

```
ansible-playbook -i inventory site-common.yml
ansible-playbook -i inventory site.yml
```

## Demo

[![asciicast](https://asciinema.org/a/a0vgjZ4IwWiD2W6jR5et1MRDg.svg)](https://asciinema.org/a/a0vgjZ4IwWiD2W6jR5et1MRDg)

Then, you need to enter via this URL: https://nexus.docs-planet.site

User is `admin` and the password will be the string auto-generated located here:
```
ssh centos@nexus.docs-planet.site
cat /data/nexus/data/admin.password
```

## Setup 


* Configure the Active Directory

![nexus-01](https://i.imgur.com/aNNJsWA.png)

* Setting user and groups LDAP mapping

![nexus-02](https://i.imgur.com/2UKPScf.png)

* Anonymous access

![nexus-03](https://i.imgur.com/Glm3avO.png)

* Create a blob Store

![](https://i.imgur.com/V757r7J.png)

![](https://i.imgur.com/y4VWn16.png)

* Create a repository

![](https://i.imgur.com/pe2zkZK.png)

* Creating docker-proxy repository

![](https://i.imgur.com/bWSpHa4.png)

![](https://i.imgur.com/2QThCQG.png)

![](https://i.imgur.com/YSzur3Q.png)

![](https://i.imgur.com/aU18T3a.png)

* Creating docker-snapshots repository

![](https://i.imgur.com/Zq4fla3.png)

![](https://i.imgur.com/oP8nJGk.png) 

![](https://i.imgur.com/4bHkou2.png)

* Creating docker-releases repository

![] 
