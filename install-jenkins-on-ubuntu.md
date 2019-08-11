# install jenkins on Ubuntu

wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -

sudo sh -c "echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list"

sudo apt install -y jenkins

sudo systemctl start jenkins.service

sudo systemctl enable jenkins.service

ps aux | grep jenkins