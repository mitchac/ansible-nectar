# goal - create and configure instances on Nectar cloud using ansible. 

I started from the code in this repo 

https://gitlab.eng.unimelb.edu.au/christianLan/ccc-assignment2-team69/tree/master/Ansible/nectar

consider previous ansible scripts i created before..

https://gitlab.unimelb.edu.au/macunningham/bioinf/tree/master/nectar

useful docs here..

https://docs.ansible.com/ansible/latest/modules/list_of_cloud_modules.html#openstack

this could be useful also..

https://github.com/SiteHuang/Building-a-Cloud-System

# create conda env

# install python-openstackclient

per installation section of this doc..

https://support.ehelp.edu.au/support/solutions/articles/6000075747-api

# obtain nectar authentication info 

per configuration section of this doc..

https://support.ehelp.edu.au/support/solutions/articles/6000075747-api

# execute script to export nectar environment vars downloaded previously

# clone this repo

# cd nectar folder

# run the following command..

ansible-playbook --ask-become-pass nectar.yaml

enter the password downloaded from nectar when prompted (circa 20 chars, alphanumeric)
