# 🚀 DevOps & Cloud Learning Portfolio  

This repository documents my **8-week self-directed upskilling plan** in **DevOps and Cloud Engineering**, combining structured weekly goals, hands-on labs, and continuous progress tracking.  
It demonstrates practical skills in CI/CD, containerization, cloud infrastructure, automation, and Infrastructure as Code.

---

## 🧭 Overview

The labs, notes, and weekly documentation in this repo build core competencies across key DevOps domains:

- **CI/CD Pipelines** – GitHub Actions, Jenkins (upcoming)  
- **Containers** – Docker, Docker Compose  
- **Orchestration** – Kubernetes (KodeKloud, Minikube)  
- **Cloud Platforms** – AWS (EC2, S3, IAM, Monitoring, Global Infrastructure)  
- **Infrastructure as Code** – Terraform (learning)  
- **DevSecOps Basics** – RBAC, IAM, secure configurations  
- **Linux & Automation** – Commands, processes, storage, scheduling, scripting  

Each week focuses on one or more practical skill areas supported by daily logs and reference notes.

---

# 🚀 DevOps Upskilling Roadmap (Flexible & Ongoing)

This program is no longer restricted to an 8-week timeline.  
Instead, it follows a **phase-based learning approach**, allowing progress at a natural pace while balancing job applications, family responsibilities, and day-to-day commitments.

The roadmap focuses on long-term mastery through foundational learning, hands-on practice, and practical DevOps projects.

---

## 🧭 Phase Overview

### **Phase 1 — Foundations (Linux, AWS, Docker, Kubernetes Theory)**  
Status: **Completed**  
- Linux basics, services, permissions, LVM  
- Docker fundamentals and image building  
- AWS Cloud Practitioner foundations  
- Kubernetes fundamentals via KodeKloud  
- Documentation of early progress and first CI setup

---

### **Phase 2 — Guided Hands-On Practice (Minikube + Terraform Basics)**  
Status: **In Progress**  
Focus:
- Creating Kubernetes manifests using `--dry-run`  
- Running Nginx workloads locally via Minikube  
- Organizing K8s practice projects  
- Terraform basics: providers, variables, outputs  
- Understanding Terraform workflow and state  
- Completing Terraform Basics course on KodeKloud

---

### **Phase 3 — Intermediate Terraform & Kubernetes Projects**  
Upcoming:
- Terraform state backends (S3 + DynamoDB)  
- Terraform modules and reusable infrastructure  
- AWS IaC (S3, EC2, IAM)  
- Kubernetes: ConfigMaps, Secrets, Ingress, multi-tier deployments  
- Helm chart basics (optional)

---

### **Phase 4 — CI/CD and Automation**  
Upcoming:
- GitHub Actions for automated testing & Docker builds  
- Deploying to a K8s cluster from CI  
- Terraform linting and validation workflows  
- Jenkins introduction (optional)

---

### **Phase 5 — Portfolio Projects**  
Upcoming:
- A full DevOps pipeline project combining:  
  - GitHub Actions  
  - Docker  
  - Terraform  
  - Kubernetes  
- Deploying a simple application end-to-end  
- Documenting architecture, lessons, screenshots, and workflows  

---

## 🔄 Progress Tracking

Progress will continue to be tracked weekly in each `weekXX_*/` folder,  
but the timeframe is **open-ended** and can expand naturally:

- Weekly logs (`weekXX_log.md`)  
- Hands-on labs folders  
- Notes folders (Terraform, Kubernetes, AWS, CI/CD)  
- Screenshots  
- Updated main progress table  

This flexible model ensures consistent learning without pressure.

---
## 📁 Repository Structure

