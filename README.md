Units for systemd and Arch Linux
==========

custom unit files for arch linux
 
 * git clone git@github.com:dearing/arch_units.git
 * cp -v arch_units/*.service /etc/systemd/system/
 * systemctl enable rackspace-virgo.service
 * systemctl start rackspace-virgo.service
 * systemctl enable rackspace-driveclient.service
 * systemctl start rackspace-driveclient.service
