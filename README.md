## docker-nginx-https-www-redirect

A simple nginx container that redirects http requests to https with the www (if not present).

Useful to be used as a default backend for Load Balancers (like the Rancher one).

A docker Hub does not configured. I build it locally and pushed it to a private repository.

Very small size: ~7 MB (alpine based). Uses about 2 MB RAM when running.

## Implemented redircts

This container is also used to redirect some domains for http/https and www/without www.

- gmk-congress -> geomechanics-congress.com
- isrm2023.com -> isrm2023.info

## License
MIT
