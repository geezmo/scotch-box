# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "scotch/box"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "admin.appandmap.dev"
  config.vm.synced_folder "/Users/alberto/Projects/appandmap", "/var/www/appandmap", :mount_options => ["dmode=777", "fmode=666"]

end
