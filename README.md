# RHV-Ansible-Toolkit

Clone this repository to the RHV-M system.

Make your own copy of the ansible-scripts so that when you pull new updates you don't overwrite the changes you make in your environment.

cp -pr RHV-Ansible-Toolkit/ansible-scripts .

cd ansible-scripts

Edit the file host_auth_variables and set the RHV-M system name, admin user and password in this file

Edit the files to properly name the cluster / data-center / host names / VM names per your RHV environment. The scripts are ready to use.

If you update your environment, keep track of the updated files and make the changes for your environment.
