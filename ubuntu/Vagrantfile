Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/focal64"
    config.vm.provider "virtualbox" do |vb|
      vb.name = "test1"
      vb.memory = "2048"
      vb.cpus = "2"
    end
    config.vm.synced_folder ".", "/vagrant", disabled: true
  end