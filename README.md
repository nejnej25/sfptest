# sfptest
SFP testing

Specifically for Ubuntu 16.04
Running ansible 2.7.10

Reminders:
1. Change IP of the host on inventory file.
2. For skipping key host checking run `export ANSIBLE_HOST_KEY_CHECKING=False`.

ansible-playbook -i inventory main.yml --diff
