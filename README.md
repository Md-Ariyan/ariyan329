#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone http://github.com/sudip7407/Repo1.git
cd Repo1
npm install
node index.js
#ass-11
sudo nano infi.sh
#!/bin/bash
while(true)
do
echo "Inside Loop"
done
control+x ,y,enter
sudo chmod 777 infi.sh
