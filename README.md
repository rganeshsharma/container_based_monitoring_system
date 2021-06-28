# Container Based Monitoring System

What is Container Based Monitoring System (CMS)?

A container based monitoring solution provides set of tools and technologies which enables monitoring out of the box for a Micro-services based application hosted on Kubernetes Platform. In this project we are using Kube-Prometheus-Stack. Kube-Prometheus-Stack is the latest Prometheus Operator deployment stack that includes Prometheus, Grafana, Alert Manager, Kube-State-Metrics and Prometehus Node Exporter services bundled together as Helm chart.

Components in CMS:

Virtual Machines: CentOS 7.9

CRI: Docker v1.13.1

Container Management and orchestration: Kubernetes v1.19.3

LB: Metallb v0.9.6

RP: Nginx0 v0.47.0

Container Monitoring Stack: Kube-Prometheus-Stack 0.48.0

Integrations: Slack and Node Problem Detector v0.8.8

Configuration Management: Ansible v 2.9.21


![CMS](https://user-images.githubusercontent.com/44496498/123605688-b953f000-d819-11eb-8b6a-c7d5f78f56d3.PNG)
