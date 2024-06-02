https://github.com/Jishu15/MCKV_aws.git
#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone https://github.com/Md-Ariyan/mdariyan328.git
cd mdariyan328
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
sh infi.sh

hosting website in ec2
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install nginx
nginx -v
cd /var/www/
sudo chmod 777 html

github file upload
git init
dir
git add .
git status
git commit -m “done”
git remote add origin <the_repository_path_name>
git push -u origin master

git init/git clone <Repository_Path>
