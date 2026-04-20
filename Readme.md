# 🚀 End-to-End DevOps CI/CD Pipeline with Monitoring & Alerting

## 📌 Overview

This project demonstrates a production-style DevOps pipeline integrating Infrastructure as Code, CI/CD automation, configuration management, and monitoring.

---

## 🛠 Tech Stack

* Terraform – Infrastructure provisioning
* Ansible – Configuration management
* GitHub Actions – CI/CD pipeline
* AWS EC2 – Compute
* Prometheus – Metrics collection
* Grafana – Visualization
* Node Exporter – System metrics
* Alertmanager – Alerting

---

## ⚙️ Architecture

GitHub → Actions → Terraform → AWS EC2 → Ansible → Monitoring Stack

---

## 🚀 Features

✔ Automated EC2 provisioning using Terraform
✔ Secure authentication using GitHub OIDC
✔ Remote backend using S3 (state) + DynamoDB (locking)
✔ Configuration using Ansible
✔ Monitoring with Prometheus + Grafana
✔ Alerting using Prometheus rules
✔ Conditional pipeline execution (only runs on changes)

---

## 🧠 Terraform Backend

* S3 stores Terraform state centrally
* DynamoDB provides state locking
* Prevents duplicate resource creation and ensures safe concurrent execution

---

## 📊 Monitoring Setup

* Node Exporter → exposes system metrics
* Prometheus → collects metrics
* Grafana → dashboards and visualization

---

## 🔔 Alerting

* High CPU usage alert configured
* Nginx service monitoring added
* Alerts triggered via Prometheus rules

---

## 🌐 Application

* Nginx deployed as sample application
* Custom HTML page served

---

## 📸 Screenshots

(Add Grafana dashboard + GitHub Actions pipeline here)

---

## 🧠 Learnings

* End-to-end CI/CD automation
* Secure cloud authentication using OIDC
* Infrastructure vs configuration separation
* Observability and monitoring

---
