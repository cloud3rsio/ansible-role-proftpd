cloud3rsio.proftpd
=========

Install proftpd.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.proftpd
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `proftpd_Port` | `21` | Int |
| `proftpd_PassivePorts` | `60000 60100` | String |

Dependencies
------------

- `cloud3rsio.yumrepo_epel`

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.proftpd
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
