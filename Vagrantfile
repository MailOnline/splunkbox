# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "splunkbox-0.0.3"
  config.vm.box_url = "http://10.250.133.132:8383/splunkbox-0.0.3.box"
  config.vm.network "private_network", ip: "10.10.10.10/24"

  config.vm.provider :virtualbox do |vb|
  	vb.memory = 2048
  	vb.cpus = 2
  end
end
