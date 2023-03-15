# gala

<code>
wget https://links.gala.com/DownloadLinuxNode

sudo tar xvf DownloadLinuxNode 
# Run install script (as root)

sed -i 's/ge 10/ge 0/g' ./gala-node/install.sh
sed -i 's/ge 12/ge 0/g' ./gala-node/install.sh

sudo ./gala-node/install.sh -y

# Add API key
sudo gala-node config api-key V7TIf/hb6cRCcYX1y6eCWDD3cOn/fkslBaRZ5eEwnbo=

# Shows the list of workloads you can run
sudo  gala-node licenses

# Config the workloads you want to run
sudo  gala-node workload add founders
sudo gala-node workload add townstar
sudo gala-node workload add player
...

# Start Gala Node
sudo  gala-node start
sudo  gala-node status

</code>
