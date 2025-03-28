# **DevOps – Security and Compliance**  
**CST 8919**  

## Lab Assignment: Grafana Installation and Dashboard Creation for Ubuntu Server Performance

### **Objective:**
This lab guides you through the installation of Grafana on an Ubuntu machine, setting up the Azure Monitor agent for performance metrics collection, and creating a dashboard in Grafana to visualize the collected metrics.

---

### **Prerequisites:**
- An Ubuntu server (version 18.04 or later)
- An Azure account with permissions to create and manage Azure resources
- Basic understanding of Linux command line interface

---

### **Lab Tasks:**

#### **Task 1: Prepare Your Ubuntu Server**

First, ensure your server is updated and upgraded to the latest version of packages:

```bash
sudo apt-get update && sudo apt-get upgrade

### **Task 2: Install Grafana**

In this task, you will install Grafana on your Ubuntu server. Follow the steps below to set up Grafana and ensure that it is running properly.

---

#### **Step 1: Add Grafana’s Official APT Repository and Install Grafana**

1. **Install required dependencies:**
   First, install the necessary dependencies to allow the system to fetch packages over HTTPS and manage software properties.
   ```bash
   sudo apt-get install -y apt-transport-https software-properties-common wget

#### **Step 2: Add Grafana’s Official APT Repository and Install Grafana**