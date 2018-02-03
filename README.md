# oracledb_swonly
Oracle 12c database software only install

## Requirements

N/A

## Role Variables

|Name|description|type|default|
|---|---|---|---|
|N/A|N/A|N/A|N/A|

## Dependencies

N/A

## Example Playbook

	- name: PLAY | Install Oracle database software only
	  hosts: [databases]
	  become: true
	  become_method: 'sudo'
	  roles:
	    - { role: oracledb_swonly }

## License

MIT

## Author Information

|Author|E-mail|
|---|---|
|Bob Winter|TBD|

## References

* [Simple Steps To Perform Opatch Maintenance With Ansible](https://blog.pythian.com/opatch-maintenance-with-ansible/)