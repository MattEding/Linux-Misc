Arduino
-------
wget https://downloads.arduino.cc/arduino-1.8.13-linux64.tar.xz  
tar -xvf arduino-1.8.13-linux64.tar.xz  
	(-x extract; -v verbose; -f files)  
cd arduino-1.8.13/  
sudo ./install.sh  

Nord VPN
--------
https://support.nordvpn.com/Connectivity/Linux/1325531132/Installing-and-using-NordVPN-on-Debian-Ubuntu-Raspberry-Pi-Elementary-OS-and-Linux-Mint.htm  
sudo apt-get install curl  
sh <(curl -sSf https://downloads.nordcdn.com/apps/linux/install.sh)  
sudo nordvpn connect Canada Toronto  
	(-s silent; -S show error; -f fail)  

Libre Office
------------
sudo apt-get remove --purge libreoffice*  
sudo apt-get clean  
sudo apt-get autoremove  

Anti-Virus
----------
https://help.ubuntu.com/community/ClamAV  
sudo apt install clamtk  
	(gui version)  

	
CMake
-----
sudo apt-get install cmake  
sudo apt-get install cmake-qt-gui  

Qt
--
https://stackoverflow.com/questions/48147356/install-qt-on-ubuntu  
sudo apt-get install build-essential  
sudo apt install qtcreator  
sudo apt-get install qt5-default  

Fira-Code
---------
https://github.com/tonsky/FiraCode/wiki/Installing  
sudo apt install fonts-firacode  

Mamba
-----
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh  
bash ./Miniconda3-latest-Linux-x86_64.sh  
conda install mamba -c conda-forge  

Wemos D1 Mini
-------------
https://learn.sparkfun.com/tutorials/how-to-install-ch340-drivers/all  
https://www.wemos.cc/en/latest/d1/d1_mini.html  
https://github.com/esp8266/Arduino  

Angry IP Scanner
----------------
sudo apt-get install openjdk-14-jre  
sudo apt install openjdk-14-jre-headless  
wget https://github.com/angryip/ipscan/releases/download/3.7.5/ipscan_3.7.5_amd64.deb  
sudo dpkg -i ipscan_3.7.5_amd64.deb  

Hyper
-----
wget https://github.com/vercel/hyper/releases/download/3.0.2/hyper_3.0.2_amd64.deb  
sudo dpkg -i hyper_3.0.2_amd64.deb  
hyper install hyper-drop-file  
hyper install hyper-opacity  
	(not working on Linux for the moment)  
hyper install hypercwd  
hyper install hyper-highlight-active-pane  
hyper-font-ligatures  
	(webGLRenderer: false; fontFamily: '"Fira Code", Menlo, ...,)  

VS Code
----
https://code.visualstudio.com/docs/setup/linux  
sudo dpkg -i code_1.53.2-1613044664_amd64.deb  
