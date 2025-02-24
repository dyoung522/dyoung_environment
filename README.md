Role Name
=========

My personal environment setup.

Example Playbook
----------------

Install the role from the command line:

```shell
ansible-galaxy role install --force git+https://github.com/dyoung522/dyoung-environment
```

Running from the command line on localhost:

```shell
ansible -K localhost -c local -m include_role -a name=$USER-environment
```

License
-------

MIT

Author Information
------------------

Donovan C. Young
