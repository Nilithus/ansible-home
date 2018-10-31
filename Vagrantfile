Vagrant.require_version ">= 2.0.0"

Vagrant.configure("2") do |config|
  config.vm.box = "debian/stretch64"
  config.vm.provision "ansible" do |ansible|
    ansible.become = true
    ansible.verbose = "v"
    ansible.playbook = "playbooks/setup.yml"
  end
end