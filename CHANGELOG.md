# 0.3.1 / _Unreleased_

- Configure the VM also on `vagrant provision` ([GH-12][])
    * Hook to all commands that trigger provisioning action

# 0.3.0 / 2013-07-12

- Support the [AWS provider](https://github.com/mitchellh/vagrant-aws) ([GH-10][])
- Support `vagrant rebuild` command of the [Digital Ocean provider](https://github.com/smdahlen/vagrant-digitalocean) ([GH-11][])
- Do not add the default port to complete URIs (e.g. `http://proxy`) ([GH-9][])

# 0.2.0 / 2013-07-05

- Add Apt proxy configuration for FTP URIs ([GH-5][])
- Warn and fail if Vagrant is older than v1.2.0 ([GH-7][])
- New [home page](http://tmatilai.github.io/vagrant-proxyconf/) ([GH-8][])

# 0.1.1 / 2013-06-27

- Don't crash if there is no configuration for us in the Vagrantfiles ([GH-2][])
    * Related [Vagrant issue](https://github.com/mitchellh/vagrant/issues/1877)

# 0.1.0 / 2013-06-27

- Initial release
- Support for Apt proxy configuration
- Based heavily on [vagrant-cachier](https://github.com/fgrehm/vagrant-cachier) plugin


[GH-2]:  https://github.com/tmatilai/vagrant-proxyconf/issues/2  "Issue 2"
[GH-5]:  https://github.com/tmatilai/vagrant-proxyconf/issues/5  "Issue 5"
[GH-7]:  https://github.com/tmatilai/vagrant-proxyconf/issues/7  "Issue 7"
[GH-8]:  https://github.com/tmatilai/vagrant-proxyconf/issues/8  "Issue 8"
[GH-9]:  https://github.com/tmatilai/vagrant-proxyconf/issues/9  "Issue 9"
[GH-10]: https://github.com/tmatilai/vagrant-proxyconf/issues/10 "Issue 10"
[GH-11]: https://github.com/tmatilai/vagrant-proxyconf/issues/11 "Issue 11"
[GH-12]: https://github.com/tmatilai/vagrant-proxyconf/issues/12 "Issue 12"
