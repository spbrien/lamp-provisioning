# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "application1" do |db|
    db.vm.box = "bento/ubuntu-16.04"
    db.vm.network "private_network", ip: "192.168.30.12"
  end
  config.vm.define "application2" do |db|
    db.vm.box = "bento/ubuntu-16.04"
    db.vm.network "private_network", ip: "192.168.30.13"
  end
  config.vm.define "application3" do |db|
    db.vm.box = "bento/ubuntu-16.04"
    db.vm.network "private_network", ip: "192.168.30.14"
  end
  config.vm.define "database" do |db|
    db.vm.box = "bento/ubuntu-16.04"
    db.vm.network "private_network", ip: "192.168.30.15"
  end
end
