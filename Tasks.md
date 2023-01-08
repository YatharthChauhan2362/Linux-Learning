# Tasks

## Hostname and host file configuration

*Change Host Name*

    sudo su
    cd /etc
    gedit hostname
    reboot

*Change Host File Configuration*

    sudo su
    cd /etc
    gedit hosts

*Access Website*

    sudo su
    cd /etc
    service apache2 start

## Configuring apache server

Apache server stored location

    sudo su 

    cd /var/wwww/html/

    ls

    gedit index.html

Change port of apache server

    sudo su

    cd /etc

    cd apache2

    ls

    gedit ports.conf

    cd ..

    service apache2 restart

## Software Installation

For .deb software:

    sudo su

    cd Downloads

    ls

    dpkg -i name.deb

Through github:

    sudo su

    git clone url-of-software

    ls

    cd software-name

    ./install

## Error resolving apt

    sudo su

    

