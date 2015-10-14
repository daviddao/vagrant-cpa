# Vagrant Environment for CellProfiler

## Setup
### Install dependencies
- Install [Vagrant](https://www.vagrantup.com/)
- Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### Clone this repository and call vagrant up
1. ```git clone https://github.com/daviddao/vagrant-cpa```
2. ```cd vagrant-cpa```
3. ```vagrant up``` (This might take couple of minutes)

### Work with the environment

#### Synchronise inside vagrant-cpa folder
The current folder vagrant-cpa will be synched with /vagrant on the virtual machine
- ```git clone https://github.com/CellProfiler/CellProfiler``` (Working with Cellprofiler)
- ```git clone https://github.com/CellProfiler/CellProfiler-Analyst``` (Working with Cellprofiler Analyst)

#### SSH into the virtual machine

We can now login via SSH (password is vagrant)
```
ssh -X -p 2222 vagrant@localhost 
``` 


You can now call i.e. CellProfiler Analyst with 

```
python /Vagrant/CellProfiler-Analyst/CellProfiler-Analyst.py
```


