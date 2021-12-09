# CI_CD_Jenkins
##  Commands that we are going to use in the Jenkins Project
### Installation of Jenkins
```sh
sudo apt-get update
```
- Check Java Exist or Not
```sh
java
```
- Location of Java
```sh
which java
```
- Check java Version
```sh
java --version
```
- Install command of Jenkins using wget
```sh
wget https://get.jenkins.io/war-stable/2.263.2/jenkins.war 
```
- Start Jenkins Server
```sh
java -jar jenkins.war
```
**By default Jenkins server uses port 8080 on the local system.**
- Use the following link in the browser after start the Jenkins Server
```sh
http://localhost:8080
```
Now after installing the Jenkins and start the server we want the one time password in the Server UI for the admin accout.
```sh
cat < ~/.jenkins/secrets/initialAdminPassword
```
> With the help of this Password you can unlock jenkins.
-
> After unlock jenkins we are creating the first admin user in jenkins Server.

## Steps to create a Project in jenkins
![Jenkins Main Window]()
1. Click on New Item
![Jenkins Project Window]()
2. Enter the Project Name in the **Enter a item Name.**
3. Then Select FreeStyle Project.
4. Then Click on Ok.
5. 


