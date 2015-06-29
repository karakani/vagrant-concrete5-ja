# Vagrant + Concrete5

## Getting Started

1. Install VirtualBox.
 * https://www.virtualbox.org/
2. Install Vagrant.
 * http://www.vagrantup.com/
3. Chef Development Kit
 * https://downloads.chef.io/chef-dk/mac/
4. Install the vagrant plugins.
 * `vagrant plugin install vagrant-omnibus`
5. Clone the repository into a local directory.
 * `git clone https://github.com/miya0001/vagrant-concrete5.git`
6. Change into a new directory.
 * `cd vagrant-concrete5`
7. Install cookbooks.
 * `berks vendor cookbooks`
8. Start a Vagrant environment.
 * `vagrant up`
9. Visit http://192.168.33.35/

## Configuration

See attributes.
https://github.com/Launch-with-1-Click/concrete5

## Contributors

* [@miya0001](https://github.com/miya0001/)
* [@ixkaito](https://github.com/ixkaito)
* [@katzueno](https://github.com/katzueno)
