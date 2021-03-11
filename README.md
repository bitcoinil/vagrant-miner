# Vagrant-Miner

This miner is based on vagrant image (.box file) of Ubuntu 20.x, 

installed with all the prerequsites required for mining the new BTCIL (=BitCoinIL) coin.

Built with Vagrant 2.2.14 on Windows 10.

Contains: BTCIL wallet, BTCIL daemon + tools, cpu miner? TBD


# Installation instructions
- install latest Vagrant software for windows 10
- download the box file from the following link (Google Drive): 
  https://drive.google.com/u/0/uc?id=1zag2aErrkreE-0Nkg1HqOh11IL3z-W4-&export=download

- run: 

vagrant init <box file path>
  
vagrant up
  
- login details: 

IP: 127.0.0.1

Port: 2222

user: root 

pass: vagrant


All the BTCIL tools are in /root/release

Feel free to update the box file with your changes (such as CPU miner, scripts for easy running, etc.), 
using the vagrant package command - https://www.vagrantup.com/docs/cli/package
and uploading the box file for others to download !
Godspeed !



  





