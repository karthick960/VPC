## Ex-4 Virtual Private Cloud (VPC)

### Name: KARTHICK K
### Register Number: 212222040070

---

## AIM
To study the steps involved in setting up a private cloud using **AWS** or **Microsoft Azure** platforms and explore its core features and services.

---

## PROCEDURE

### **Step 1: Create a Cloud Account**
- Sign up for an account on **AWS** or **Microsoft Azure**.
- Complete verification using your **email** and **credit card**.
- Log in to the **AWS Management Console** or **Azure Portal**.

---

### **Step 2: Set Up a Virtual Private Cloud (VPC / VNet)**
- **For AWS:**
  1. Go to **VPC Dashboard** → Click **Create VPC**.
  2. Enter a name and specify the **CIDR block** (e.g., `10.0.0.0/16`).

- **For Azure:**
  1. Navigate to **Virtual Network (VNet)** in Azure Portal.
  2. Create a VNet by defining **name**, **region**, and **address space**.

---

### **Step 3: Configure Subnets and Routing**
- Create **Public** and **Private Subnets** within the VPC or VNet.
- Configure **Route Tables** to manage traffic between subnets and the internet.
- Attach an **Internet Gateway** to the public subnet for external connectivity.
- Keep private subnets isolated for internal communication.

---

### **Step 4: Create and Launch Instances**
- Launch an **EC2 Instance** (AWS) or **Virtual Machine** (Azure) within your VPC/VNet.
- Choose an appropriate **AMI** or **OS Image** (Ubuntu, Amazon Linux, Windows).
- Assign each instance to the respective subnet (Public/Private).

---

### **Step 5: Security Configuration**
- Create **Security Groups** (AWS) or **Network Security Groups (NSGs)** (Azure).
- Configure **inbound/outbound rules**:
  - Allow `SSH (22)` for Linux access.
  - Allow `RDP (3389)` for Windows access.
  - Allow `HTTP (80)` for web servers.
- Ensure private subnet instances are **not directly accessible** from the internet.

---

### **Step 6: Storage and Networking**
- Attach **Elastic Block Store (EBS)** volumes or **Azure Managed Disks**.
- Configure **Load Balancers** and **NAT Gateways** if needed.
- Verify DNS, IP allocation, and subnet connectivity.

---

### **Step 7: Testing**
- Use `ping`, `ssh`, or **RDP** to check connectivity between instances.
- Test public instance access through the internet.
- Confirm internal communication between private instances.

---

## OUTPUT
<img width="1912" height="1185" alt="Screenshot 2025-11-15 at 10 27 26 AM" src="https://github.com/user-attachments/assets/414cceab-e06b-43b2-bdd0-835ac75baadb" />
<img width="1912" height="1185" alt="Screenshot 2025-11-15 at 10 30 59 AM" src="https://github.com/user-attachments/assets/438208e2-20c3-4aff-8ce2-0098af77a3c4" />
<img width="1912" height="1185" alt="Screenshot 2025-11-15 at 10 32 20 AM" src="https://github.com/user-attachments/assets/17b51a34-3775-4d74-ac05-70828cc5ee9b" />
<img width="1912" height="1185" alt="Screenshot 2025-11-15 at 10 35 55 AM" src="https://github.com/user-attachments/assets/3fc8339a-aee5-4fbe-a78e-bcd9ef164f93" />





## RESULT
A **private cloud environment** was successfully created using the **AWS/Azure** platform.  
Core components such as **VPC/VNet**, **Subnets**, **Instances**, and **Security Groups** were configured.  
The setup was tested and verified for **internal communication** and **external access** as per the configuration.
