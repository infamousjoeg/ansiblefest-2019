awsec2-provision
=========

Provisions an EC2 instance in AWS based on variable values provided.

Requirements
------------

* boto3 `pip3 install boto3`

Role Variables
--------------

* ami_id
* assign_public_ip
* instance_tags_name
* instance_tags_role
* keypair
* region
* security_group
* subnet
* type

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: roles/awsec2-provision, ami_id: ami-123456789, instance_tags_name: Ubuntu Client, instance_tags_role: ubuntu_client }

License
-------

MIT

Author Information
------------------

Joe Garcia, DevOps Security Engineer, CyberArk - [Twitter](https://twitter.com/Joe_Garcia)