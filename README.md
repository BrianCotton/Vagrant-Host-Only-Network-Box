# Vagrant-Host-Only-Network-Box
This is a Ubuntu 12.04 box with a hostonly network setup with private IP 192.168.x.x
This box was used to follow along with book "Vagrant: Up and Running"
The box has been configured with the following:Hostname of book-example; port forwarding 80, 8082 to host; shared folder location to /vagrant; Provisioning script to install apache and share /var/www to shared directory on host machine; privage host-only network of 192.168.10.10 that can only be seen by host machine.
