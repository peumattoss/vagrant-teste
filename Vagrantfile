
Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"


  config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1"


  config.vm.network "private_network", ip: "192.168.33.10"

  vb.memory = "4096"

end
