# Kubernetes_projects
# its in testing ...


<!-- ssh-keygen -t rsa -b 4096 -C "g2k2@live.com"


eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_rsa

ssh -T git@github.com -->

<!-- https://github.com/janushanth/Kubernetes_projects.git -->

<!-- Java

sudo apt update
sudo apt install fontconfig openjdk-17-jre
java -version
 -->

<!-- jenkins

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
 sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins 

 sudo cat /var/lib/jenkins/secrets/initialAdminPassword 


-->


<!-- 
# Add Docker's official GPG key:
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc

# Add the repository to Apt sources:
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update





 sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin


 sudo docker run hello-world 
 sudo usermod -aG docker jenkins
 
 -->

<!-- 
 groovy

 sudo apt update
sudo apt install groovy -->


<!-- java -version

export JAVA_HOME=/usr/lib/jvm/default-java

sudo nano /etc/environment


JAVA_HOME="/usr/lib/jvm/default-java"


source /etc/environment


java -version
groovy -version


sudo systemctl restart jenkins -->



<!-- #!/bin/bash

# Define your Docker Hub credentials and repository details
DOCKER_USERNAME="g2k2@live.com"
DOCKER_PASSWORD="123@Intel"
DOCKER_IMAGE_NAME="my-docker-app"
DOCKER_OWNER="gobikrishnan"

# Set the Docker tag using the current date and time
DOCKER_TAG=$(date "+%Y%m%d%H%M%S")

# Log in to Docker Hub
echo $DOCKER_PASSWORD | docker login -u $DOCKER_USERNAME --password-stdin > /dev/null 2>&1

# Navigate to the directory containing the Dockerfile
cd /var/lib/jenkins/workspace/01_myproject/01_Project/source

# Build the Docker image
docker build -t $DOCKER_OWNER/$DOCKER_IMAGE_NAME:$DOCKER_TAG .

# Push the Docker image to Docker Hub
docker push $DOCKER_OWNER/$DOCKER_IMAGE_NAME:$DOCKER_TAG -->
