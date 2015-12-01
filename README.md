# hadoop_dev
Set up an Hadoop Development Virtual Machine using Vagrant

## Prerequisite
* Install Vagrant
* Install Crepo from https://github.com/cloudera/crepo

## Set up the virtual machine
* Change directory to the desired subdirectory, e.g., ubuntu
* Run "vagrant up"

## Get Hadoop repo
* crepo sync

## Build hadoop
* Run "vagrant ssh"
* In the virtual machine, change directory to "/vagrant"
* Run "mvn install -DskipTests -Pdist"
