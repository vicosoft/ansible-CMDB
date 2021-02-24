# ansible-CMDB
Playbooks for creating machine inventories for the CMDB.

## Settings

Change the value directory for output files in:

```
roles/cmdb/create_cmdb/vars/main.yml
```

## How to run:

To run tasks, change the option value.

```
$ ansible-playbook playbooks/cmdb/create_cmdb.yml --extra-vars="cmdb_host=HOSTNAME"
```

or for all hosts:

```
$ ansible-playbook playbooks/cmdb/create_cmdb.yml --extra-vars="cmdb_host=*"
```
