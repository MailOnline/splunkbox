splunkbox
=========

Vagrant box with Splunk for testing.


Requirements
------------

* [VirtualBox](https://www.virtualbox.org/)
* [Vagrant](https://www.vagrantup.com/)
* Access to MOL dev network (the box will be downloaded from an internal IP)


To use it
---------

```
$ git clone git@github.com:MailOnline/splunkbox.git
$ cd splunkbox
$ vagrant up
```

After that, the Splunk web UI should be accessible via http://10.10.10.10:8000 with username *admin* password *admin*

Removing VirtualMachine
-----------------------
```
$ vagrant destroy
```
