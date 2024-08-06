Vagrant.configure("2") do |config|
  config.vm.define "servidor1" do |servidor1|
    servidor1.vm.box = "ubuntu/bionic64"
    servidor1.vm.network "private_network", ip: "192.168.56.101"
    servidor1.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
  end

  config.vm.define "servidor2" do |servidor2|
    servidor2.vm.box = "ubuntu/bionic64"
    servidor2.vm.network "private_network", ip: "192.168.56.102"
    servidor2.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
  end

  config.vm.define "servidor3" do |servidor3|
    servidor3.vm.box = "ubuntu/bionic64"
    servidor3.vm.network "private_network", ip: "192.168.56.103"
    servidor3.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
  end
end

