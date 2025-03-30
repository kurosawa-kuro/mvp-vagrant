Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  
  # vagrant-vbguest の自動更新を無効化
  if Vagrant.has_plugin?("vagrant-vbguest")
    config.vbguest.auto_update = false
  end
end
