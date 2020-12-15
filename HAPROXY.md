# Haproxy Setup

This playbook use haproxy as a TLS proxy reverse. In order to use https, you need to provide a ssl certificate file, so we create this file using the following command

```
sudo cat /etc/letsencrypt/live/docs-planet.site/fullchain.pem \
  /etc/letsencrypt/lve/docs-planet.site/privkey.pem | pbcopy
```
