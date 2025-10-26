# Django Blog Deployment on AWS ☁️

This project demonstrates a **production-grade Django web application** deployed on **AWS** using:
- **EC2** for hosting (Ubuntu, Nginx, Gunicorn)
- **RDS (MySQL)** for database
- **Route 53** + **GoDaddy** for DNS
- **Let’s Encrypt** for SSL/HTTPS

---
### 🔧 Tech Stack
- Django 5.2.7
- Gunicorn
- Nginx
- Amazon EC2 & RDS
- Certbot (SSL)
- Route 53 + GoDaddy DNS

---
### 🧩 Architecture Overview
User → Route 53 → EC2 (Nginx + Gunicorn + Django) → RDS (MySQL)

![AWS Django Architecture](architecture/aws_django_architecture.png)

---
### 🧑‍💻 Author
**Sahil**  
IT Administrator | AWS & Cloud Enthusiast  
[LinkedIn](https://linkedin.com/in/) | [GitHub](https://github.com/)
