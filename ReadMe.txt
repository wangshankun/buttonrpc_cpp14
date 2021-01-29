
Ubuntu:
sudo apt install libzmq3-dev
=================================
Centos:
sudo yum install -y epel-release
sudo yum install -y zeromq-devel


g++ main_server.cpp  -lzmq -I./ -o server
g++ main_client.cpp  -lzmq -I./ -o client


