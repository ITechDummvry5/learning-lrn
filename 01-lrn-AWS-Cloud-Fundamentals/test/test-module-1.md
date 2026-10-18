# Module 1

## Module Quiz

### Test Your Skills – 1

In our coffee shop example, a barista and customer were used to represent the **client-server model**.

The barista represents the **server** and the customer represents the **client**.

**Question:**

Which scenario **BEST** describes how the client-server model works in this analogy?

**Options:**

1. The customer takes a cup of coffee from a self-serve station without informing the barista.

   → This describes how a client and server do not interact.

2. The barista proactively prepares a coffee and brings it to the customer without being asked.

   → This describes how the client does not need to submit a request to the server.

3. The customer makes their own coffee using the coffee shop equipment without interacting with the barista.

   → This describes how the client does not require the server.

4. **The customer goes to the barista and places an order for a coffee. The barista prepares the coffee and hands it back to the customer.**

   → This describes how the client places the request, and the server responds.

   ✅ **Correct Answer**

**Explanation:**

This scenario accurately describes the client-server model.

The **client** (customer) makes a request to the **server** (barista), and the server processes the request and sends back the response.

---

### Test Your Skills – 2

You work for a local charity organization. Your organization has sensitive data that must remain within your country for compliance reasons. However, you also need a solution that can scale quickly to handle seasonal spikes in demand. You decide to keep on-premises resources for compliance and use cloud-based resources for dynamic scaling.

**Question:**

Which type of cloud deployment does this situation describe?

**Options:**

1. On-premises deployment

   → Everything stays only in your own data center.

2. Public cloud deployment

   → Everything runs fully in the cloud.

3. **Hybrid deployment**

   → Mix of on-premises and cloud resources.

   ✅ **Correct Answer**

4. Data-compliance deployment

   → This is not a real cloud deployment type.

**Explanation:**

With a hybrid cloud solution, you can keep sensitive data on-premises to meet compliance requirements while using cloud-based resources for dynamic scaling.

### Test Your Skills – 3

A retail business plans to launch a new line of clothing, but they are struggling with accurately predicting how much server capacity they will need to support the launch.

**Question:**

Which benefit of the AWS Cloud is most relevant to this situation?

**Options:**

1. Stop spending money to run and maintain data centers.

   → Not the main point here.

2. **Stop guessing capacity.**

   → Correct Answer ✅

3. Trade upfront expense for variable expense.

   → Related, but not the best match.

4. Go global in minutes.

   → Not relevant to this situation.

**Explanation:**

With the AWS Cloud, the company can conveniently scale resources up or down based on actual demand, eliminating the need to guess future capacity requirements.

### Test Your Skills – 4

You just joined a tech start-up, and the business is growing rapidly. Your new company decides that they need to design a resilient and scalable infrastructure on AWS to handle increased traffic and help ensure high availability.

**Question:**

Which statement **BEST** describes the AWS Global Infrastructure benefit of high availability?

**Options:**

1. AWS stores all of your website’s data in a single AWS storage bucket to centralize data management.

   → This does not improve high availability.

2. AWS has many customer support options to make sure the answers to your questions are highly available on its website.

   → This is about support, not infrastructure.

3. **AWS provides multiple data centers across different geographic regions so your website can remain operational even if one location faces issues.**

   → Correct Answer ✅

4. AWS offers a single, highly secure data center that can handle all your traffic, which makes sure that your website is available.

   → A single data center is risky and not highly available.

**Explanation:**

AWS provides multiple data centers across different geographic regions. This setup enhances high availability by making sure that your online store can handle increased traffic even during unforeseen events.

### Test Your Skills – 5

You work for a startup company that is developing an application in the cloud. A new security update is available for your operating system (OS), and you are tasked with verifying that the OS is patched accordingly.

**Question:**

Which statement **BEST** describes which party is responsible for applying security patches to the OS that is running in the cloud?

**Options:**

1. AWS is responsible for applying security patches to the OS.

2. **Your company is responsible for applying security patches to the OS.**

   → Correct Answer ✅

3. Both AWS and the customer apply separate patches.

