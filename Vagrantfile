# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.require_version ">= 1.5.0"
Vagrant.configure(2) do |config|
  config.vm.box = "data-science-toolbox/data-science-at-the-command-line"
  config.vm.network "forwarded_port", guest: 8000, host: 8000
  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.memory = 2048
    vb.cpus = 2
  end
end
