# CourseDevEnv

## Setup

1. clone needed repositories under this repository
1. run `vagrant up` to start vm
1. setup the projects with their documentation
   * use `vagrant ssh` to login to vm
   * source code should be found from under `/home/vagrant/course` folder if cloned properly under this repository

## Commands

* `vagrant up` - starts vm
* `vagrant halt` - shutdowns the vm
* `vagrant destroy -f` - deletes the vm
* `vagrant ssh` - ssh into the vm
* `vagrant provision` - rerun the provision

All of the commands needs to be run on same folder where the `Vagrantfile` is located. If you modify the `Vagrantfile` then the vm needs to restarted with `vagrant halt` and `vagrant up` commands.