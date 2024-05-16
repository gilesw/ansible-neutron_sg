# ansible-neutron\_sg

Setup security groups (software firewalls) on Rackspace.

# Templates

see example\_template/ for a sample heat file

# Dependencies

In order to use this role you need a specific Python virtualenv. See venv directory for details.
You also need to be able to use the heat cli tool so the PATH might need adjusting

# Warning

Because of rule limits (20 I think) a group can half apply and leave the other rules missing

# Docs

https://developer.rackspace.com/docs/cloud-orchestration/v1/resources-reference/rackspace/#rackspace-cloud-loadbalancer
