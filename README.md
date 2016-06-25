## Introduction ##
This is a set of Virtualbox tools written for general management of Virtualbox VMs, such as turning a VM on or off through console.

## Setup ##
In your `vm.list` file, add the list of VMs you want available to the tool.

Example:  
```
test1
test2
```

## Usage ##
Turn on all VMs:  
`vmon --all`

Turn off all VMs:  
`vmoff --all`

Turn on a specific VM:  
`vmon <nameofvm>`

Turn off a specific VM:  
`vmoff <nameofvm>`
