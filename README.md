# Zomato-Clone
steps to configure 

Create Jenkins server along with Sonarqube using the below repo

(https://github.com/Eshwardvp/Terraform-EC2-Jenkins.git)


Login to the Jenkins server

Install required plugins

Eclipse Temurin installer
sonarqube scanner
nodejs
OWASP Dependency-Check
docker


To integrate 

Go to Tools

Add JDK 
JDK17 & select from adoptium.net & SELECT JDK17.0.8.1+1

SonarQube scanner
select latest version

Nodejs
nodejs16.2.0

Dependency-Check installations 
install from github.com

Docker installations

apply & save

---------------
To Integrate with sonarqube

we will have to generate sonarqube token and add it to Jenkins (Manage Creds)

Inegrate sonarqube with jenkins

manage jenkins -----> system -----> SonarQube servers ---> add SonarQube servers ---> http://13.127.96.191:9000 & select token

Integrate with Docker

go to creds ---> add docker creds

