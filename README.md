# prestashop-aws-deployment



\# PrestaShop AWS Cloud Infrastructure Deployment



A production-ready e-commerce deployment of \*\*PrestaShop\*\* hosted on \*\*AWS\*\*, utilizing an Ubuntu Linux web tier, an Apache web server, PHP 8.3, and a managed Amazon RDS MySQL database backend.



\##  Architecture Stack

\* \*\*Cloud Provider:\*\* Amazon Web Services (AWS Free Tier)

\* \*\*Compute / Web Tier:\*\* Amazon EC2 running \*\*Ubuntu Server 24.04 LTS\*\*

\* \*\*Web Server:\*\* Apache2

\* \*\*Application Language:\*\* PHP 8.3

\* \*\*Database Tier:\*\* Amazon RDS \*\*MySQL 8.0\*\*



\---



\## 📂 Project Structure

📸 Deployment & Configuration Screenshots
Here are visual logs capturing key phases of the deployment, configuration, and database connection setup:

Environment Setup:

PrestaShop Installation & System Configuration:

prestashop-aws-deployment/

├── README.md

└── assets/

&#x20;   ├── Screenshot\_1.png

&#x20;   ├── Screenshot\_2.png

&#x20;   ├── Screenshot\_3.png

&#x20;   ├── Screenshot\_4.png

&#x20;   ├── Screenshot\_5.png

&#x20;   ├── Screenshot\_6.png

&#x20;   ├── Screenshot\_7.png

&#x20;   ├── Screenshot\_8.png

&#x20;   └── Screenshot\_9.png

Deployment Steps Overview
EC2 Provisioning: Launched an Ubuntu Server 24.04 LTS instance on AWS with configured security groups for HTTP, HTTPS, and SSH traffic.

Database Provisioning: Deployed a secure, managed MySQL 8.0 instance via Amazon RDS and established network connectivity rules from the web server.

Software Stack Installation: Installed and configured Apache2 and PHP 8.3 on the EC2 instance.

PrestaShop Installation: Downloaded and configured PrestaShop, linking it successfully to the Amazon RDS MySQL backend database.
