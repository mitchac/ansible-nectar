## Goal: Create an instance on Nectar / Melbourne Research Cloud. 

### Step 1 

Clone this repo

### Step 2

Create the environment from the environment.yml file and activate the new environment "openstack"

conda env create -f environment.yml

### Step 3

Obtain nectar authentication info 

per configuration section of this doc..

https://support.ehelp.edu.au/support/solutions/articles/6000075747-api

### Step 4

Execute script to export nectar environment vars downloaded previously 

through Authentication section of the previous doc

### Step 5

cd nectar folder

### Step 6 

Run the following command..

ansible-playbook --ask-become-pass nectar.yaml

enter the password downloaded from nectar when prompted (circa 20 chars, alphanumeric)

### Notes / References

I started from the code in this repo 

https://gitlab.eng.unimelb.edu.au/christianLan/ccc-assignment2-team69/tree/master/Ansible/nectar
