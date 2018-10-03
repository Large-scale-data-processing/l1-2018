

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.hostname = "lsdp-l1"

  config.vm.network :private_network, ip: "10.0.0.2"
  
  config.vm.synced_folder "project/", "/project"

  config.vm.provision :shell,
    inline: "apt-get update && apt-get install -y mailutils"

end
