# mongodb_org_repo

An Ansible role that installs MongoDB.org repository on EL 6/7.


## Role Variables

Available variables and their default values are listed below:

* `mongodb_org_repo_version: 3.4` - MongoDB version, versions prior to 3.0 aren't supported.
* `mongodb_org_repo_enabled: yes` - enable or disable MongoDB repository.


## Example Playbook

```yaml
    ---
    - hosts: all
      roles:
        - { role: ezamriy.mongodb_org_repo, mongodb_org_repo_version: 3.2 }
```


## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
