# gcp-ace
Files and Scripts to GCP ACE

# Startup Scripts

## For Asia

#! /bin/bash

sudo apt-get update
sudo apt-get --assume-yes install wget
sudo apt-get --assume-yes install python3 python3-dev python3-venv
sudo wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py

sudo wget https://raw.githubusercontent.com/MarcelloTinoco/gcp-ace/main/ws-asia.py
sudo python3 ws-asia.py


============================================================

## For Europe

#! /bin/bash

sudo apt-get update
sudo apt-get --assume-yes install wget
sudo apt-get --assume-yes install python3 python3-dev python3-venv
sudo wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
sudo wget https://raw.githubusercontent.com/MarcelloTinoco/gcp-ace/main/ws-europe.py
sudo python3 ws-europe.py

============================================================

## For USA

#! /bin/bash

sudo apt-get update
sudo apt-get --assume-yes install wget
sudo apt-get --assume-yes install python3 python3-dev python3-venv
sudo wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
sudo wget https://raw.githubusercontent.com/MarcelloTinoco/gcp-ace/main/ws-us.py
sudo python3 ws-us.py

============================================================
