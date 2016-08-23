# Space robots

vagrant file and associated ansible playbook for provisioning an ubuntu 14 environment with ROS.

Requires:
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/)

To run:
- create a python virtualenvironment and install requirements `pip install -r requirements.txt`
- Start and provision vm: `vagrant up --provision`
- To ssh in: `vagrant ssh`

To run desktop:

- in virtualbox gui, login `vagrant / vagrant`
- `startx`

TODO:

- does this work for others?
- install gazebo
