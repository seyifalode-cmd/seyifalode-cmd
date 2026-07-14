# Oluwaseyi Michael Falode · Cloud & Cybersecurity Engineer

> Building secure, scalable cloud infrastructure — and hunting the threats that target it.

**[View Full Project Portfolio →](https://github.com/seyifalode-cmd/portfolio)**

I work across the full cloud security stack: detection engineering and threat modelling, identity security and Zero Trust architecture, cloud-native security pipelines, and security automation. My projects are hands-on — built from scratch, validated with measurable results, documented to a standard that demonstrates the actual work.

---

## What I Work With

**Cloud & Infrastructure**
AWS · Azure · Terraform · Ansible · EC2 · S3 · Lambda · Key Vault · Auto Scaling · Load Balancers

**Containers & Orchestration**
Kubernetes · Docker · Docker Compose · Docker Swarm · Spring Boot on K8s

**CI/CD & Automation**
Jenkins (multi-node, pipelines, Groovy libraries) · Python CD · Infrastructure as Code

**Security & Threat Detection**
Detection Engineering · MITRE ATT&CK · Sigma Rules · GuardDuty · EventBridge · Lambda · CloudTrail · Microsoft Entra ID · Conditional Access · Zero Trust · CrowdStrike Falcon · Splunk · Microsoft Sentinel · Elastic SIEM · SOC Monitoring · Threat Hunting · EDR

---

## Featured Projects

| Project | What It Is |
|---------|-----------|
| [**Operation FORAGER — Detection Engineering Lab**](https://github.com/seyifalode-cmd/operation-forager-detection-lab) | End-to-end detection lab around a malware-free intrusion: 51,225 labelled synthetic log events, 4 behavioural detections in 3 structural shapes, scored 4/4 with zero false positives — plus a human-in-the-loop AI triage validation exercise |
| [**AWS GuardDuty Automated Threat Detection Pipeline**](https://github.com/seyifalode-cmd/aws-guardduty-threat-detection-pipeline) | 8-service AWS-native pipeline built from scratch: GuardDuty → EventBridge → SNS + Lambda → CloudTrail + S3 → CloudWatch. Automated EC2 isolation on HIGH severity findings. 391 sample findings processed, 8 alert emails delivered in seconds |
| [**Entra ID Conditional Access Lab**](https://github.com/seyifalode-cmd/entra-conditional-access-lab) | Enterprise identity security framework on Microsoft Entra ID Premium P2: 5 Conditional Access policies (MFA, geo-blocking, compliant device, privileged access, vendor restriction) with Graph API JSON, PowerShell deployment scripts, and What If validation |
| [**Sigma Detection Rules — 15-Rule ATT&CK Library**](https://github.com/seyifalode-cmd/sigma-detection-rules) | Production-grade detection-as-code library: 15 MITRE ATT&CK-mapped Sigma rules spanning credential access, lateral movement, exfiltration, persistence, defense evasion, and impact — each with Splunk SPL, Sentinel KQL, and Elastic translations |
| [**SOAR Playbooks — SOC Automation Library**](https://github.com/seyifalode-cmd/soar-playbooks) | 4 vendor-neutral SOAR playbooks (phishing response, suspicious login, malware/endpoint isolation, cloud misconfiguration) with Python enrichment scripts, VirusTotal/MISP/IP geo integration, and mandatory human-in-the-loop approval gates |
| [Kubernetes Container Security Pipeline](https://github.com/seyifalode-cmd/k8s-container-security-pipeline) | Three-layer DevSecOps pipeline: Trivy image scanning + OPA Gatekeeper admission control + Falco runtime threat detection on a live Minikube cluster |
| [CrowdStrike Threat Hunt — SCATTERED SPIDER](https://github.com/seyifalode-cmd/crowdstrike-threat-hunt-portfolio) | Hypothesis-driven threat hunt against a real-world eCrime group using CrowdStrike Falcon CQL, mapped to MITRE ATT&CK v14 |
| [Wiz + Palo Alto Cloud IR Playbook](https://github.com/seyifalode-cmd/wiz-paloalto-cloud-ir-playbook) | End-to-end cloud incident response — Wiz Toxic Combination detection (Log4Shell + public S3 + IAM escalation) with Palo Alto Cortex XDR automated containment |
| [Splunk SOC Monitoring Lab](https://github.com/seyifalode-cmd/splunk-soc-monitoring-lab) | End-to-end SOC monitoring environment built in Splunk with SPL queries, detection rules, scheduled alerts, and dashboards |

---

## Project Categories

### Detection Engineering & Threat Detection
- [operation-forager-detection-lab](https://github.com/seyifalode-cmd/operation-forager-detection-lab) — Malware-free intrusion simulation · 51,225 synthetic log events · 4 behavioural detections · 3 structural shapes · 4/4 validated · zero false positives · Python standard library only
- [aws-guardduty-threat-detection-pipeline](https://github.com/seyifalode-cmd/aws-guardduty-threat-detection-pipeline) — GuardDuty · EventBridge · SNS · Lambda · CloudTrail · S3 · CloudWatch · automated EC2 isolation · severity triage · forensic audit chain
- [sigma-detection-rules](https://github.com/seyifalode-cmd/sigma-detection-rules) — 15 MITRE ATT&CK-mapped Sigma rules · Splunk SPL · Sentinel KQL · Elastic · detection-as-code
- [soar-playbooks](https://github.com/seyifalode-cmd/soar-playbooks) — 4 SOAR playbooks · phishing · suspicious login · malware · cloud misconfiguration · Python enrichment · MITRE ATT&CK · human-in-the-loop
- [crowdstrike-threat-hunt-portfolio](https://github.com/seyifalode-cmd/crowdstrike-threat-hunt-portfolio) — CrowdStrike Falcon threat hunt · SCATTERED SPIDER · MITRE ATT&CK
- [splunk-soc-monitoring-lab](https://github.com/seyifalode-cmd/splunk-soc-monitoring-lab) — Splunk SOC monitoring and detection

### Identity Security & Zero Trust
- [entra-conditional-access-lab](https://github.com/seyifalode-cmd/entra-conditional-access-lab) — Microsoft Entra ID Premium P2 · 5 Conditional Access policies · MFA · geo-blocking · Intune device compliance · vendor restriction · Graph API JSON · PowerShell deployment
- [azure-cloud-security-lab](https://github.com/seyifalode-cmd/azure-cloud-security-lab) — Entra ID · RBAC · Defender for Cloud · Microsoft Sentinel · KQL

### Cloud Security & Incident Response
- [wiz-paloalto-cloud-ir-playbook](https://github.com/seyifalode-cmd/wiz-paloalto-cloud-ir-playbook) — Wiz Toxic Combination detection · Palo Alto Cortex XDR · cloud incident response
- [k8s-container-security-pipeline](https://github.com/seyifalode-cmd/k8s-container-security-pipeline) — Trivy · OPA Gatekeeper · Falco · three-layer Kubernetes security pipeline

### Cloud Infrastructure (AWS & Azure)
- [aws-terraform-ec2-iac](https://github.com/seyifalode-cmd/aws-terraform-ec2-iac) — EC2 provisioning with Terraform IaC
- [aws-serverless-web-lambda](https://github.com/seyifalode-cmd/aws-serverless-web-lambda) — Serverless web application on AWS Lambda
- [azure-key-vault-lab](https://github.com/seyifalode-cmd/azure-key-vault-lab) — Azure secrets management
- [disaster-recovery-strategy-aws](https://github.com/seyifalode-cmd/disaster-recovery-strategy-aws) — AWS multi-region DR strategy
- [load-balanced-autoscaling-webservers](https://github.com/seyifalode-cmd/load-balanced-autoscaling-webservers) — ALB + ASG with Terraform
- [terraform-remote-state-s3](https://github.com/seyifalode-cmd/terraform-remote-state-s3) — Remote Terraform state in S3
- [modular-webserver-infrastructure](https://github.com/seyifalode-cmd/modular-webserver-infrastructure) — Modular Terraform web infrastructure
- [python-appserver-provisioner](https://github.com/seyifalode-cmd/python-appserver-provisioner) — EC2 Python app server via Terraform + Ansible

### Kubernetes & Containers
- [kubernetes-rolling-deployment-demo](https://github.com/seyifalode-cmd/kubernetes-rolling-deployment-demo) — Zero-downtime K8s rolling deployments
- [kubernetes-core-namespaces-demo](https://github.com/seyifalode-cmd/kubernetes-core-namespaces-demo) — Kubernetes namespace architecture
- [kubernetes-mysql-persistent-volume-demo](https://github.com/seyifalode-cmd/kubernetes-mysql-persistent-volume-demo) — MySQL with persistent volumes on K8s
- [kubernetes-cluster-ec2-infrastructure](https://github.com/seyifalode-cmd/kubernetes-cluster-ec2-infrastructure) — K8s cluster on EC2 with Terraform
- [spring-boot-k8s-vulnerability-remediation](https://github.com/seyifalode-cmd/spring-boot-k8s-vulnerability-remediation) — Spring Boot containerisation and K8s security hardening
- [docker-swarm-ec2-provisioner](https://github.com/seyifalode-cmd/docker-swarm-ec2-provisioner) — Docker Swarm on EC2 with Terraform + Ansible
- [ghost-blog-docker-compose](https://github.com/seyifalode-cmd/ghost-blog-docker-compose) — Ghost + MySQL via Docker Compose
- [docker-springboot-container-build](https://github.com/seyifalode-cmd/docker-springboot-container-build) — Spring Boot Docker container build

### CI/CD & Jenkins
- [jenkins-ci-cd-springboot-docker](https://github.com/seyifalode-cmd/jenkins-ci-cd-springboot-docker) — Jenkins pipeline for Spring Boot + Docker
- [jenkins-docker-springboot-ci](https://github.com/seyifalode-cmd/jenkins-docker-springboot-ci) — Jenkins + Docker + Maven CI for Spring Boot
- [jenkins-multi-node-infrastructure](https://github.com/seyifalode-cmd/jenkins-multi-node-infrastructure) — Multi-node Jenkins master setup on EC2
- [jenkins-groovy-reporting-library](https://github.com/seyifalode-cmd/jenkins-groovy-reporting-library) — Reusable Groovy library for Jenkins build reports
- [python-ci-cd-pipeline](https://github.com/seyifalode-cmd/python-ci-cd-pipeline) — Jenkins + Ansible CD pipeline for Python apps

### Ansible & Configuration Management
- [ansible-control-node-provisioner](https://github.com/seyifalode-cmd/ansible-control-node-provisioner) — Provision Ansible control node on EC2
- [ansible-managed-nodes-provisioner](https://github.com/seyifalode-cmd/ansible-managed-nodes-provisioner) — Provision managed nodes for Ansible
- [ansible-control-node-setup](https://github.com/seyifalode-cmd/ansible-control-node-setup) — SSH key generation and control node config
- [ansible-sandbox-ec2](https://github.com/seyifalode-cmd/ansible-sandbox-ec2) — EC2 sandbox with Ansible pre-installed
- [mariadb-ansible-setup](https://github.com/seyifalode-cmd/mariadb-ansible-setup) — MariaDB install and config via Ansible
- [httpd-static-web-deployment](https://github.com/seyifalode-cmd/httpd-static-web-deployment) — Apache HTTP static site deployment via Ansible

### Terraform & IaC Testing
- [terratest-infrastructure](https://github.com/seyifalode-cmd/terratest-infrastructure) — Infrastructure testing with Terratest

---

## Currently Working On
- Detection engineering: building and validating behavioural detection rules mapped to MITRE ATT&CK across cloud identity, AWS, and endpoint log sources
- Cloud security automation: AWS-native threat response pipelines using GuardDuty, EventBridge, Lambda, and CloudTrail
- Identity security: Zero Trust frameworks using Microsoft Entra ID Conditional Access and least-privilege architecture

---

<p align="center">
  <a href="https://github.com/seyifalode-cmd?tab=repositories">View All Repositories</a>
</p>
