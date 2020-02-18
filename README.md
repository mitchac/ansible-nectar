## Goal: Create an instance on Nectar / Melbourne Research Cloud. 

### Step 1 

Create a Conda enviroment on your computer

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands

### Step 2

Install python-openstackclient

per installation section of this doc..

https://support.ehelp.edu.au/support/solutions/articles/6000075747-api

### Step 3
Obtain nectar authentication info 

per configuration section of this doc..

https://support.ehelp.edu.au/support/solutions/articles/6000075747-api

### Step 4

Execute script to export nectar environment vars downloaded previously

### Step 5 

Clone this repo

### Step 6

cd nectar folder

### Step 7 

Run the following command..

ansible-playbook --ask-become-pass nectar.yaml

enter the password downloaded from nectar when prompted (circa 20 chars, alphanumeric)

### Notes / References

I started from the code in this repo 

https://gitlab.eng.unimelb.edu.au/christianLan/ccc-assignment2-team69/tree/master/Ansible/nectar
