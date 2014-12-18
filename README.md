Vectorstack
===========

Vector stack will install the following stack on CoreOs Vagrant box



- Cassandra 
- Apache Solr
- Nodejs
- Celery with Python 2.7
- Apache Spark 1.1.1

Requirement
-
- VirtualBox 4.3.20 - [Download](http://download.virtualbox.org/virtualbox/4.3.20/VirtualBox-4.3.20-96996-OSX.dmg)
- Vagrant 1.7.1 - [Download](https://dl.bintray.com/mitchellh/vagrant/vagrant_1.7.1.dmg)

Install Vagrant on OSX
-

Installing Vagrant

Download the latest installer, for OSX there is a point and click .dmg installer.

![Vagrant install on MAC OSX](https://raw.githubusercontent.com/kgrvamsi/vectorstack/master/osx-yosemite-vagrant.png) 


Run the .dmg and install the Vagrant.pkg package file. The binary gets installed in the Applications folder with a link to the /usr/bin so it is added to the shell path.

The user data for Vagrant is filed in the directory from which vagrant was used and is stored in an invisible directory named .vagrant.d


Installation
-
Fetch the project to your local directory

	cd /path/to/download
	git clone https://github.com/kgrvamsi/vectorstack.git

Run the following command to run the vagrant box
	
	cd vectorstack
	vagrant up

Docker Orchestration
-

Install Fig inside the Vagrant Box

	cd /vectorstack 
	curl -L https://github.com/docker/fig/releases/download/1.0.1/fig-`uname -s`-`uname -m` > fig; chmod +x fig
	./fig up




