Here’s the updated Module Quiz with Questions 7 and 8 added:

---

# Module 2: Compute in the Cloud

## Module Quiz

### Question 1

**Question:**  
How does Amazon EC2 compare to running servers on premises?

**Options:**

1. It is more expensive but offers more control.
2. It is more flexible, cost-effective, and quicker to get started.
3. It requires more time to set up and maintain.
4. It is only useful for large businesses.

**Correct Answer:**  
**2. It is more flexible, cost-effective, and quicker to get started.** ← Correct

**Explanation:**  
Amazon EC2 is designed to be flexible, cost-effective, and quick to set up compared to on-premises servers.

---

### Question 2

**Question:**  
What is multi-tenancy in the context of Amazon EC2 instances?

**Options:**

1. Each virtual machine is isolated but shares resources from a host machine.
2. Multiple servers run in the same data center.
3. Only one user can use the instance at a time.
4. A server can only run one type of application.

**Correct Answer:**  
**1. Each virtual machine is isolated but shares resources from a host machine.** ← Correct

**Explanation:**  
Multi-tenancy allows multiple virtual machines to share resources on the same physical host, with isolation between them.

---

### Question 3

**Question:**  
A company uses Amazon EC2 instances to deploy their application.  
What would happen if they need to stop or terminate the EC2 instances?

**Options:**

1. You are still charged for the instances.
2. The instances will automatically restart after a set time.
3. You pay only for running instances, not for stopped or terminated ones.
4. Your instances are permanently deleted and cannot be recovered.

**Correct Answer:**  
**3. You pay only for running instances, not for stopped or terminated ones.** ← Correct

**Explanation:**  
With Amazon EC2, you only pay for running instances, not for ones that are stopped or terminated.

---

### Question 4

**Question:**  
What must be specified when preparing to launch an Amazon EC2 instance?

**Options:**

1. The type of instance and the operating system
2. The amount of storage and the number of users
3. The instance's location and backup plan
4. The network bandwidth and data transfer limit

**Correct Answer:**  
**1. The type of instance and the operating system** ← Correct

**Explanation:**  
You need to choose the EC2 instance type (how powerful you want it) and the Amazon Machine Image (AMI), which determines the operating system and software for your instance.

---

### Question 5

**Question:**  
A financial institution is running a real-time analytics application that processes large datasets stored across multiple servers to provide quick query results. The application requires fast processing of data with a focus on handling large volumes of information efficiently.

Which Amazon EC2 instance type would be the BEST choice for this task?

**Options:**

1. General purpose
2. Compute optimized
3. Storage optimized
4. Memory optimized

**Correct Answer:**  
**4. Memory optimized** ← Correct

**Explanation:**  
Memory optimized instances are designed for high-memory workloads and offer the performance needed to handle large volumes of data efficiently, making them the best choice for real-time analytics.

---

### Question 6

**Question:**  
A retail company is setting up a solution to analyze historical sales data that is stored locally. The solution requires fast access to large datasets with consistent, high disk throughput for quick data retrieval.

Which Amazon EC2 instance type would be the MOST suitable for this use case?

**Options:**

1. General purpose
2. Compute optimized
3. Accelerated computing
4. Storage optimized

**Correct Answer:**  
**4. Storage optimized** ← Correct

**Explanation:**  
Storage optimized instances are designed for workloads that require high-disk throughput and low-latency access to large datasets. This makes them the best choice for data analytics applications.

---

### Question 7

**Question:**  
What is a primary advantage of using the AWS Command Line Interface (AWS CLI) over the AWS Management Console?

**Options:**

1. It provides a visual, drag-and-drop interface for managing AWS resources.
2. It uses automation and scripting, which reduces manual steps and errors.
3. It is only available for Windows users.
4. It requires fewer configurations and is ideal for one-time manual provisioning.

**Correct Answer:**  
**2. It uses automation and scripting, which reduces manual steps and errors.** ← Correct

**Explanation:**  
The AWS CLI enables automation through scripting, which is more efficient and reduces manual errors compared to the console.

---

### Question 8

