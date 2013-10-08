# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|

  config.vm.define "nodejs" do |nodejs|
    nodejs.vm.box = "precise64"
    nodejs.vm.box_url = "http://files.vagrantup.com/precise64.box"
    nodejs.vm.forward_port 8000, 4567
    nodejs.vm.host_name = "nodejs"
    nodejs.vm.provision :shell, :path => "provision.sh"
  end

end
