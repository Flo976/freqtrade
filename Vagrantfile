Vagrant.configure("2") do |config|
  config.vm.synced_folder "/home/florent/Documents/GitHub/freqtrade", "/home/vagrant/freqtrade"
  # Configuration de base de la VM
  config.vm.box = "ubuntu/jammy64"

  # Configuration du réseau si nécessaire, par exemple un réseau privé
  config.vm.network "private_network", ip: "192.168.56.46"

  
end

