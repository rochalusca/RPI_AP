[EN] ## RPI-Wireless-Hotspot
This script configures your Raspberry Pi 3 model B+ with a IP fixed and as a Access Point.

<b><font size="4"> <strong> Features:<b/><font/>

* Configured Access Point starts automatically on boot, no extra configuration necessary;
* Configured WiFi network (wlan0) is WPA encrypted;
* Default SSID "RaspberryPi_AP" and WPA key "intit1234" can be modified during install;
* Configured Wifi network will operate as Access Point on IP 192.168.0.1;
* Once set up, the wired network (eth0) will still operate as fixed IP 192.168.1.10;

* Use the Uninstall script to return the configuration as normal.

<b><font size="4">Requirements:<b/><font/>

* A Raspberry Pi 3 model B+ running raspbian;
* An active ethernet connection.

<b><font size="4">Installation:<b/><font/>

1. In the terminal, run:
    sudo git clone https://github.com/rochalusca/RPI_AP.git

2. Navigate to folder, and execute
    sudo ./install

3. Confirm that you agree with the changes to be made;

<b><font size="4">Uninstalling:<b/><font/>

* Navigate to folder, and execute
    sudo ./uninstall
<hr/>
<b><font size="4"> Notes and configuration:

* This setup has been tested on a fresh and new install of raspbian;
* If set up on an existing install then any current config files will be backed up with the extension ".old";
* if necessary returning to original network settings Uninstalling the package;

* Usually you can find the folder Navigate in the terminal like this:
<hr/><hr/>

[BR]<b><font size="5">RPI-Wireless-Hotspot<b/><font/>
<hr/>
Este script configura seu Raspberry Pi 3 modelo B + com um IP fixo e como um Access Point.

<b><font size="4">Características:<b/><font/>

* O Access Point configurado inicia automaticamente na inicialização, sem necessidade de configuração extra;
* Rede Wi-Fi configurada (wlan0) é criptografada por WPA;
* O SSID padrão "RaspberryPi_AP" e a chave WPA "intit1234" podem ser modificados durante a instalação;
* A rede Wi-Fi configurada operará como ponto de acesso no IP 192.168.0.1;
* Uma vez configurada, a rede com fio (eth0) ainda funcionará como IP fixo 192.168.1.10;
 
* Use o script de desinstalação para retornar a configuração normalmente.

<b><font size="4">Requisitos:<b/><font/>

* Um Raspberry Pi 3 modelo B + rodando raspbian;
* Uma conexão Ethernet ativa.

<b><font size="4">Instalação:<b/><font/>

1. No terminal, execute:
     sudo git clone https://github.com/rochalusca/RPI_AP.git
    
2. Navegue até a pasta e execute
     sudo ./install

3. Confirme que você concorda com as alterações a serem feitas;

<b><font size="4">Desinstalando:<b/><font/>

* Navegue até a pasta e execute
     sudo ./uninstall
<hr/>
<b><font size="4">Notas e configuração:<b/><font/>

* Esta configuração foi testada em uma nova e nova instalação de raspbian;
* Se configurado em uma instalação existente, será feito backup de todos os arquivos de configuração atuais com a extensão ".old";
* se necessário, retornando às configurações originais da rede Desinstalando o pacote;

* Normalmente você pode encontrar a pasta Navegar no terminal assim:
