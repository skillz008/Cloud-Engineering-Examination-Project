# The Future of Smart Learning Platforms

A dynamic prototype hosted on AWS showcasing a cloud-native landing page.

## 🛠️ Stack
- AWS EC2 (Ubuntu 22.04)
- Nginx (Reverse Proxy)
- Tailwind CSS (Styling)
- Let’s Encrypt (HTTPS - optional)

## 🌐 Live Demo
http://44.203.114.63  
(Or your domain if configured)

## 📸 Screenshot
![Screenshot](screenshot.png)

## ✅ Setup Steps

### 1. EC2 Provisioning
- Ubuntu 22.04 on AWS EC2 (t2.micro)
- Open ports: 22, 80, 443

### 2. Web App Setup
- Installed Node.js
- Created basic Node.js server

### 3. Nginx as Reverse Proxy
- Configured to proxy traffic from port 80 to Node.js app on port 3000

### 4. SSL (Optional)
- Installed Certbot
- Enabled HTTPS with Let’s Encrypt

### 5. Final View
Dynamic content with name, project pitch, and biography styled using TailwindCSS.

## Author
**Joshua**  
Cloud Engineer  
