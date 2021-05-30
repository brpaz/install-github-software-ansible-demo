
# Install software from GitHub with Ansible demo.

> Demo project that shows how to use [Ansible](https://ansible.com) to install Software from GitHub. Example code for [How to keep software installed from GitHub updated with Ansible](http://brunopaz.dev/blog/how-to-keep-software-installed-from-github-updated-with-ansible) blog article.

## System requirements

* [Ansible](https://ansible.com) >= 2.9
* Python and Pip
* [github3.py](https://github3py.readthedocs.io/en/master/)

## Usage

### With Vagrant

You can test this repo, without having to install Ansible on your local machine with Vagrant.

Just run `vagrant up`, to spin a new machine.

To run the playbook on the VM:

```
vagrant ssh
cd /vagrant
ansible-playbook -i hosts setup.yml 
```

### On your local Machine

* Install Ansible - Follow the instructions for your distribution [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).
* Install dependencies:
  * `pip install -r requirements.txt`
  * `ansible-galaxy install -r requirements.yml`
* Run ansible playbook
  * ```ansible-playbook -i hosts setup.yml```


## Author

👤 **Bruno Paz**

* Website: [brunopaz.dev](https://brunopaz.dev)
* Github: [@brpaz](https://github.com/brpaz)
* Twitter: [@brunopaz88](https://twitter.com/brunopaz88)

## 📝 License

Copyright © 2021 [Bruno Paz](https://github.com/brpaz).

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
