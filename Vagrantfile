Vagrant.configure("2") do |config|
  config.vm.box = "debian/buster64"
  config.vm.synced_folder ".", "/vagrant"
  config.vm.network "private_network", type: "dhcp"
  config.vm.provision "shell", path: "install-docker.sh"
end
