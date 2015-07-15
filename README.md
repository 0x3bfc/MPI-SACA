#MPI-SACA

![Alt text](images/mpi.jpg "Open-MPI")

This package is a library based on Ansible scripting and Vagrant to deploy CLOUD-SACA an MPI-Cluster based package on multiple service providers for more information about, check out this link [CLOUD-SACA](http://www.nubios.nileu.edu.eg/tools/MainPage.html?tool=cloudSACA)

**Install Vagrant on Ubuntu distribution:**

        $ sudo apt-get install vagrant

  **RECOMMENDED**
  but I suggest to install Vagrant Binary from [here](http://www.vagrantup.com/downloads.html)

by default virtualbox is the main hypervisor for vagrant, so we do not need any plugins to use virtualbox

**Install Vagrant Azure Plugin**

Azure provides a vagrant plugin used which interfaces with it's API

     $ vagrant plugin install vagrant-azure

also import this dummy azure vagrant box
  
     $ vagrant box add azure https://github.com/msopentech/vagrant-azure/raw/master/dummy.box

**Install Vagrant Google Client Plugin**

I am using standard Vagrant 1.1 plugin installation mode, try the following command line to install google plugin 

     $ vagrant plugin install vagrant-google

also you have to import google box to vagrant to be able to create vm on GCE (Google Compute Engine)

     $  vagrant box add gce https://github.com/mitchellh/vagrant-google/raw/master/google.box


