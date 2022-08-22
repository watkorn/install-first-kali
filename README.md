# install-first-kali 2022.8  
usr/pass : kali/kali  
sudo apt update  
sudo apt upgrade  

#chrome install  
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb  
sudo apt install gdebi-core  
sudo gdebi google-chrome-stable_current_amd64.deb  
#set chrome to default  
sudo update-alternatives --config x-www-browser  

#vol3 #python  
cd Desktop/  
git clone https://github.com/volatilityfoundation/volatility3.git  
cd volatility3  
pip3 install -r requirements-minimal.txt  
python3 setup.py build  
sudo python3 setup.py install  
sudo apt-get install libsnappy-dev  
pip3 install -r requirements.txt  
python vol.py -h  

#set openvpn of tryhackme  
![vpn](vpn,png)  
