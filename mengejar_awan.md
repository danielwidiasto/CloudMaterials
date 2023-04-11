# Bahan Ujian Cloud
## 1.  Character Cloud Computing <hr>

* On Demand Self-Service<br>
Users that use cloud computing can access computing resources and services instantly without going via a centralized IT administrator or department.

* Broad Network Access <br> 
Cloud computing services are accessible over the internet from any device with an internet connection.

* Rapid Elasticity <br>
  Cloud computing resources can be easily scaled up or down as needed to meet changing demands, without the need for manual intervention.

* Pay as you go <br>
Users will only pay for the same amount of resources they use, which can save a lot of cost when compared to investing and maintaining their own physical infrastructure.

* Resource Pooling <br> 
Multiple users can share the same physical resources, such as servers, storage, and network devices, while maintaining privacy and security.

* Measured Service <br> 
Cloud computing providers can monitor and measure resource usage, and users are typically charged based on their actual usage.


### 1.1 Advantages from using cloud computing service: <hr>
* Scalability: <br>
Without having to spend money on pricey hardware or software, cloud computing enables organizations to scale up or down their computer capabilities as needed.

* Cost savings: <br>
Businesses can save a lot of money by using cloud computing instead of building and maintaining their own IT infrastructure.

* Flexibility: <br>
Cloud computing enables workers to access information and programs from any location and on any internet-connected device.

* Disaster recovery: <br>
Companies can recover swiftly from unforeseen occurrences because to the generally effective disaster recovery solutions that cloud computing providers have in place.

* Collaboration: <br>
Regardless of their location, employees can easily work together in real-time on documents and projects thanks to cloud computing.

### 1.2 Disadvantages from using cloud computing service: <hr>
* Security: <br>
Because organizations may be entrusting their sensitive data to third-party suppliers, cloud computing might pose security issues.

* Downtime: <br>
Service interruptions or downtime may occur for cloud computing providers, which could have an effect on how a business operates.

* Dependency: <br>
Companies that significantly rely on cloud computing may wind up depending too much on their supplier, which could be dangerous if the service has problems.

* Integration: <br>
Moving to the cloud can be complicated, and it can be difficult to integrate cloud services with already-installed on-premises systems.

* Data sovereignty: <br>
Companies operating in specific sectors or nations may be compelled to keep their data on-site, which may not be achievable with all cloud computing companies.

## 2. Cloud Service Model <hr>
Cloud Services can be divided into 4 parts:
Public, Private, Hybrid, Community.

### 2.1 Public Cloud <hr>
AWS, Azure, and Google Cloud are examples of public cloud computing service models that offer resources like servers, storage, and applications to the general public over the internet and are owned by a third party that are available for customers on a pay-per-use or subscription basis where typically the customers share the same resource and reduce the cost and increase efficiency. <br>

### 2.2 Private Cloud <hr>
An infrastructure for cloud computing that is only intended for use by one company is known as a private cloud model. In a private cloud model, the organization's IT department manages and controls the computing resources, including servers, storage, and networking, that are installed on-site and protected by the firewall. <br>

Private clouds are intended for a single organization's exclusive usage, in contrast to public clouds, which are accessible to multiple organizations and handled by outside suppliers. Private clouds can provide the scalability and flexibility of cloud computing while upholding the security and control of on-premises infrastructure.

Advantages: <br>
* The user/group who owned the server has complete control over their cloud infrastructure. This includes the security, compliance, and performance.
* Private cloud server can be tuned to the owners liking. For example to meet a spesific requirements and needs.
* Less likely to get a data breach. As stated above, private cloud aren't accesible to the public. Thus making it less likely to get breached.
* Private Clouds can be more cost-effective, as the owners can leverage the scalability and flexibility of the cloud itself.

Advantages: <br>
* Need to hire a very skilled IT team of staff to manage and maintain the server.
* Initial investment required to build the cloud environment.

## 3. Cloud Delivery Models <hr>

### *Software As A Service* or *SaaS* <br>

In SaaS, software applications are delivered via the internet as a service rather than being downloaded and operated locally on a user's device. A software vendor hosts the application and makes it accessible to users online in a SaaS model. <br>
Also, customers often pay a monthly or annual subscription fee to use the vendor-hosted and maintained software. Updates, security, and maintenance of the program are all the vendor's responsibilities.

Here are some examples of SaaS: <br>
- ClickUp, a project management software.
- HubSpot, customer relationship management (CRM) system.
- Salesforce, CRM system.
- Donorbox, a non-profit donation management software.

Advantage:<br>
- Can be accessed anywhere as long as there is internet connections
- cost effective
- no need to pay for initial installment

Disadvantages:<br>
- User's data are being stored in a third party provider
- Data security and privacy control are limited.

### *Platform as a service* or *PaaS*

In PaaS, usually a third-party provider delivers hardware and software tools to the users over the internet. Later on, these tools are required by the users to develop the applications. A PaaS provider hosts the hardware and softawre on it's own infrastructure. As a result, PaaS frees devs from having to install in-house hardware and software to develop or run a new application.

Examples of PaaS: <br>
- Microsoft Azure
- SAP Cloud
- AWS Lambda
- Dokku

