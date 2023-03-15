# gala

<code>
wget https://links.gala.com/DownloadLinuxNode

sudo tar xvf DownloadLinuxNode 


sed -i 's/ge 10/ge 0/g' ./gala-node/install.sh
sed -i 's/ge 12/ge 0/g' ./gala-node/install.sh

sudo ./gala-node/install.sh -y


sudo gala-node config api-key V7TIf/hb6cRCcYX1y6eCWDD3cOn/fkslBaRZ5eEwnbo=

sudo  gala-node licenses


sudo  gala-node workload add founders
sudo gala-node workload add townstar
sudo gala-node workload add player


sudo  gala-node start
sudo  gala-node status

</code>
