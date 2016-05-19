Purpose
-------

Spin up a usable ELK Stack deployment within Vagrant for learning and POC's.

Quick How-To
-----------
````
git clone https://github.com/mrlesmithjr/vagrant-ansible-elkstack.git
cd vagrant-ansible-elkstack
vagrant up
````
When you are done tear it all down easily...
````
./cleanup.sh
````

Requirements
------------

The following packages must be installed on your Host you intend on running all  
of this from. If Ansible is not available for your OS (Windows) you can check  
out the following..  
http://everythingshouldbevirtual.com/ansible-using-ansible-on-windows-via-cygwin

Ansible (http://www.ansible.com/home)

VirtualBox (https://www.virtualbox.org/)

Vagrant (https://www.vagrantup.com/)
