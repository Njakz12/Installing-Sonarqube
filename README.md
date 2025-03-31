


![image](https://github.com/user-attachments/assets/5110c26f-225a-4b10-9985-20d21db4099d)






# Sonarqube
## Create user sonarqube user in the root user interactive 

Make java is installed

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

