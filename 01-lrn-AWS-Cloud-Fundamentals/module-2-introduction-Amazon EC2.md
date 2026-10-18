Here’s the clear and simple version of the video notes:

---

### Amazon EC2 (Elastic Compute Cloud)

Amazon EC2 is a service that lets you rent **virtual servers** in the cloud.  
These virtual servers are called **EC2 instances**.

---

### Quick Reminder: Client-Server Model
Remember the coffee shop example:
- Customer (Client) asks for a latte
- Barista (Server) prepares it and gives it back

The same idea is used by almost every business (healthcare, insurance, video streaming, etc.).  
They all need **compute power** (servers) to run their applications and serve customers.

---

### Why Use EC2 Instead of Your Own Servers?

**Traditional way (On-premises):**
- You buy physical servers
- You install them in a data center
- It takes a lot of time and money

**With Amazon EC2:**
- AWS already has a huge amount of compute capacity ready
- You just request the servers you need
- They are ready in a few minutes
- When you finish, you can stop or delete them
- You only pay for the time the instances are **running**

---

### What is an EC2 Instance?
An EC2 instance is a **virtual machine (VM)**.

Multiple virtual machines share the same physical server.  
This is called **multi-tenancy**.

AWS uses a special software called a **hypervisor** to:
- Share the physical server resources
- Keep each virtual machine completely isolated and secure

You don’t manage the physical server or the hypervisor — AWS does that for you.

---

### What Can You Control on an EC2 Instance?

When you create an EC2 instance, you can choose:

- **Operating System** → Windows or Linux
- **Software** → Your own applications, websites, databases, or third-party software
- **Size** → You can make the instance bigger or smaller (this is called **vertical scaling**)
- **Networking** → Decide if the instance is public or private

You have full control over what runs on the instance.

---

### Key Benefits of EC2

- Very flexible
- Fast to start (minutes instead of weeks)
- Cost-effective (pay only for what you use)
- Easy to resize when needed
- No long-term commitment

---

**In short:**  
Amazon EC2 gives you virtual servers in the cloud that you can launch, configure, and stop whenever you want — without buying or managing physical hardware.

Here’s the clear and simple version:

---

### Amazon EC2 – Key Points

Amazon EC2 is more **flexible**, **cost-effective**, and **faster** than managing your own servers on-premises.

You can:
- Launch servers when you need them
- Scale them up or down easily
- Stop or terminate them when you no longer need them
- Pay only for the time they are running

---

### Comparing On-Premises vs Cloud Resources

#### Challenges of On-Premises Resources
If you want to create new websites using traditional servers:
- You must buy the hardware in advance
- Wait for delivery
- Install and configure everything yourself
- You are locked into a fixed capacity

This process is slow, expensive, and inflexible.


![AWS](images/on-premises.jpg)

---

#### Benefits of Using Cloud Resources (Amazon EC2)
With EC2:
- You can launch instances in minutes
- Scale up or down based on demand
- Stop instances when traffic is low
- No big upfront costs


![AWS](images/cloudresources.jpg)

---

### How Amazon EC2 Works (3 Simple Steps)

#### 1. Launch an Instance
When you create an EC2 instance, you choose:
- **Amazon Machine Image (AMI)** → This is the operating system (Windows or Linux) + any pre-installed software
- **Instance Type** → This decides the power of the server (CPU, memory, network performance)

#### 2. Connect to the Instance
You can connect to the instance in different ways:
- Applications can talk to it over the network
- For Linux → Use **SSH**
- For Windows → Use **Remote Desktop (RDP)**
- Or use AWS tools like **AWS Systems Manager** (safer and easier)

#### 3. Use the Instance
Once connected, you can:
- Run commands
- Install software
- Add storage
- Organize files
- Run your applications

---

**Summary:**  
Amazon EC2 gives you virtual servers that you can start, use, and stop whenever you need — without the long waiting time and high cost of buying physical servers.