**Question:**  
What is the customer's responsibility when using compute services like Amazon EC2 according to the AWS shared responsibility model?

**Options:**

1. AWS manages the security of the cloud, and the customer manages the security of the infrastructure.
2. The customer is responsible for securing the physical hardware of their EC2 instances.
3. AWS is responsible for managing the operating system, networking, and applications on the customer's EC2 instances.
4. The customer is responsible for configuring, securing, and managing the operating system, networking, and applications on their EC2 instances.

**Correct Answer:**  
**4. The customer is responsible for configuring, securing, and managing the operating system, networking, and applications on their EC2 instances.** ← Correct

**Explanation:**  
The customer handles the operating system, networking, and applications on the EC2 instances. AWS manages the hardware.

Question -

What are the required configurations when launching an Amazon EC2 instance for a web server? (Select THREE.)

Choose 3.

 A. Amazon Machine Image (AMI)

 B. Load balancing

 C. Instance type

 D. Permissions

 E. Storage

 F. Instance termination behavior

Try again

Correct!

 To launch an EC2 instance for a web server, configure the AMI to define the operating system and software; select the instance type to allocate CPU, memory, and storage; and set up storage options, including the type and size of the volume.Load balancing, permissions, and instance termination behavior are not required when launching a basic Amazon EC2 web server. 



Question -

What is an Amazon Machine Image (AMI) used for when launching an Amazon EC2 instance?

Choose 1.

 A. To choose the instance size

 B. To pre-configure the operating system and software

 C. To store instance data

 D. To configure networking settings

Try again

Correct!

 An AMI is a pre-configured virtual machine image that contains the operating system, application server, and applications. This helps to launch EC2 instances quickly with the desired software and settings.


Question -
A financial services company needs to run sensitive applications that handle confidential customer data and require compliance with industry regulations. They need complete control over the physical server, including instance placement and resource allocation.Which pricing option should they choose?

Choose 1.
 A. Savings Plans
 B. Spot Instances
 C. On Demand
 D. Dedicated Hosts
Try again
Correct!
Rationale: Dedicated Hosts provide exclusive use of a physical server, providing full control over placement and resource allocation. This is ideal for security-sensitive and licensing-specific workloads.

Question -
A startup is running a batch processing workload that can tolerate occasional interruptions, and they want to reduce costs by taking advantage of unused Amazon EC2 capacity.Which pricing option would offer them the most savings?

Choose 1.
 A. Reserved Instances
 B. On Demand
 C. Spot Instances
 D. Savings Plans
Try again
Correct!
Rationale: Spot Instances offer up to 90 percent off On-Demand pricing, making them the most cost-effective option for workloads that can tolerate interruptions.


Question -
A customer is building a new application and is unsure of their usage patterns but expects to grow and stabilize usage over time. They want to start without a long-term commitment.Which pricing option should they use?

Choose 1.
 A. Savings Plans
 B. Spot Instances
 C. Reserved Instances
 D. On Demand
Try again
Correct!
Rationale: On-Demand pricing is ideal for starting without commitment. The customer can test and adjust based on actual usage before committing to longer-term options.

Question -
What is the main reason for deploying Amazon EC2 instances across multiple Availability Zones?

Choose 1.
 A. To provide high availability by allowing instances in different Availability Zones to handle traffic if one Availability Zone fails
 B. To automatically scale instances based on resource usage in each Availability Zone
 C. To increase the power and speed of each individual instance
 D. To decrease the cost of instances by distributing them evenly across AWS Regions
Try again
Correct!
Rationale: By deploying instances across multiple Availability Zones, businesses can avoid service disruption in the event of an Availability Zone failure.

Question -
How does AWS make sure that a business can meet fluctuating demand without over-provisioning resources?

Choose 1.
 A. By providing fixed resources that are always available
 B. By offering resources that are always running, regardless of demand
 C. By requiring businesses to purchase excess resources in advance to handle peak demand
 D. By allowing businesses to provision resources that automatically scale based on demand
Try again
Correct!
Rationale: The AWS scalability and elasticity features automatically adjust resources to meet demand, resulting cost-efficiency and performance.