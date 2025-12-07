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
├── week01_lab-setup/               # Linux & AWS foundations
│   ├── README.md
│   ├── week01_log.md
│   ├── aws-lab-notes.md
│   └── screenshots/
│
├── week02_aws-labs/                # AWS Cloud Practitioner & labs
│   ├── README.md
│   ├── week02_log.md
│   └── screenshots/
│
├── week03_docker/                  # Docker Deep Dive
│   ├── README.md
│   ├── week03_log.md
│   ├── docker-lab-notes.md
│   ├── docker-commands.md
│   └── screenshots/
│
├── week04_kubernetes/              # Kubernetes Fundamentals
│   ├── README.md
│   ├── week04_log.md
│   ├── k8s-lab-notes.md
│   └── screenshots/
│
├── week05_kubernetes-iac/          # Kubernetes & IaC Foundations
│   ├── README.md                    
│   ├── week05_log.md                
│   └── screenshots/                # Kubernetes/AWS/Terraform progress images
│
├── week06_iac-k8s-handson/         # Week 6 – Terraform + Minikube Hands-On
│   ├── README.md                   # Week 6 progress, plan + reflection
│   ├── week06_log.md               # Daily log
│   └── screenshots/                # AWS/Terraform progress images
│
├── week07_iac-advanced/            # Terraform + Minikube hands-on 
│   ├── README.md
│   ├── week07_log.md
│   ├── terraform-projects/
│   └── k8s-minikube-labs/
│
├── week08_terraform-advanced/      # Week 8 – Terraform State, Lifecycle, Graph & Advanced Commands
│   ├── README.md
│   ├── week08_log.md
│   ├── terraform-notes/            # State, backend concepts, lifecycle rules, graph
│   ├── hands-on-labs/              # KodeKloud state & lifecycle labs
│   └── screenshots/                # Plans, state commands, graph visuals
|
├── week09_terraform-continued/     # Week 9 – Terraform Basics Completion & Consolidation
│   ├── README.md
│   ├── week09_log.md
│   ├── hands-on-labs/              # Continued Terraform Basics labs
│   └── notes/                      # Consolidated Terraform command & state notes
|
├── docs/                           # Documentation, historical summaries, and reference notes
|   ├── phase-roadmap.md            # phase-based, long-term roadmap for document planning + orientation                          
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

## 🔗 Links to Detailed Logs & Documentation

This repository uses a layered documentation approach to keep the main README concise while preserving detailed learning history and reflections.

- 📅 **Daily & Weekly Logs**  
  - Individual daily progress, challenges, and next steps are documented in `weekXX_log.md` files within each week’s folder.

- 🗂️ **Weekly & Historical Summaries**  
  - Earlier weekly summaries (Weeks 1–7), including objectives, challenges, and reflections, have been archived to keep this README concise.
    👉 See detailed historical summaries in:
    - `/docs/weekly-summaries.md`

- 🧭 **Phase-Based Roadmap**  
  - The long-term, phase-based DevOps upskilling structure and learning objectives are documented in:  
    - `docs/phase-roadmap.md`

- 📘 **Hands-On Notes & References**  
  - Topic-specific notes and lab documentation are maintained alongside hands-on projects in their respective folders (e.g. Kubernetes, Terraform).

This structure allows detailed progress tracking while keeping the repository easy to navigate for reviewers and recruiters.


