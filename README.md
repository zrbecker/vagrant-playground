# Vagrant Playground

The purpose of this repository is to maintain some useful vagrant box
configurations.

You must have [https://www.vagrantup.com/](Vagrant) and
[https://www.virtualbox.org/](VirtualBox) installed.

For example one of the boxes in this repository is a docker server. To set it
up you enter the following commands

```
cd docker-base
vagrant up
vagrant ssh
sudo docker run hello-world
```

It will take a little while to download the ubuntu/xenial64 base image (if you
don't already have it cached), and run the `bootstrap.sh` script to install
docker.
