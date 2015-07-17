# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "http://boxes.dojo-voyage.net/package.box"

  config.vm.define :sv1 do |sv|
    sv.vm.hostname = "treasure2015"
    sv.vm.network :private_network, ip: "192.168.56.230" 
    sv.vm.provider :virtualbox do |vb|
      vb.name = "treasure2015"
    end
  end
end
