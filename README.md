Ansible Role: Corp-Proxy
========================

Working in a highly regulated cooperate IT infrastructure, the need to have proxy settings all over the place to get access to various internet resources is required. To help colleagues with the general setup for various tools used in our projects, this role can be used. A specific set of tools is taken into account.

Requirements
------------

None. For now, the role checks if the tools mentioned in it are installed, but does not enforce the installation during its execution.

Role Variables
--------------
```
coorp_proxy_url_http:
coorp_proxy_url_https:
coorp_proxy_url_noproxy:
coorp_proxy_username:
coorp_proxy_password:
coorp_proxy_tools: [default]
  - pkg_mgr
  - bash
  - docker
```


Dependencies
------------

None.

Example Playbook
----------------


License
-------

BSD

Author Information
------------------

Matthias Preu <5973515+mpreu@users.noreply.github.com>