Bootstrap: docker
From: debian:stretch

%post
    apt-get -y update
    apt-get -y install curl python3-dateutil
    curl https://raw.githubusercontent.com/saulpw/deb-vd/master/pool/main/v/visidata/visidata_1.5-1_all.deb -o visidata_1.5-1_all.deb
    dpkg -i visidata_1.5-1_all.deb

%runscript
    vd