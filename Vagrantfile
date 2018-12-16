# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "diegovarussa/php5.5"
  config.vm.synced_folder "../", "/vagrant"
  config.vm.provision "shell",
    inline: "/vagrant/vagrant-php55/scripts/composer-install.sh"
end
