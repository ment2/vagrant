Kernel updates & create centos8-kernel6 Vagrant box

------------------------------------Kernel updates

[vagrant@kernel-update ~]$ uname -r
4.18.0-519.el8.x86_64

[vagrant@kernel-update ~]$ uname -r
6.6.1-1.el8.elrepo.x86_64


-----------------------------create centos8-kernel6 Vagrant box

user@Ubuntu:/media/sf_/test_vm/packer$ vagrant box list
centos8-kernel6  (virtualbox, 0)
generic/centos8s (virtualbox, 4.3.6)


user@Ubuntu:/media/sf_/test_vm/packer$ vagrant init centos8-kernel6
A `Vagrantfile` has been placed in this directory. You are now
ready to `vagrant up` your first virtual environment! Please read
the comments in the Vagrantfile as well as documentation on
`vagrantup.com` for more information on using Vagrant.

vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Box 'wlad124650/centos8-kernel6' could not be found. Attempting to find and install...
    default: Box Provider: virtualbox
    default: Box Version: 1.0
==> default: Loading metadata for box 'wlad124650/centos8-kernel6'
    default: URL: https://vagrantcloud.com/api/v2/vagrant/wlad124650/centos8-kernel6

