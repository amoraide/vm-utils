## Introduction ##
This is a set of Virtualbox tools written for general management of Virtualbox VMs, such as turning a VM on or off through console.

## Setup ##
In your `vm.list` file, add the list of VMs you want available to the tool.

Example:  
```
test1
test2
```
I typically symlink the tools in `/usr/bin` though up to you.

## Usage ##
### Tools ###
```
vmon
vmoff
vmstate
vmlist
```
### Commands ###
#### vmon ####
```
vmon --all
vmon <vm name>
```
#### vmoff ####
```
vmoff --all
vmoff <vm name>
```
#### vmstate ####
```
vmstate --all
vmstate <vm name>
```
#### vmlist ####
```
vmlist
vmlist --all
vmlist --valid
vmlist <vm name>
```
