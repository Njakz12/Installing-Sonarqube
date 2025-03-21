# Sonarqube
## Create user sonarqube user in the root user interactive 

Install sonarqube using the root user

After installing sonarqube do this 

mv sonarqube-10.4.1.88267.zip /opt/

cd /opt/

unzip sonarqube-10.4.1.88267.zip

adduser sonaradmin

chown -R sonaradmin:sonaradmin sonarqube-10.4.1.88267

cd sonarqube-10.4.1.88267/

cd bin/    

cd linux-x86-64

su sonaradmin

./sonar.sh

./sonar.sh start

./sonar.sh status

netstat -ntlp 

Sonarqube is running in 9000