4. The OS vendor applies the patches.

**Explanation:**

The customer is responsible for managing security configurations and applying security patches to the OS running on Amazon EC2 instances.

Here’s the **full version** with every question, all options, and the correct answer clearly marked:

---

## Module Test

### Question 1

**What is the customer's responsibility, based on the AWS Shared Responsibility Model? (Select TWO.)**

- Physical security of data centers

- Networking and infrastructure hardware maintenance

- Updating compute, networking, storage, and database software

- **Managing operating system (OS) patches** ← Correct

- **Encrypting client-side data** ← Correct

---

### Question 2

**Which statement BEST describes the difference between AWS Regions and Availability Zones?**

- A. An Availability Zone spans multiple physical locations across Regions, and Regions are located across the world.

- **B. A Region is a geographical location that contains three or more Availability Zones. An Availability Zone is a distinct location within a Region that contains one or more discrete data centers.** ← Correct

- C. A Region is a single data center, and an Availability Zone consists of multiple data centers.

- D. An Availability Zone is a geographical location that contains three or more Regions. A Region is a distinct location within an Availability Zone that contains one or more discrete data centers.

---

### Question 3

**Which deployment type is BEST for this situation?**

**(Government agency wants to keep control of existing IT but use AWS for some apps)**

- **A. Hybrid** ← Correct

- B. On-premises

- C. Cloud

- D. Compliance

---

### Question 4

**Which statement accurately defines the cloud computing model and addresses the finance manager's concern about fixed costs?**

- A. Cloud computing reduces the need for additional hardware but still involves significant fixed monthly fees.

- B. Cloud computing involves purchasing dedicated servers and setting up a private data center. This model often comes with fixed costs related to hardware and maintenance.

- **C. Cloud computing is a model for delivering IT resources over the internet. Businesses can rent services on a pay-as-you-go basis, which can help reduce fixed costs and allow for more flexible budgeting.** ← Correct

- D. Cloud computing is basically just using someone else's server to host your website, and it does not offer any sort of significant cost advantages over traditional hosting solutions.

---

### Question 5

**Which statement BEST describes the client-server model and its relationship to cloud computing?**

- A. In the client-server model, the server only handles data storage, and the client performs all processing tasks. Cloud computing provides data storage, but not processing power.

- B. In the client-server model, the client is responsible for securing their data, and the server is responsible for securing the physical hardware. Cloud computing replaces the client-server model.

- **C. In the client-server model, the client sends requests to the server, which processes the requests and sends back responses. Cloud computing provides scalable server resources that can be accessed over the internet.** ← Correct

- D. The client-server model is outdated and no longer used in modern applications. Cloud computing has replaced it completely.

---

### Question 6

**What BEST describes the benefits of AWS Global Infrastructure related to this situation? (Select TWO.)**

- A. Cost savings

- **B. Fault tolerance** ← Correct

- C. Compliance with regulatory standards

- D. Ease of use

- **E. High availability** ← Correct

---

### Question 7

**Which choice BEST describes which advantage of the cloud this enterprise can benefit from?**

**(Want to reduce operational overhead of managing physical infrastructure)**

- Stop guessing capacity

- Increase speed and agility

- **Stop spending money running and maintaining data centers** ← Correct

- Benefit from massive economies of scale

---

### Question 8

**Which statement BEST describes the company's responsibility when it comes to securing physical infrastructure of the cloud?**

- A. The company does not have any responsibility when it comes to security in the cloud.

- **B. AWS is responsible for securing the physical infrastructure, and the company can focus on securing their data and applications within the cloud.** ← Correct

- C. The company is fully responsible for securing all physical infrastructure of the cloud, including data centers.

- D. The company shares responsibility with the cloud provider for securing the physical infrastructure.

---
ple:** AWS secures the physical servers, while the company protects customer information and manages access to its application.

### Summary

By combining these two concepts, a business can:

- Reach customers around the world.
- Reduce latency by deploying closer to customers.
- Improve availability by using multiple Availability Zones.
- Keep its applications and data secure through shared responsibilities.