Advantages: <br>
- Cost Effective, as there is no need to purchase hardware or pay expenses during downtime.
- Time Savings, no need to sped time setting up/ maintaining the core stack.
- Future-Proof, Access to state-of-the-art data center, hardware and operating systems.

Disadvantages: <br>
- Vendor Dependency, very dependent upon the vendor's capabilities.
- Risk of Lock-In, Customers  may get locked into a language/interface/program they no longer need
- Compatibility, difficulties may aries if PaaS is used in conjunction with existing development platforms.
- Security Risks, While PaaS providers secure the infrastructure and platform itself; Businesses are responsilbe for security of the applications they build.

### *Infrastructure as a Service* or *IaaS* <br>

IaaS is essentially virtual servers that the customer rents from another company that has a data center. Essentially, IaaS promotes access versus ownership.

This solution provides the end user with flexibility when it comes to hosting custom-built apps or standard software while also providing a general data center for storage.

Advantages: <br>
- Pay for What You Use: Fees are computed via usage-based metrics
- Dynamically Scale: Rapidly add capacity in peak times and scale down as needed
- Reduce Downtime: IaaS enables instant recovery from outages

Disadvantages: <br>
- Unexpected Costs: Monthly fees can add up, or peak usage may be more than expected
- Vendor Lock-In: Moving from one IaaS provider to another can be challenging
- Broadband Dependency: Only as good as the reliability of the internet connection
- Third-Party Expertise: Lack of mature service providers, guidance or ecosystem support

## 4. Docker and Kubernetes <hr>

### **4.1 Docker**
Docker is an open-source containerization platform that allows developers to build, package, and deploy applications as lightweight, portable containers that can run anywhere, including in cloud computing environments. <br>

> Containers are a type of virtualization technology that allows multiple applications to run on a single operating system kernel without interfering with each other.

Docker can be used in cloud computing environments to deploy and manage applications at scale. Containers can be easily replicated and distributed across multiple nodes or clusters, allowing applications to handle large volumes of traffic or usage. Docker also provides tools for managing containers, including automated deployment, scaling, and monitoring.

Advantages of Docker:

    Portability: Docker containers can be simply transferred across data centers and public or private clouds.

    Efficiency: Docker containers use less resources than virtual machines, allowing enterprises to run more apps on the same infrastructure.

    Scalability: Docker containers can quickly scale up or down to accommodate changing workloads or demand.

    Flexibility: Docker can build and deploy applications using a variety of programming languages and technologies.

    Security: Container isolation and image scanning secure apps and data in Docker.

Disadvantages of Docker:

Docker has certain drawbacks, such as 
  - the complexity of managing multiple containers and the risk of container sprawl, where enterprises may struggle to track and manage many containers. 
  - Containerization may entail costly and time-consuming application and infrastructure changes.

### **4.2 Kubernetes**

Kubernetes is an open-source container orchestration platform that helps organizations automate the deployment, scaling, and management of containerized applications. <br>

Kubernetes is designed to manage a large number of containers and multiple clusters, providing a platform-agnostic way to deploy and manage applications across public, private, and hybrid cloud environments.

Key Features:

* Container orchestration: Kubernetes deploys, scales, and balances containerized applications across     nodes and clusters.

* Self-healing: Kubernetes automatically replaces failed containers and nodes to keep applications running.

* Kubernetes automatically discovers and routes traffic to the right container or service.

* Horizontal scaling: Kubernetes automatically scales containers up or down to address traffic spikes.

* Rolling updates and rollbacks: Kubernetes may update applications without downtime or disruptions. It can also undo updates.

* Security and compliance: Kubernetes offers RBAC, network policies, and container image scanning.

Some benefits of using Kubernetes include:

* Scalability: Kubernetes can easily scale applications to meet the needs of large or growing organizations.

* Portability: Kubernetes supports a wide range of container technologies, making it easy to move applications between different environments.

* Efficiency: Kubernetes automates many aspects of application deployment and management, saving time and resources for developers and IT teams.

* Flexibility: Kubernetes can be customized and extended to meet the specific needs of different organizations or applications.

* Community support: Kubernetes has a large and active community of developers and users, providing a wealth of resources and expertise for organizations that use the platform.

Main Drawbacks: 

* However, Kubernetes can also have a steep learning curve and may require significant expertise to deploy and manage effectively.

### **4.3 Comparisson**

Docker and Kubernetes are popular cloud computing technologies, although they handle different challenges.
Here are some key differences between Docker and Kubernetes:

1. Focus: Docker is focused on containerization, while Kubernetes is focused on container orchestration.

2. Management: Docker provides basic management capabilities for containers, while Kubernetes provides a more comprehensive solution for managing containerized applications.

3. Scalability: Docker can scale containers vertically, while Kubernetes can scale containers horizontally across multiple nodes and clusters.

4. Complexity: Docker is relatively simple to use and can be used with a wide range of tools and technologies, while Kubernetes has a steeper learning curve and requires more expertise to use effectively.

5. Community: Docker has a large and active community of developers and users, while Kubernetes has a growing and active community focused on container orchestration.

## 5. Virtualization Mechanism
