### 1) change the drectory to frontend
```bash
cd frontend
```
### 2) update the terminal and install nodejs and npm
```bash
 sudo apt update &&
sudo apt install nodejs npm -y
```
### 3) install npm and fix the audit
```bash
npm install &&
npm audit &&
npm audit fix
```
### 4) open userservices.js by using following path and open with vim editor and add the ec2 instance public ip into file .
```bash
vim src/api/UserServices.js
```
### 5) start the npm
```bash
npm start
```
### 6) Run the npm 
```bash
npm run build
```
### 7) change the directory to backend 
```bash
cd ../backend/
```
### 8) create a jar file into backend file 
```bash
java -jar target/student-registration-backend-0.0.1-SNAPSHOT.JAR
```
### 9) copy the instance public ip and run into search engine and fill details and submit form .
