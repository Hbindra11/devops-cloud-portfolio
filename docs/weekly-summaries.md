# 🗓️ Weekly and daily Progress Summaries (Historical)

This document contains detailed weekly summaries from the early stages of the DevOps upskilling journey.
These weeks predate the transition to a phase-based roadmap and are preserved for historical and reflective purposes.

---

## 📜 Historical Progress Log

This section contains a chronological record of earlier weekly and daily updates, preserved for documentation and reflection purposes.

### Week 1 — Linux & Environment Setup (Foundations)

Focus:
- Set up the DevOps learning environment and repository structure.
- Reviewed core Linux concepts relevant to DevOps.

Key Activities:
- Practiced Linux commands including navigation, file operations, user and permission management.
- Created initial repository structure and documentation.
- Began tracking progress using daily logs.

Outcome:
- Established a working learning environment and documentation workflow.

---
### Week 2 — AWS Fundamentals & Linux Reinforcement

Focus:
- AWS Cloud Practitioner Essentials.
- Continued reinforcing Linux fundamentals.

Key Activities:
- Completed AWS Skill Builder modules covering core cloud concepts, compute, storage, and IAM basics.
- Completed AWS EC2 and S3 introductory labs.
- Documented AWS concepts and screenshots in the repository.

Outcome:
- Built foundational understanding of AWS cloud services and shared responsibility model.

---
### Week 3 — Docker Fundamentals

Focus:
- Containerization concepts and hands-on Docker practice.

Key Activities:
- Learned Docker fundamentals including images, containers, volumes, and networking.
- Ran and inspected containers using Docker CLI.
- Built Docker images and used Docker Compose for multi-container applications.
- Containerized a small JavaScript project from earlier bootcamp experience.

Outcome:
- Gained confidence working with Docker and containerized workflows.

---
### Week 4 — Kubernetes Fundamentals (Theory)

Focus:
- Kubernetes architecture and core object types.

Key Activities:
- Completed KodeKloud “Kubernetes for Absolute Beginners” course modules.
- Learned about Pods, ReplicaSets, Deployments, Services, and YAML structure.
- Practiced Kubernetes concepts through labs (theory-focused).

Outcome:
- Established strong theoretical foundation in Kubernetes, preparing for hands-on practice with Minikube.

---
### Week 5 Recap – Kubernetes + IaC Foundations

Week 5 focused on:

- Completing the **Kubernetes for Absolute Beginners** course (100%)
- Installing **Minikube** as preparation for future Kubernetes hands-on
- Beginning **Terraform Basics** (providers, workflow, simple resources)
- Continuing AWS Cloud Practitioner modules (Module 4 completed during extended period)
- Updating repository documentation and summaries

> Week 5 included a few disruptions (birthday + sick day), so some progress spilled over into the early days of Week 6.  
> The core focus was completing Kubernetes theory and beginning Infrastructure as Code fundamentals.

---

### Week 6 – IaC Progress + AWS Practitioner Advancement

**Adjusted Week 6 Objective:**  
Strengthen Terraform fundamentals and continue AWS Cloud Practitioner Essentials while preparing for full Kubernetes + Terraform hands-on work in Week 7.

### 🎯 **Goals (Revised Based on Actual Progress)**

- Strengthen Terraform basics:
  - Providers (`local_file`, `random_pet`)
  - Variables and outputs (completed)
  - Terraform workflow: `init`, `plan`, `apply`, `destroy`
- Install Terraform **locally** on Windows (completed)
- Continue AWS Cloud Practitioner Essentials:
  - Completed Module 11 (Pricing & Support) — 90%
  - Remaining: Modules 8, 12, 13
- Maintain repo documentation and weekly logs
- Prepare environment for Week 7:
  - Terraform project folder structure
  - Minikube ready for hands-on work

> Note: Full Terraform + Minikube hands-on (Deployments, Services, YAML manifests, AWS IaC projects) has been moved to **Week 7**, as Week 6 focused on regaining momentum, completing AWS Module 11, and establishing a clean Terraform local setup.

---
### Week 7 – Kubernetes & Terraform Hands-On Restart

**Adjusted Week 7 Objective:**  
Rebuild momentum after a slow start to the week by performing small, focused hands-on exercises with Minikube and Terraform. The goal was to reinforce practical skills in Kubernetes resource creation and Terraform configuration basics while balancing job applications and personal commitments.

### 🎯 Goals (Realistic and Flexible for the Week)

- Re-establish consistent progress despite variable daily availability.
- Perform hands-on Kubernetes practice using Minikube:
  - Create Pod, Deployment, and Service manifests using `--dry-run=client -o yaml`
  - Deploy an application (Nginx), access it via NodePort, and clean up resources
- Begin structured Terraform hands-on practice:
  - Configure providers (`local`, `random`)
  - Use variables, outputs, and tfvars for overrides
  - Execute full Terraform workflow (`init`, `validate`, `plan`, `apply`, `destroy`)
- Organize new local practice folders for both Kubernetes and Terraform exercises
- Document progress and maintain repo updates through the week

> Week 7 included limited time on several days due to job applications and family responsibilities, but still resulted in meaningful progress in Minikube and Terraform hands-on practice.

---

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

