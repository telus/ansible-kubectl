# ansible-kubectl

This package installs kubectl.

# Tunables

* ```kubectl_version```(integer) - The version for kubectl you want to install
* ```package_destination```(string) - The download destination for the kubectl package

# Example Playbook

```
- hosts: servers
  roles:
     - role: telusdigital.kubectl
```

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* Alex Podobnik | [e-mail](mailto:alexandar.podobnik@gmail.com)
