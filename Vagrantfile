Vagrant::DEFAULT_SERVER_URL.replace('https://vagrantcloud.com')
Vagrant.configure("2") do |config|
  config.vm.define "dock" do |c|
    c.vm.box = "geerlingguy/centos7"
    c.vm.provision "shell", inline: "mount --make-rprivate /", run: "always"
  end
end
