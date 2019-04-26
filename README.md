# Jenkins Installation With Vagrant & Ansible

---

The server is installed with the following packages:

- Centos 7
- Basic system packages
- Git
- JAVA 1.8.0
- Jenkins

## Prerequisites

- Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- Install [Vagrant](http://www.vagrantup.com/) (tested with 2.1.5)
- Clone this repository to the root of your project directory
  ```bash
  git clone https://github.com/abdelrahman403/vagrant-ansible-jenkins.git
  ```
- In your project directory, run `vagrant up`

## Usage

- In your browser, go to `127.0.0.1:8080`

  Jenkins can be accessed from port 8080.
