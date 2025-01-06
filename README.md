# Deployment-of-Django-app-with-Nginx-and-Mysql

![image](https://github.com/user-attachments/assets/9dc3d3a2-576a-4457-ae5e-919863d2efec)


# Step 1
First install docker and docker-compose in your system
```bash
apt update
apt install docker.io -y
apt install docker-compose -y
docker -v
docker-compose --version
```

# step 2
Git clone the code in your local system
```bash
git clone https://github.com/muhammadaliazhar/Deployment-of-Django-app-with-Nginx-and-Mysql.git
```

Step 3
Move inside the project folder and run the application using docker compose
```bash
cd project-folder
docker-compose up -d
```

Step 4 
check that 3 containers are running in your system
```bash
docker ps
```

Step 5
Allow port # 8000 in your security group rule/ firewall and access application using your public ip address




















