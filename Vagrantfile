Vagrant::Config.run do |config|
  config.vm.box = "virtualmachine"
  config.vm.forward_port 80, 3000
  config.vm.provision :puppet
end

