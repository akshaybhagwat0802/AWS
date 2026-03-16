## Setup backend for project
### 1) Clone the github repository into the terminal 
```bash
git clone "github url "
```
### 2) update the terminal and install the jdk
```bash
sudo apt update &&
sudo apt install openjdk-21-jdk -y
```
### 3) install the maven into the terminal 
```bash
sudo apt install maven -y
```
### 4) change the directory to the backend 
```bash
cd project-student-app-updated &&
cd backend
```
### 5) open application.properties file and paste the rds endpoint into that file and also database name and password.
```bash
vim src/main/resources/application.properties
```
### 6) clean the maven package 
```bash
mvn clean package
```
### 7) change the directory to the frontend 
```bash
cd ../frontend/
```
##
