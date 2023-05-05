# Local Machine Preparation

[Vagrant](https://www.vagrantup.com/) (optional) Vagrantfile can be used for VM provisioning.

Example:

```console
abutsko@abutsko:~/contribution/devops-bootcamp-tasks/linux-vm-task(main)
$ export VAGRANT_EXPERIMENTAL="disks" # required for "disks" configuration

abutsko@abutsko:~/contribution/devops-bootcamp-tasks/linux-vm-task(main)
$ vagrant up
==> vagrant: You have requested to enabled the experimental flag with the following features:
==> vagrant: 
==> vagrant: Features:  disks
==> vagrant: 
...
abutsko@abutsko:~/contribution/devops-bootcamp-tasks/linux-vm-task(main)
$ vagrant ssh

==> vagrant: You have requested to enabled the experimental flag with the following features:
==> vagrant: 
==> vagrant: Features:  disks
==> vagrant: 
==> vagrant: Please use with caution, as some of the features may not be fully
==> vagrant: functional yet.
Welcome to Ubuntu 20.04.5 LTS (GNU/Linux 5.4.0-131-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

 System information disabled due to load higher than 1.0


0 updates can be applied immediately.

New release '22.04.1 LTS' available.
Run 'do-release-upgrade' to upgrade to it.


vagrant@ubuntu-focal:~$ 
```
