Install virtualbox in Ubuntu

Supported versions= Focal Fossa | Eoan | Disco

Tested and verifed: 30 November 2019

    su
    
    cd ~/ && mkdir Downloads
#

    nano /etc/apt/sources.list


    deb http://cz.archive.ubuntu.com/ubuntu disco main
    deb [arch=amd64] https://download.virtualbox.org/virtualbox/debian disco contrib

#

    wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add - && sudo apt-get update -y && apt install libvpx5 -y

#

    cd ~/Downloads && wget https://download.virtualbox.org/virtualbox/6.0.14/virtualbox-6.0_6.0.14-133895~Ubuntu~bionic_amd64.deb && chmod +x virtualbox-*.deb && dpkg -i virtualbox-*.deb && apt install -f -y
    
#    
    Reboot and Enjoy