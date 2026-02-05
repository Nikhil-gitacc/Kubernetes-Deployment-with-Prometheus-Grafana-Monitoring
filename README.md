# Kubernetes-Deployment-with-Prometheus-Grafana-Monitoring
Production-grade Kubernetes deployment with Prometheus &amp; Grafana monitoring. Includes Dockerized app, Helm charts, service discovery, dashboards, and alerting. Demonstrates container orchestration, observability, and SRE best practices.
# Kubernetes Deployment with Prometheus & Grafana Monitoring

This project demonstrates a production-style Kubernetes deployment with full observability using Prometheus and Grafana. It includes a Dockerized sample application, Helm-based deployments, service discovery, metrics scraping, dashboards, and alerting rules.

---

## 🚀 Architecture Overview

- **Dockerized Application**  
  A lightweight web app packaged into a container image.

- **Kubernetes Cluster**  
  Deployed on Minikube, EKS, or any CNCF-compliant cluster.

- **Helm Charts**  
  Used for deploying:
  - Application
  - Prometheus
  - Grafana

- **Prometheus**  
  Scrapes metrics from:
  - Application endpoints
  - Kubernetes nodes
  - Kube-state-metrics

- **Grafana**  
  Provides dashboards for:
  - Pod health
  - Node performance
  - Application latency
  - Resource utilization

---

## 🧰 Tech Stack

- Kubernetes  
- Docker  
- Helm  
- Prometheus  
- Grafana  
- Kube-State-Metrics  
- Node Exporter  

---

## 📦 Project Structure

---

## 🛠️ How to Deploy

### 1. Start Kubernetes Cluster

### 2. Build & Push Docker Image

### 3. Deploy Application

### 4. Deploy Monitoring Stack

### 5. Access Grafana

Login:  
- **User:** admin  
- **Password:** admin  

---

## 📊 Dashboards Included

- Kubernetes Cluster Monitoring  
- Node Exporter Full  
- Pod Resource Usage  
- Application Latency & Throughput  

---

## 🔔 Alerts Configured

- High CPU usage  
- High memory usage  
- Pod restart loops  
- Node down alerts  

---

## 🎯 Key Skills Demonstrated

- Kubernetes orchestration  
- Helm chart packaging  
- Observability & SRE best practices  
- Metrics scraping & dashboarding  
- Containerization  
- Cloud-native monitoring stack  

---

## 📌 Future Enhancements

- Add Loki for log aggregation  
- Add CI/CD pipeline with GitHub Actions  
- Add HPA (Horizontal Pod Autoscaler)  
