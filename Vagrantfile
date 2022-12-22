# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.memory = 1024
    vb.cpus = 1
    vb.name = "servidor-centos"
  end
  config.vm.box = "centos/7"
  config.vm.provision "shell", path: "script.sh"
end
