openstack_utilities
===================

Small repo with a couple of tools / examples to help with OpenStack.

Testing against Keystone v3 / Kilo.

**credentials**
* create a file in the directory in the format:
auth_url=''
username=''
password=''
project_id=''
user_domain_id=''
ssl_bundle=''

**nova_boot**
* creates a machine using the Nova client, requires Keystone v3 API / Nova v2 API
* it will prompt for each bit of information
* stores credentials in a file in the same directory, run without arguments to test