```
devops-labs/
│
├── week01_lab-setup/                # Linux & AWS foundations
│   ├── README.md
│   ├── week01_log.md
│   ├── aws-lab-notes.md
│   └── screenshots/
│
├── week02_aws-labs/                 # AWS Cloud Practitioner & labs
│   ├── README.md
│   ├── week02_log.md
│   └── screenshots/
│
├── week03_docker/                   # Docker Deep Dive
│   ├── README.md
│   ├── week03_log.md
│   ├── docker-lab-notes.md
│   ├── docker-commands.md
│   └── screenshots/
│
├── week04_kubernetes/               # Kubernetes Fundamentals
│   ├── README.md
│   ├── week04_log.md
│   ├── k8s-lab-notes.md
│   └── screenshots/
│
├── week05_kubernetes-iac/           # Kubernetes & IaC Foundations
│   ├── README.md                    
│   ├── week05_log.md                
│   └── screenshots/                 # Kubernetes/AWS/Terraform progress images
│
├── week06_iac-k8s-handson/          # Week 6 – Terraform + Minikube Hands-On
│   ├── README.md                    # Week 6 progress, plan + reflection
│   ├── week06_log.md                # Daily log
│   └── screenshots/                 # AWS/Terraform progress images
│
├── week07_iac-advanced/             # Terraform + Minikube hands-on 
│   ├── README.md
│   ├── week07_log.md
│   ├── terraform-projects/
│   └── k8s-minikube-labs/
│
├── week08_terraform-advanced/       # Week 8 – Terraform State, Lifecycle, Graph & Advanced Commands
│   ├── README.md
│   ├── week08_log.md
│   ├── terraform-notes/             # State, backend concepts, lifecycle rules, graph
│   ├── hands-on-labs/               # KodeKloud state & lifecycle labs
│   └── screenshots/                # Plans, state commands, graph visuals
|
├── week09_terraform-continued/      # Week 9 – Terraform Basics Completion & Consolidation
│   ├── README.md
│   ├── week09_log.md
│   ├── hands-on-labs/               # Continued Terraform Basics labs
│   └── notes/                       # Consolidated Terraform command & state notes
|
├── docs/                           # Documentation, historical summaries, and reference notes
│   └── weekly-summaries.md         # Archived weekly progress summaries (Weeks 1–7)
|
├── linux-commands.md
├── kubectl-commands.md             
├── terraform-commands.md            
│
└── .github/workflows/
    └── ci.yml                       # GitHub Actions – CI setup

```

The repository is being gradually structured as I progress through a **phase-based, ongoing DevOps upskilling roadmap**, covering key domains such as CI/CD, containerization, cloud infrastructure, automation, and infrastructure as code.

---

## 📊 Overall Progress Summary (as of Dec 3, 2025)

| **Topic / Skill Area** | **Platform / Resource** | **Current Progress** | **Key Highlights & Achievements** |
|------------------------|-------------------------|----------------------|-----------------------------------|
| **Kubernetes (Theory + Hands-On)** | KodeKloud + Minikube | **100% (course)**; Hands-on ongoing | Completed full KodeKloud Kubernetes course. Installed and configured Minikube. Performed local hands-on practice by creating Pod, Deployment, and Service manifests and deploying an Nginx application locally. |
| **Linux Basics for DevOps** | KodeKloud | **100% Complete** | Completed all modules covering storage, LVM, networking, services, cron, security, and permissions. Certificate earned. |
| **AWS Cloud Practitioner Essentials** | AWS Skill Builder | **~90% Complete** | Completed additional modules including AI/ML & Data Analytics (Module 8) with **100% quiz score**. Remaining modules to be completed as part of the ongoing roadmap. |
| **Terraform for Beginners (Course)** | KodeKloud | **~40% Complete** | Installed Terraform locally. Covered providers, variables, outputs, Terraform workflow, state concepts, advanced commands (`validate`, `fmt`, `show`, `graph`), lifecycle rules, and mutable vs immutable infrastructure. |
| **Terraform (Local Hands-On Projects)** | Local Terraform | **Active** | Built structured Terraform projects using `main.tf`, `variables.tf`, `outputs.tf`, and `terraform.tfvars`. Practiced provider configuration, variable precedence, outputs, and full Terraform lifecycle (`init → plan → apply → destroy`). |
| **CI/CD & Automation (Intro)** | GitHub Actions | **Initial Setup Done** | Created first GitHub Actions CI workflow (`ci.yml`). CI/CD expansion planned in later phases. |
| **Portfolio & Documentation** | GitHub | **Ongoing** | Repo reorganized into a scalable, phase-based structure. Weekly logs maintained. Documentation refactored to separate historical summaries from the main README. |


📘 This table provides a high-level snapshot of progress across ongoing DevOps learning domains as part of a **phase-based, long-term upskilling roadmap**.

---
### 🔄 Recent Focus (Weeks 8–9)

- Transitioned from a fixed 8-week upskilling plan to a **phase-based learning roadmap**.
- Continued Terraform Basics learning (state, lifecycle rules, advanced commands).
- Week 9 began with limited technical progress due to intensive job application and interview preparation.
- Focus remains on steadily completing Terraform Basics while balancing real-world constraints.
  
