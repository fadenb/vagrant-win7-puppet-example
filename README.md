# vagrant-win7-puppet-example
Just a minimal example on how to use vagrant with a Windows 7 basebox and puppet.

## Requirements
### Vagrant
* [https://github.com/WinRb/vagrant-windows](https://github.com/WinRb/vagrant-windows "vagrant-windows") installed

### Basebox
* See [vagrant-windows readme](https://github.com/WinRb/vagrant-windows#creating-a-base-box)
* Installed puppet
 * Use msi from [https://downloads.puppetlabs.com/windows/](https://downloads.puppetlabs.com/windows/)
* Make sure to modify `config.vm.box = "tiny7_puppet3.3.1"` in [Vagrantfile](/Vagrantfile) according to your basebox name
