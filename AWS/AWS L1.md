## After Setting up the server open Terminal and create a folder and put the pem file in it

#### 1 .Give ssh key permissions
`chmod 700 kirat-class.pem`
#### 2 .ssh(Secure Shell)  into machine 
`ssh -i name-password.pem ubuntu@ec2-65-0-180-32.ap-south-1.compute.amazonaws.com`
#### 3. Clone repo or copy code and paste in the folder
##### If any error occur https://www.tecmint.com/resolve-temporary-failure-in-name-resolution/
#### 4. Install Node.js (run the second cmd that contains bash)

[https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04]
#### 4. Install all dependencies
```
cd sum-server
npm install
```
#### 5. Start the back-end 
```
node index.js
```
#### 6. Now hit the public IP from AWS



### To ping a website to a particular IP run in terminal and add IP and website
```
sudo vi /etc/hosts
```
### And then verify by using this (this will give you to which IP website is pointing)
```
ping google.com
```

