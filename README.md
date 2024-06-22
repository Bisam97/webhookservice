# WebhookService V1.0.0 Pre

## Installing 

### Debian Based distros
  Download the .deb package for Debian or Ubuntu and install it.

  Debian
    
    sudo apt install ./webhookservice_1.0.0-1_all.deb 
  Ubuntu
  
    sudo apt install ./webhookservice_1.0.0-0ubuntu1_all.deb 

### Other distros

  Download gmabas3 for your distro and install it and then download the tar.gz file 

    tar xzf webhookservice-1.0.0.tar.gz
    cd webhookservice-1.0.0/
    ./configure
    make
    make install

  If you have systemd

    cp webhookservice/.hidden/webhook.service /etc/systemd/system/
