# Product
jv

#Install
sudo yum install docker
 
#Docker 서비스 실행
sudo service docker start
 
#부팅시 자동 실행 설정
sudo chkconfig docker on

sudo wget -q0 https://get.docker.com/ | sh
sudo docker rm 'sudo docker ps -ap'
sudo docker rmi hello-world
