# EC2 HTML Mini Project

A simple static HTML website hosted using Apache on an AWS EC2 instance running Amazon Linux 2023.

## 🚀 Features

- Hosted on Amazon EC2
- Apache Web Server (httpd)
- Custom HTML Page (`index.html`)
- Publicly accessible over HTTP

## 📁 File Structure
project-folder/
├── index.html
└── README.md

## 🌐 Live Demo

http://16.171.155.12/

## 🛠️ Technologies Used

- Amazon EC2
- Apache (httpd)
- Amazon Linux 2023
- HTML5

## 🧰 Setup Instructions

1. Launch an EC2 instance using Amazon Linux 2023.
2. Install Apache:
   ```bash
   sudo dnf install -y httpd
   sudo systemctl start httpd
   sudo systemctl enable httpd
Create your HTML page in /var/www/html/index.html

Open port 80 in EC2 Security Group for public access.

Author

Jamal Zouhaoui

📄 License

MIT License
