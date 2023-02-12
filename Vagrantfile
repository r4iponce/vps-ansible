# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.provider "libvirt" do |vconfig|
    vconfig.memory = 2048
    vconfig.cpus = 3
   end
  config.vm.box = "fedora/37-cloud-base"
    config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "playbooks/vagrant.yml"
  end
end
