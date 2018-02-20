
```
curl -s https://raw.githubusercontent.com/realm/realm-object-server/master/install.sh | bash

export NVM_DIR="/home/ec2-user/.nvm"
. "/home/ec2-user/.nvm/nvm.sh"
    
ros init FAST-ROS-Production

cd FAST-ROS-Production/

npm start

npm install realm-object-server-cognito-auth

rm -r node_modules/

npm install

npm install realm-object-server-cognito-auth

vi /home/ec2-user/FAST-ROS-Production/start.sh

sudo vi /usr/lib/systemd/system/ros.service

sudo systemctl daemon-reload

sudo systemctl start ros

sudo systemctl status ros

sudo systemctl stop ros
```
