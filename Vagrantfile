Vagrant.configure("2") do |config| 
 config.vm.define :servidorUbuntu do |servidorUbuntu|
 servidorUbuntu.vm.box = "bento/ubuntu-20.04"
 servidorUbuntu.vm.network :private_network, ip: "192.168.100.3"
 servidorUbuntu.vm.hostname = "servidorUbuntu"
 servidorUbuntu.vm.provision "file", source: "C:/Users/HP/Desktop/Azure/vmaz1_key.pem", destination: "/home/vagrant/"
 end
end