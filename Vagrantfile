Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/focal64"

  config.vm.provider "virtualbox" do |vb|

    vb.cpus = 1
    vb.memory = "1024"

  end

  config.vm.network "private_network", type: "static", ip: "192.168.56.100"
  config.vm.network "forwarded_port", guest: 80, host: 8080



end