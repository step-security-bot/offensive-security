# Kali Linux WSL Ninja

1. Install Kali Linux WSL fron Windows Store 

        https://www.microsoft.com/en-us/p/kali-linux/9pkr34tncv07?activetab=pivot:overviewtab
    
2. Open Kali Linux, follow the wizard for install define your username and password and reset root password

        sudo passwd
    
3. Add this path to Windows Defender as an exception

        C:\Users\usuario\AppData\Local\Packages\KaliLinux.*

#
33.37 GB free space required in your disk. Repeat it until you see that really were installed successfully at 100%.

    sudo apt-get autoclean && apt-get clean cache && sudo apt update && apt install kali-linux-full kali-linux-all && sudo apt full-upgrade -y
#    
    sudo apt-get autoclean && apt-get clean cache && sudo apt update && apt install git screen neofetch screenfetch synaptic lsb-release software-properties-common forensics-all forensics-all-gui forensics-extra-gui forensics-extra zipalign curl dirmngr apt-transport-https jq postgresql nginx sslstrip hping3 hashcat openvpn network-manager-openvpn-gnome gnome gdm3 gnome-tweaks gnome-tweak-tool synaptic caca-utils inetutils-traceroute python-nautilus mdbtools make libncurses5-dev module-assistant mingw-w64 synaptic autopsy pcsxr gir1.2-nautilus-3.0 sshfs resolvconf nmap net-tools ssh gcc python2 python3 gimp php-mbstring php-gettext python-dev python-setuptools python-setuptools python-dev python-pip python3-pip gparted pvm-dev compiz ndisc6 steghide httrack mesa-utils ethtool build-essential macchanger gnome winbind wget nano git file-roller p7zip-full p7zip-rar rar unrar zip unzip unace bzip2 lhasa jlha-utils lzip xz-utils mercurial make pulseaudio libcanberra-pulse blender blender-data byzanz calibre calibre-bin dde-calendar dde-qt5integration docker expect ffmpeg fig2dev fonts-dejavu gawk ghex gnome-dictionary hexchat hexchat-common hexchat-perl hexchat-plugins hexchat-python3 hwdata inkscape libavresample4 libblosc1 libchm1 libdbusextended-qt5-1 libdcmtk14 libdframeworkdbus-dev libdframeworkdbus2 libdmr-dev libdmr0.1 libdtkcore-bin libdtkcore-dev libdtkcore2 libdtkwidget-dev libdtkwidget2 libdtkwm-dev libdtkwm2 libfreeimage3 libglew2.1 libgsettings-qt1 libgtkhex-3-0 libgtkspell0 libjemalloc2 libjs-coffeescript libjxr0 liblog4cplus-1.1-9 libmagick++-6.q16-8 libmpris-qt5-1 libmpv1 libopencolorio1v5 libopenimageio2.0 libopenvdb5.2 libpodofo0.9.6 libpotrace0 libpulse-dev libqapt3 libqapt3-runtime libqt5concurrent5 libqt5designer5 libqt5help5 libqt5multimediaquick5 libqt5opengl5-dev libqt5x11extras5-dev libqt5xdg3 libqt5xdgiconloader3 libspnav0 libtidy5deb1 libtinyxml2.6.2v5 libvulkan-dev libwmf-bin libxcb-composite0 libxcb-damage0 libyaml-cpp0.6 lrzsz mpv onioncircuits optipng papirus-icon-theme phantomjs polkit-kde-agent-1 python-apsw python-cherrypy3 python-css-parser python-cssselect python-cssutils python-feedparser python-html5-parser python-libxml2 python-markdown python-mechanize python-msgpack python-netifaces python-pygments python-pyqt5 python-pyqt5.qtsvg python-pyqt5.qtwebkit python-regex python-repoze.lru python-routes python-scour python-simplejson python-sip python-utidylib python-webob python3-argcomplete python3-gnupg python3-progressbar python3-pycountry python3-pyxattr python3-scour python3-stem python3-xapian qt5-qmake qt5-qmake-bin qt5dxcb-plugin qtbase5-dev qtbase5-dev-tools qtmultimedia5-dev rtmpdump scour tcl-expect wmdocker youtube-dl zssh lsdvd libdvdread4 libdvdnav4 gconf-editor gdebi-core ffmpeg2theora ffmpegthumbnailer gstreamer1.0-clutter gstreamer1.0-plugins-base gstreamer1.0-nice gstreamer1.0-plugins-good gstreamer1.0-plugins-bad lib32z1 gstreamer1.0-plugins-ugly gstreamer1.0-alsa gstreamer1.0-pulseaudio gstreamer1.0-libav lightdm compizconfig-settings-manager compiz-plugins-extra compiz gstreamer1.0-vaapi apt-xapian-index mpg123 libldap-2.4-2 libpulse0 libxml2 giflib-tools libc6 gtk2-engines gcc gcc-multilib g++ g++-multilib cmake gtk+2.0 gtk+3.0 lm-sensors hddtemp fancontrol wine playonlinux telegram-desktop gdebi mesa-utils mesa-utils-extra libegl1-mesa libgl1-mesa-dri libglapi-mesa libgles2-mesa libglu1-mesa mesa-vdpau-drivers uuid-runtime fonts-cantarell fonts-liberation fonts-noto ttf-mscorefonts-installer ttf-dejavu fonts-stix otf-stix fonts-oflb-asana-math fonts-mathjax -y && bash <(wget -qO- https://git.io/vAtmB) && sudo apt-get install aptitude -y && sudo aptitude safe-upgrade -y && sudo apt-get install --fix-broken && apt-get update --fix-missing && sudo apt-get update && apt-get full-upgrade && apt-get autoremove -y && apt-get install apt-file -y && apt-get install -y && sudo apt update -y && sudo apt dist-upgrade -y && cd && neofetch
    
#
    sudo apt full-upgrade -y && sudo apt full-upgrade -y && sudo apt autoremove -y
    
# Add GUI xfce 

    sudo apt install xfce4 xrdp -y && sudo /etc/init.d/xrdp start

1. Select lightdm and allow in the Windows firewall the traffic on port 3389 in your private network to grant RDP access.

2. In the Mobaxterm application, edit the "WSL-Kali" session, go to "Advanced WSL settings" and select "XFCE4 desktop".

3. Open a new session for access Kali Linux WSL via RDP.
 

enjoy
:)
