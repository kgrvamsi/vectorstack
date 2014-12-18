Vectorstack
===========

Vector stack will install the following stack on CoreOs Vagrant box



- Cassandra 
- Apache Solr
- Nodejs
- Celery with Python 2.7
- Apache Spark 1.1.1



Install Vagrant on OSX
-

Installing Vagrant

Download the latest installer, for OSX there is a point and click .dmg installer.

![Vagrant install on MAC OSX](https://raw.githubusercontent.com/kgrvamsi/vectorstack/master/osx-yosemite-vagrant.png) 


Run the .dmg and install the Vagrant.pkg package file. The binary gets installed in the Applications folder with a link to the /usr/bin so it is added to the shell path.

The user data for Vagrant is filed in the directory from which vagrant was used and is stored in an invisible directory named .vagrant.d