## 🧠 AWS Cloud Infrastructure Design

As part of my cloud computing coursework, I designed and implemented a complete **cloud infrastructure on AWS** for a simulated company, **Karite Pte Ltd**. The goal was to create a scalable and secure network architecture that supports both public and private services.

#### 🧩 Key Components
- **Virtual Private Cloud (VPC)** with multiple subnets across **two availability zones**
- **Public & Private Subnets** for secure resource segmentation
- **EC2 Instances** deployed for:
  - Web Server (HTTPd)
  - NAT Instance (with Source/Destination check disabled)
  - Database Server
- **Internet Gateway & Route Tables** setup for traffic routing
- **Security Groups** configured with specific rules for HTTP, SSH, ICMP, and MySQL
- **IAM Users & Groups** setup with necessary policies
- **Route 53 DNS Configuration** linking a custom domain to the deployed web server

#### 🌐 Outcome
Deployed a functioning multi-tier cloud infrastructure with:
- Proper **routing & NAT translation**
- A web server displaying a custom landing page
- DNS pointing to a public IPv4 web service via **Route 53**

> *This project demonstrates my understanding of cloud fundamentals, networking, and AWS ecosystem management using real-world architecture practices.*

---
