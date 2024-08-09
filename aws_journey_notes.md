# AWS Cloud Practitioner Learning Journey

## Introduction

👋 Hello there! Today marks **Day ONE** of my journey to become a better data practitioner.  I'm diving into the world of AWS Cloud with this awesome video course by freeCodeCamp.org: [AWS Certified Cloud Practitioner Course](https://www.youtube.com/watch?v=NhDYbskXRgc&t=9533s). 

I'll be sharing my notes and progress here as I go, hoping it will help me solidify my understanding and perhaps be useful to others on a similar path. 

## Summary (so far)

* **Exam Overview:** 65 questions (50 scored, 15 unscored), 90 minutes exam time, 120 minutes seat time.
* **Key Concepts:** 
    * Cloud Computing Fundamentals
    * AWS Advantages
    * Global Infrastructure
* **Additional Topics:** 
    * Evolution of Computing Power
    * AWS Budget
    * MFA for Root User

## Detailed Notes 

### Cloud Computing Fundamentals

* **Definition:** Using remote servers on the internet to store, manage, and process data, instead of local servers or personal computers.
* **Evolution:** 
    * Dedicated Servers: One physical machine dedicated to a single business. Expensive, high maintenance, high security.
    * Virtual Private Server (VPS): One physical machine virtualized into multiple sub-machines for different businesses.
    * Shared Hosting: One physical machine shared by hundreds of businesses.
    * Cloud Hosting: Multiple physical machines acting as one system, abstracted into multiple cloud services.
* **Cloud Service Providers (CSPs):** Offer multiple cloud services, unified APIs, metered billing, and automation (IaC).
* **Common Cloud Services:** 
    * Compute (EC2): Virtual machines to run applications, programs, and code.
    * Networking (VPC): Virtual networks for internet connections or network isolation.
    * Storage (EBS): Virtual hard drives to store files.
    * Databases (RDS): Virtual databases for storing and reporting data.
* **Types of Cloud Computing:** 
    * SaaS (Software as a Service): A product run and managed by the service provider (e.g., Gmail, Salesforce).
    * PaaS (Platform as a Service): Focus on deployment and management of your apps (e.g., Heroku).
    * IaaS (Infrastructure as a Service): Basic building blocks for cloud IT (e.g., AWS, Azure).
* **Deployment Models:** 
    * Public Cloud: Everything is built on the CSP's infrastructure
    * Private Cloud: Everything is built on the company’s data centers
    * Hybrid: Using both on-premise and cloud service provider resources
    * Cross-Cloud: Using multiple cloud providers

### AWS Advantages and Global Infrastructure

* **Benefits:** 
    * Cost-effective: Trade fixed expenses for variable expenses, benefit from economies of scale
    * Global: Reach a wider audience and deploy resources closer to users
    * Secure: Robust security measures and compliance certifications
    * Reliable: High availability and fault tolerance
    * Scalable: Easily increase or decrease resources based on demand
    * Elastic: Automatically adjust resources to match workload fluctuations
    * Current: Access to the latest technologies and innovations

* **Global Infrastructure:**
    * Regions: Geographically distinct locations with multiple Availability Zones
    * Availability Zones: Isolated locations within a region for fault tolerance
    * Edge Locations: Points of presence for content delivery and caching
    * Direct Connect Locations: Partnered data centers for dedicated high-speed connections
    * Local Zones: Datacenters close to populated areas for low latency
    * Wavelength Zones: Edge computing on 5G networks for ultra-low latency

* **Choosing a Region:** Consider compliance, cost, available services, and latency to end-users.
* **Regional vs Global Services:** 
    * Regional services: Launched in a specific region (e.g., EC2 instances, VPCs)
    * Global services: Operate across multiple regions (e.g., IAM, Route 53)

* **Fault Tolerance:** Regions are isolated to prevent cascading failures and ensure high availability.
* **AWS Global Network:** The backbone of AWS, connecting all global infrastructure components.
* **AWS Direct Connect:** Provides dedicated, high-speed, low-latency connections from on-premise to AWS.
* **Data Residency:** The physical or geographic location of where data is stored.
* **GovCloud (US):** An isolated AWS region designed to host sensitive government data and workloads.

### Additional Topics

* **Evolution of Computing Power:**
    * From dedicated servers to serverless computing (functions running on managed containers)
    * GPUs offer significant performance boosts for certain tasks compared to CPUs

* **AWS Budget:**
    * Use CloudWatch alarms to monitor spending and receive notifications when thresholds are exceeded.

* **MFA for Root User:**
    * Enable multi-factor authentication for the root user to enhance security and protect against unauthorized access.

**Note:** This is a summary of my Day 1 learning.  I will be updating this file as I continue through the course.