# My notes and work through the course

[Link](https://www.udemy.com/course/linux-shell-scripting-projects/)

Using Vagrant
sudo apt setup vagrant

vagrant up 'name'
vagrant box add USER/BOX
vagrant box add jasonc/centos7

vagrant ssh [VM_NAME]

exit

vagrant halt [VM] - Stops the VM
vagrant up [VM] - Starts the VM
vagrant suspend [VM] - Suspends the VM
vagrant resume [VM] - Resumes the VM
vagrant destroy [VM]

Vagrant.configure(2) do |config|
    config.vm.box = "jasonc/centos7"
end


