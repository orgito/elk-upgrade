> This code is published as part of the corresponding blog article at the [Toptal Engineering Blog](https://www.toptal.com/ansible/update-elastic-stack-ansible-playbooks)
>
> Visit https://www.toptal.com/blog and subscribe to our newsletter to read great posts!


# Ansible Playbook to upgrade the Elastic Stack

For upgrades withing the same major version. Eg: 6.4.3 to 6.5.0.

## Usage:

Edit the `inventory` to reflect your setup, run the playbook:

``` bash
$ ansible-playbook -i inventory -e elk_version=6.5.0 main.yml
```
