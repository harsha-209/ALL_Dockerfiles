# ALL_Dockerfiles


we have multiple Language Dockerfile 


1 . maven based java language dockerfile to deploy in tomcat

here need to understant to deploy tomcat on webapps folder 

2. for python based dockerfile we have to observer that requirment.txt file , in this requirement file hava all dependency so we have to install with pip command 


3. for nodejs or npm based docker file , we have to observe that package.json file. in the package.json file we have to all dependencies in this file , so we have to install through npm i to install all package in this package.json file

outputs of some languages and its deployments


(https://user-images.githubusercontent.com/51083187/122209775-88db9000-cec2-11eb-83d6-9edcea8c547a.png

S.No
Stack
Dependencies file
Build Tool
WebServer
Binary Directory
Binary Extension

1
Java
pom.xml
Maven/Gradle
Tomcat
target
.war/.jar

2
Angular
package.json
Angular CLI/ng
Nginx/Apache
dist
.html/.js/.css etc

3
React
package.json
react-scripts/webpack
Nginx/Apache
build
.html/.js/.css etc
