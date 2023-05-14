# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "generic/centos8"

  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 2
  end

  config.vm.define "bash" do |srv|
    srv.vm.network "private_network", ip: "192.168.56.10"
    srv.vm.hostname = "bash"
  end

end