---
## 🗓️ Weekly Progress Summaries (Archived)

Earlier weekly summaries (Weeks 1–7), including objectives, challenges, and reflections, have been archived to keep this README concise.

👉 See detailed historical summaries in:  
`/docs/weekly-summaries.md`

---

## 🗓️ Recent Updates

| **Date** | **Update** |
|-----------|------------|
| **Dec 3 (Week 8 – Day 5)** | Continued the Terraform Basics course. Covered **mutable vs immutable infrastructure**, lifecycle rules, and completed related hands-on labs. |
| **Dec 2 (Week 8 – Day 4)** | Completed additional Terraform Basics hands-on labs and reached **40% completion**. Spent the rest of the day preparing for an upcoming job interview related to a previous application. |
| **Dec 1 (Week 8 – Day 3)** | Received a job application rejection which briefly affected motivation. Later practiced for an upcoming **German-language interview**, limiting time for technical study. |
| **Nov 30 (Week 8 – Day 2)** | No study — took the day off due to household tasks for 1st Advent and helping daughter prepare for schoolwork. |
| **Nov 29 (Week 8 – Day 1)** | Reviewed earlier Terraform notes and continued the **Terraform Basics** course. Covered more about state, `terraform validate`, `terraform fmt`, `terraform show`, `terraform providers`, `terraform refresh`, and flags such as `-refresh-only` and `-refresh=false`. Also learned about `terraform graph` and visualizing dependencies with Graphviz. |
| **Nov 28 (Week 7 – Day 7)** | Continued the KodeKloud **Terraform Basics** course, completed lessons and hands-on labs on Terraform **state**, increasing progress from **31% → 36%**. |
| **Nov 27 (Week 7 – Day 6)** | Updated the repo documentation. Completed the remaining half of **AWS Cloud Practitioner Essentials Module 8 (AI/ML & Data Analytics)** and scored **100%** on the quiz. |
| **Nov 26 (Day 5)** | Worked on another job application earlier in the day. In the evening, continued **Terraform hands-on practice**. Set up a new Terraform project folder and created: `main.tf` (local + random providers), `variables.tf` (default filename variable), `outputs.tf` (random name + file path), and `terraform.tfvars` (override filename). Confirmed variable precedence and successfully ran the full Terraform workflow: `init → plan → apply → destroy`. |
| **Nov 25 (Day 4)** | Followed the updated Week 7 plan and spent 30 minutes practicing Kubernetes with Minikube. Created a new local practice folder and generated YAML manifests for **Pod, Deployment, and Service** using `--dry-run=client -o yaml > file.yaml`. Applied each resource, verified them, accessed the Nginx application in the browser, and then cleaned up by deleting the objects. |
| **Nov 24 (Day 3)** | Spent the majority of the day on a new job application. No hands-on DevOps work completed. |
| **Nov 23 (Day 2)** | No study — family responsibilities and Sunday routines made it difficult to focus. |
| **Nov 22 (Day 1)** | Completed the **Hello Minikube** tutorial from the Kubernetes website. Successfully launched the example app but wasn’t fully sure what the tutorial was intended to teach beyond verifying the Minikube environment. |
| **Nov 21 2025** | Successfully installed **Terraform v1.14.0** on Windows and verified the setup. Completed **AWS Cloud Practitioner Module 11 (Pricing & Support)** with a **90% score**. Only Modules 8, 12, and 13 remain before completing the AWS Practitioner Essentials course. |
| **Nov 20 2025** | Advanced Terraform basics further to **31% completion**. Completed lessons and hands-on labs on variable definitions and outputs (five labs total). Spent the morning preparing a new short CV (English + German). Used Markdown → PDF export for improved layout. Afternoon included exercise breaks and family responsibilities. |
| **Nov 19 2025** | Continued **Terraform for Beginners** (KodeKloud). Progress increased from 12% → **19%** after completing hands-on labs on configuring multiple providers (`local_file` and `random_pet`) and practicing the Terraform workflow. |
| **Nov 18 2025** | Updated GitHub profile and cleaned up pinned repositories. Added missing short descriptions to previous bootcamp projects for better portfolio presentation. |
| **Nov 17 2025** | Spent most of the day applying for a new role and troubleshooting formatting issues in PDFs generated from application `.docx` files. |
| **Nov 16 2025** | Installed **Minikube** using Docker Desktop as the virtualization engine. Verified installation with `minikube status`. Confirmed that `kubectl` was already available via Docker Desktop. Explored the Minikube Dashboard and prepared to begin the **Hello Minikube** tutorial next. |
| **Nov 15 2025** | Completed **AWS Cloud Practitioner Essentials – Module 4 (Going Global)**. Covered AWS CloudFormation, global infrastructure, and IaC concepts. Scored **83%** on the module quiz. |
| **Nov 14 2025** | Sick with fever — no study. |
| **Nov 13 2025** | Birthday 🎉 + attended an unexpected interview for a sales-related role. No study. |
| **Nov 12 2025** | Revisited the **Terraform for Beginners** KodeKloud course (previously at 12%). Recapped lessons after a short break. Completed the first hands-on labs on writing `.tf` files and running Terraform workflow commands. Found explanations unclear but completed the tasks successfully. |
| **Nov 11 2025** | Updated GitHub repository documentation and reorganized progress logs. |
| **Nov 10 2025** | Completed *Kubernetes for Absolute Beginners* (KodeKloud) 🎓 — 100 %. Practiced Services, ConfigMaps, Secrets and microservices deployment labs. |
| **Nov 8 2025** | Started *Terraform for Beginners* on KodeKloud (12 %). Learned IaC and HCL basics. |
| **Nov 7 2025** | Reached 70 % in *Kubernetes course*; covered Services and ConfigMaps. |
| **Nov 6 2025** | Completed AWS Cloud Practitioner Essentials Module 3 (Compute Services) with **88 % quiz score**. |
| **Nov 5 2025** | Updated GitHub repository and consolidated progress logs for early November. |
| **Nov 4 2025** | Reached **60 %** in *Kubernetes for Absolute Beginners* (KodeKloud). Completed Deployments – Updates & Rollbacks with labs. Practiced rollout, rollback, and version control using `kubectl`. |
| **Nov 3 2025** | Completed the *Linux Basics for DevOps* course on KodeKloud 🎓 (100 %). Covered disk partitioning, file systems, storage types (DAS/NAS/SAN), NFS, and LVM labs. |
| **Nov 2 2025** | Practiced Linux storage commands (`mkfs`, `mount`, `blkid`) while revisiting file system and partition management labs. |
| **Nov 1, 2025** | Completed AWS Cloud Practitioner Module 7 (Databases) and Module 2 (Compute in the Cloud) — scored 83% and 86% in the quizzes. |
| **Oct 31, 2025** | Reached 53% in KodeKloud Kubernetes course — covered Replication Controllers, ReplicaSets, and started Deployments. Began AWS Module 7 (Databases). |
| **Oct 30, 2025** | Reached 40% in Kubernetes course — learned YAML structure and created Pods with manifests via labs. |
| **Oct 29, 2025** | Began Week 4 – *Kubernetes Intro*. Completed 25% of the **KodeKloud Kubernetes for Absolute Beginners** course. Learned about cluster components, Pods, Nodes, and API server functions. Held off Minikube installation per course recommendation. |
| **Oct 28, 2025** | Closed Week 3 documentation and repo updates. Planned Week 4 learning schedule. |
| **Oct 26–27, 2025** | Advanced KodeKloud Linux Basics to 84%, covering iptables, cron, and systemctl. Containerized Pig Latin Translator app in Docker. |
| **Oct 25, 2025** | Completed AWS Cloud Practitioner Module 10 (*Monitoring, Compliance & Governance*) with 91% score. |
| **27 Oct 2025** | Practiced Docker further — built a Dockerfile for a **JavaScript CLI Pig Latin Translator** project (from bootcamp). Successfully built an image and ran it as a container. |
| **26 Oct 2025** | Continued **Linux Basics on KodeKloud**, reaching **84% completion**. Covered *Security & File Permissions (iptables)* and *Service Management* modules, including cron jobs, systemd targets, and log inspection with `journalctl`. |
| **25 Oct 2025** | Completed **AWS Cloud Practitioner Essentials – Module 10: Monitoring, Compliance & Governance**. Scored **91%** in the quiz and reviewed CloudWatch, CloudTrail, and AWS Config. |
| **24 Oct 2025** | Continued Docker Docs tutorials — explored **Volumes** and **Networking** while running the *Getting Started To-Do App* using `docker compose watch`. Understood how containers communicate within Docker networks and how volumes persist database data. Completed the **Dockerfile tutorial** — built a custom image, created a new repository on Docker Hub, and successfully pushed the image after troubleshooting Docker Desktop login. |
| **23 Oct 2025** | Completed the **Docker Docs – Get Started tutorial**. Modified and tested both front-end and back-end of the *Getting Started To-Do App* while running `docker compose watch`. Verified live reloading in browser and prepared for final Docker tutorial on **building and pushing images**. |
| **22 Oct 2025** | Continued with the **Linux Basics for DevOps** course on KodeKloud. Reached **73% completion**, covering **networking**, **security**, and **file permissions** modules. Practiced commands for SSH, SCP, user/group management, permissions, and IP configuration. |
| **21 Oct 2025** | Continued with Docker learning — attempted **Phase 2 – Building Your Own Images**, then switched to the official **Docker Docs – Get Started Guide** for practical clarity. Ran `docker run -d -p 8080:80 docker/welcome-to-docker`, inspected container logs and filesystem, and cloned the **Getting Started To-Do App** project. Executed `docker compose watch` to launch the React frontend, Node backend, and database containers. Planned to modify the app source next. |
| **20 Oct 2025** | Reviewed progress to date — 51% completion of KodeKloud Linux Basics course; Kicked off **Week 3 – Docker Deep Dive**. Updated Docker Desktop to the latest version and verified setup by running the `hello-world` container. Began *TechWorld with Nana – Learn Docker in 2025* course and completed **Phase 1 – Docker Fundamentals**, practicing image pulling, running, stopping, and removing containers (Nginx example). |
| **19 Oct 2025** | Finished **Skill Builder Lab: Introduction to AWS Identity and Access Management (IAM)** — created IAM users, roles, and policies; tested access permissions. Earned completion certificate (screenshot uploaded). Updated `aws-lab-notes.md` with summary of IAM concepts and screenshots in `/week02_aws-labs/screenshots/`.|
| **18 Oct 2025** | Completed **AWS Cloud Practitioner Essentials – Module 5 (Networking in the Cloud)**. Scored **86%** on the second attempt after revisiting VPC, subnets, and security groups concepts for deeper understanding. Completed **Module 9 (Security in the Cloud)** with **100% score** after rewatching IAM and shared responsibility model lessons. Reinforced understanding of encryption, key management, and AWS security best practices. Added module assessment screenshots to `/week02_aws-labs/screenshots/`. |
| **15 - 17 Oct 2025** | Completed AWS EC2 and S3 labs and advanced to 51% in the KodeKloud *Linux Basics* course. Reinforced Linux fundamentals (users, permissions, processes) while preparing to complete the AWS IAM lab next. |
| **13–14 Oct 2025** | Added `week02_aws-labs/` folder and initial documentation. Completed AWS Skill Builder labs **“Introduction to Amazon EC2”** and **“Introduction to Amazon S3”**, plus Cloud Practitioner Essentials **Module 6 (Storage)** with 87% quiz score. Uploaded corresponding screenshots and certificates to `/screenshots/`. |
| **11 Oct 2025** | Progressed through Module 2 (Compute in the Cloud). Planned transition to AWS Skill Builder hands-on labs and KodeKloud standard upgrade. |
| **10 Oct 2025** | Began AWS Cloud Practitioner Essentials; completed Module 1 (AWS Cloud Basics). |
| **09 Oct 2025** | Completed all core Linux labs, watched Boot.dev Linux course, created `linux-commands.md` and `week01_log.md`. Updated repo structure and main README. |
| **08 Oct 2025** | Advanced through KodeKloud Linux labs; reviewed user and permission concepts (`adduser`, `chmod`, `chown`) — hands-on practice pending. |
| **07 Oct 2025** | Continued KodeKloud Linux labs: practiced navigation (`pwd`, `ls`, `cd`), directory management, and file creation. Captured terminal screenshots. |
| **06 Oct 2025** | Set up `devops-labs` repository and `.github/workflows/` folder for initial CI/CD setup. Installed AWS Free Tier and registered on KodeKloud. Watched “Introduction to DevOps.” |

---

🧭 *This changelog is updated weekly as I progress through my **phase-based, long-term upskilling roadmap** *



