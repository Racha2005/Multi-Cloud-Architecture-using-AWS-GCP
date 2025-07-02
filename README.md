🌐 Multi-Cloud Architecture using AWS & GCP
This project demonstrates a basic multi-cloud setup where a web server hosted on AWS EC2 links to another web server hosted on GCP Compute Engine, and vice versa.
➡️ The goal is to simulate cross-cloud communication between two different platforms.

🔧 Tools & Services Used
☁️ Amazon EC2 (AWS)
☁️ Google Compute Engine (GCP)
🖥️ Apache2 Web Server
🐧 Linux (Amazon Linux 2 & Ubuntu)
📝 HTML + CSS Styling
🔐 SSH Access & Security Groups

🚀 Instance Details
✅ AWS EC2 Instance
🔑 Key Pair: keypair-333.pem
🌐 Public IP: 13.127.202.236
🖼️ Background Image:
https://wallpapers.com/images/hd/solid-light-purple-1517-x-853-rsorkyq9fivrbpam.jpg
📝 Heading: AWS Web Server - Multi-Cloud Architecture
🔗 Link: Visit GCP Server

✅ GCP Compute Engine Instance
🌐 Public IP: 34.47.147.194
🖼️ Background Image:
https://media.istockphoto.com/id/1308016132/vector/a-horizontal-empty-bright-radiant-fluorescent-neon-green-coloured-backgrounds.jpg
📝 Heading: GCP Web Server - Multi-Cloud Architecture
🔗 Link: Visit AWS Server

🔁 Cross-Linking Architecture
➡️ AWS Page links to GCP Server:
🔗 http://34.47.147.194

➡️ GCP Page links to AWS Server:
🔗 http://13.127.202.236

💡 This cross-connection simulates real-world multi-cloud architecture between cloud providers.

📚 Key Takeaways
🔹 Provisioned virtual machines on AWS EC2 and GCP Compute Engine
🔹 Installed and configured Apache2 web servers
🔹 Handled firewalls, SSH access, and security groups
🔹 Created and styled custom HTML landing pages
🔹 Linked both web pages to simulate real-time cross-platform routing

🔗 Live Demo Links
🌐 AWS Web Server → http://13.127.202.236
🌐 GCP Web Server → http://34.47.147.194

⚙️ Setup Instructions
🔸 Step 1: Update & Install Apache

sudo apt update
sudo apt install apache2 -y

🔸 Step 2: Add index.html Content

sudo nano /var/www/html/index.html
➡️ Paste the respective HTML content (AWS or GCP version)

🔸 Step 3: Restart Apache Server

sudo systemctl restart apache2

🔸 Step 4: Test in Browser
➡️ Visit public IPs:

🟣 AWS: http://13.127.202.236

🟢 GCP: http://34.47.147.194

💡 Collapsible Setup Guide for README
<details> <summary>📋 Setup Commands (Click to Expand)</summary>

sudo apt update  
sudo apt install apache2 -y  
sudo nano /var/www/html/index.html  
sudo systemctl restart apache2  
</details>
