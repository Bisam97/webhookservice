# WebhookService V1.0.0 Pre

## Installing 

  !! For All Distros !!
  
  Add User webhooklog

    
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

## Features

 This programm can:
 
   * Gen Unique ID  to identify the Requester
   * CLI Webhook add / Edit dialog
   * Activate / Deactivate Webhooks
   * can Run as Systemd Service
   * Only Support HTTP but with NGINX Reverse Proxy is HTTPS also Supported
   * logging and sort Logs at the next Day in /var/log/webhook/archive/YYYY/MM/DDMMYYYY.log (1.1.2024 is 112024.log)

ToDo:
  * Better Logging
  * Block Portscaner with fake response
  * FixBugs
