# 🚀 My First DevOps Project: Deploy Static Website on AWS EC2

## 📌 Project Overview
This is my first DevOps project where I deployed a simple static HTML website on an AWS EC2 instance using Git and Nginx.

The goal of this project is to understand:
- Git basics (init, commit, push, pull)
- Deploying an application on a cloud server
- Working with AWS EC2
- Using Nginx as a web server

---

## 🧰 Technologies Used
- Git & GitHub
- AWS EC2 (Ubuntu Server)
- Nginx Web Server
- HTML

---

## 🏗️ Project Architecture
User → GitHub → EC2 Instance → Nginx → HTML Website


## ⚙️ Steps to Run This Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Create AWS EC2 Instance
Launch Ubuntu EC2 instance
Open ports:
22 (SSH)
80 (HTTP)

3️⃣ Connect to EC2
ssh -i your-key.pem ubuntu@your-ec2-public-ip

4️⃣ Install required packages
sudo apt update
sudo apt install nginx git -y

5️⃣ Clone project inside EC2
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

6️⃣ Deploy website
sudo cp index.html /usr/share/nginx/html/index.html

7️⃣ Access the website
http://your-ec2-public-ip



🎯 Learning Outcomes

By completing this project, I learned:

How to use Git & GitHub for version control
How to deploy a website on a cloud server
Basic Linux server management
How web servers (Nginx) work


👨‍💻 Author
Name: Muhammed_Reda
Role: Junior DevOps Engineer (Learning Phase)