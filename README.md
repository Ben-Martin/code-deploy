

# EC2 setup
yum update -y
curl --silent --location https://rpm.nodesource.com/setup_6.x | bash -
yum -y install nodejs
mkdir /var/www
npm install pm2 -g

# optional
yum install git -y