This is my personal repo to learn microservices , devops

commands

**To create image using google jib**
-> mvn compile jib:dockerBuild

**To run in docker container**
-> docker run -p 9000:9000 singhcse01/cards:1.0

**To run mysql as a docker container on local**
-> docker run -p 3306:3306 --name accountsdb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=accountsdb -d mysql 