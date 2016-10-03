# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "bento/centos-6.8"
  config.vm.network "private_network", ip: "192.168.33.11"
  config.vm.hostname = "ldap_serv"
  config.vm.provider "virtualbox" do |vb|
    vb.cpus = 1
    vb.memory = 4096
end
end