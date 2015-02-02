# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "scotch/box"
  config.vm.network "private_network", ip: "192.168.33.74"
  config.vm.hostname = "admin.appandmap.dev"
  config.vm.synced_folder "/Users/alberto/Projects/appandmap", "/var/www/appandmap", type: "nfs"
  config.vm.provider :virtualbox do |v|
    v.customize ["modifyvm", :id, "--memory", 4096]
  end
end
