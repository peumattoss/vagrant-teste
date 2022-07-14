
Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"



  
  config.vm.network "forwarded_port", guest: 80, host: 8888

  config.vm.network "forwarded_port", guest: 80, host: 8888, host_ip: "127.0.0.1"

  config.vm.disk :disk, name: "HD", size: "50GB", primary: true


  config.vm.provider "virtualbox" do |vb|
  vb.cpus = "2"

  vb.name = "teste_zeppelin"

  vb.memory = "4096"

  

  
  end

 

end
