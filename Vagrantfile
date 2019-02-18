Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "vagranthost"
  config.vm.network "private_network", ip: "192.168.50.10"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
    vb.cpus = "2"
  end
end
