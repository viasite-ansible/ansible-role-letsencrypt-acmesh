[![Build Status](https://travis-ci.org/viasite-ansible/ansible-role-letsencrypt-acmesh.svg?branch=master)](https://travis-ci.org/viasite-ansible/ansible-role-letsencrypt-acmesh)

# ansible-role-letsencrypt-acmesh

Example:

```
letsencrypt_acmesh_certs:
  - domains: [ example.com ]
    deploy_path: "/path/to/deploy"
    args: "--dns dns_selectel"
```
