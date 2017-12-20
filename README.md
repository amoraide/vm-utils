## Introduction ##
This is a set of Virtualbox tools written for general management of Virtualbox VMs, such as turning a VM on or off through console. Please note, this toolset's primary use is to do things to a headless VM server through the console.

My own personal usage of these tools is to better manipulate environments where server to server communication is the norm.

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
vmon <vm>
vmon --head <vm>
vmon <vm1> --head <vm2> ...
vmon <vm1> <vm2> ...

```
#### vmoff ####
```
vmoff --all
vmoff <vm>
vmoff <vm1> <vm2> ...
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
