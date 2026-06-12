<div align="center">

# Hi, I'm Muhammad Kaif Laghari 👋
### Cloud & DevOps Engineer · Systems Performance Researcher · Infrastructure Automation

*Automating cloud delivery pipelines by day, benchmarking ARM SoCs by night.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-kaif-leghari/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://muhammad-kaif-portfolio.onrender.com/)
[![arXiv](https://img.shields.io/badge/arXiv-2509.18929-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.18929)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammadkaifleghari@gmail.com)

</div>

---

## 🧭 About Me

I'm a **Software Engineering graduate (CGPA: 3.49) from SZABIST Hyderabad** specializing in **Cloud Infrastructure, DevOps automation, and Systems Performance**. My work spans the full software delivery lifecycle — from designing secure AWS deployment architectures to publishing first-author quantitative research on ARM SoC thermal constraints.

- 🔭 Currently deepening expertise in **Kubernetes orchestration** and **multi-cloud IaC**
- 📄 Published **first-author research** on Meta Quest 3 / ARM SoC performance at arXiv (paper `2509.18929`)
- 💼 DevOps internship at **CloudLem** — CI/CD automation + secure deployment architecture on AWS

---

## 📄 Research & Publications

<div align="center">

### 📑 First-Author Publication · arXiv:2509.18929

**"Native Mixed Reality Compositing on Meta Quest 3: A Quantitative Feasibility Study of ARM-Based SoCs and Thermal Headroom"**

*Preprint · arXiv · September 2025*

[![Read on arXiv](https://img.shields.io/badge/Read_Paper-arXiv:2509.18929-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.18929)
[![PDF](https://img.shields.io/badge/Download-PDF-blue?style=flat-square&logo=adobeacrobatreader)](https://arxiv.org/pdf/2509.18929)

</div>

> Investigated the feasibility of integrating a native MR compositing pipeline into the **Meta Quest 3** (Snapdragon XR2 Gen 2), enabling first-person MR content creation without external PC infrastructure. Conducted a simulation-based performance study benchmarking thermal headroom and processing constraints against **Snapdragon 8 Gen 3** and **MediaTek Dimensity 9300** under real-time 720p/30fps compositing workloads — using Meta's Passthrough Camera API, Unity Sentis, and FastSAM.

**Key skills demonstrated:**
- 📊 Quantitative benchmarking methodology for edge XR compute workloads
- 🌡️ Thermal throttling analysis and SoC headroom modeling under sustained loads
- 🔬 Hardware-software interface performance profiling on ARM architectures

---

## 🛠️ Tech Stack & Tools

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)
![ALB](https://img.shields.io/badge/ALB-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![CodeDeploy](https://img.shields.io/badge/CodeDeploy-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazon-cloudwatch&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-8C4FFF?style=flat-square&logo=amazon-aws&logoColor=white)

### 🐳 Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![DockerHub](https://img.shields.io/badge/DockerHub-2496ED?style=flat-square&logo=docker&logoColor=white)

### 💻 Languages & Environments
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

### 🔒 QA & Security Testing
![Manual Testing](https://img.shields.io/badge/Manual_Testing-FF4B4B?style=flat-square&logo=checkmarx&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC_Testing-6B21A8?style=flat-square&logo=shield&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 1. 🔄 Automated CI/CD with AWS CodeDeploy & GitHub Actions
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Muhammad-Kaif-leghari/Automated-CI-CD-with-AWS-CodeDeploy-GitHub-Actions)

**Problem:** Manual deployments to AWS EC2 were slow, error-prone, and lacked rollback safety.

**Solution:** Built an end-to-end CI/CD pipeline using **GitHub Actions** and **AWS CodeDeploy** to automate the build, test, and deployment of a containerized **Flask** application. Automated Docker image versioning, stored build artifacts securely in **S3**, and executed zero-downtime deployments to **EC2** environments using strictly enforced IAM policies.

`AWS CodeDeploy` `GitHub Actions` `EC2` `S3` `Docker` `Flask` `Python`

---

### 2. ⚖️ Optimizing Traffic Distribution with AWS ALB
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Muhammad-Kaif-leghari/Optimizing-Traffic-Distribution-AWS-ALB)

**Problem:** Single-instance hosting creates computing bottlenecks, high latency risk, and single points of failure under production workloads.

**Solution:** Implemented **AWS Application Load Balancer (ALB)** to distribute incoming traffic across multiple EC2 instances using targeted routing rules. Improved application availability by ensuring traffic only hits healthy targets and integrated **Auto Scaling policies** to dynamically scale infrastructure metrics based on real-time load demand.

`AWS ALB` `Auto Scaling` `EC2` `High Availability` `Load Balancing`

---

### 3. 🔐 Amazon VPC Network Architecture for Secure EC2 Deployment
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Muhammad-Kaif-leghari/Amazon-VPC-Setup-Public-Subnet-EC2)

**Problem:** Deploying cloud resources directly into default public subnets leaves internal architectures exposed without proper security governance.

**Solution:** Architected a secure, custom **Amazon VPC** infrastructure using optimized CIDR block allocation to establish isolated network foundations. Mapped reliable external connectivity paths via **Internet Gateways** and custom routing tables while hardening compute nodes with strict security group firewall access rules.

`Amazon VPC` `Network Security` `EC2` `Internet Gateway` `Security Groups`

---

### 4. 🛡️ Women's Safety Project (Final Year Project)
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Muhammad-Kaif-leghari/WomenSafetyProject)

**Problem:** Standard safety applications run vulnerably when cellular signals drop or background environments kill live tracking services.

**Solution:** Designed a comprehensive background-resilient mobile architecture incorporating real-time GPS coordinates syncing, automated ambient audio recording intervals, and a native SMS fallback mechanism ensuring emergency communication transmits even without mobile data connectivity.

`Mobile Architecture` `GPS Services` `Background Processing` `Failover Systems` `Python`

---

### 5. 🔍 Manual Testing — RBAC on OrangeHRM
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Muhammad-Kaif-leghari/Manual-Testing-RBAC-OrangeHRM)

**Problem:** Role-Based Access Control implementations in enterprise suites can harbor subtle privilege escalation bugs overlooked by automated vulnerability configurations.

**Solution:** Structured a comprehensive manual testing plan targeted at identifying boundary conflicts, testing session hijacking vectors, and mapping out user privilege matrix exceptions across standard Admin, HR Manager, and ESS profiles.

`Manual Testing` `RBAC` `Security Assurance` `QA Lifecycle` `Test Design`

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Muhammad-Kaif-leghari&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Muhammad-Kaif-leghari&theme=default&hide_border=true" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Muhammad-Kaif-leghari&layout=compact&theme=default&hide_border=true&langs_count=8" height="130"/>

</div>

---

## 🏅 Certifications & Experience

* **DevOps Intern** · CloudLem *(Nov 2025 – Dec 2025)* — Managed automated CI/CD configurations, image distribution architectures via DockerHub, and strict environment secrets compliance.
* **Containers w/ Docker & Kubernetes** · IBM / Coursera *(2025)*
* **AWS Cloud Technical Essentials** · AWS / Coursera *(2025)*

---

## 📬 Let's Connect

I'm open to **DevOps Engineer**, **Cloud Infrastructure**, and **Systems Performance** engineering roles. Let's build something solid.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/muhammad-kaif-leghari/)
[![Email](https://img.shields.io/badge/Email-muhammadkaifleghari@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:muhammadkaifleghari@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=flat-square&logo=github)](https://muhammad-kaif-portfolio.onrender.com/)

---

<div align="center">
<sub>Profile views: <img src="https://komarev.com/ghpvc/?username=Muhammad-Kaif-leghari&style=flat-square&color=blue" alt=""/></sub>
</div>
