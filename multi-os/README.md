# Vagrant : 

This Vagrant file will use an ansible playbook and:
- Will Create multiple machines (CENTOS6, CENTOS7, UBUNTU16, UBUNTU18, UBUNTU20, AMAZON LINUX, AMAZON LINUX 2)
- Will add a user named 'testuser' and add the public key to the machines as well for passwordless authentication
- This can be used to create a Fleet of multi-distro machines for testing purpose.

## Getting Started

One just needs to install required version of vagrant & ansible on his machine to use this Vagrant file.

### Prerequisites

Following are the pre-requists for this Vagrantfile to run

```
Vagrant version: >=2.2.7
ansible version: >=3.8.2
```

### Using the vagrant files

* Copy the needed vagrant files/folder and anyother files part of this on your machine
* Check the pre-requisites are present
* run vagrant up

## Built With

* [vagrant](https://www.vagrantup.com/docs/index.html) - A utility for managing the lifecycle of virtual machines. 

## Contributing

* Contributions are welcome
* TBD

## Authors

* **Imran Bhullar** - *Initial work* - [Imran Bhullar](https://www.imranbhullar.com)


## License

* **Apache License, Version 2.0**
