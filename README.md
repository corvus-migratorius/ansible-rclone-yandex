Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

`rclone_config_path`: where to keep the configuration file (default: `/root/rclone.conf`)
`rclone_mountpoint`: where to mount the Yandex Disk share
`rclone_group`: how to name the group that will own the mountpoint

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

```yaml
roles:
  - role: rclone_yandex
    rclone_mountpoint: /mnt/yandex-disk
    rclone_group: yandex
```

License
-------

BSD

Author Information
------------------

corvus-migratorius@proton.me