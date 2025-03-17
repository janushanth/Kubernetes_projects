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
openjdk version "17.0.13" 2024-10-15
OpenJDK Runtime Environment (build 17.0.13+11-Debian-2)
OpenJDK 64-Bit Server VM (build 17.0.13+11-Debian-2, mixed mode, sharing) -->

<!-- jenkins

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins -->

<!-- sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins -->
<!-- sudo cat /var/lib/jenkins/secrets/initialAdminPassword -->


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



