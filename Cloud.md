- [Cloud](#cloud)
  - [What is the cloud?](#what-is-the-cloud)
    - [Iaas : Virtual machines](#iaas--virtual-machines)
    - [Paas: app service](#paas-app-service)
    - [Saas: Microsoft office 365](#saas-microsoft-office-365)
    - [Plan out VNET:](#plan-out-vnet)
  - [Commands to create public and private keys for Azure](#commands-to-create-public-and-private-keys-for-azure)
  - [Self study task](#self-study-task)




# Cloud

## What is the cloud?
* Centrally managed

### Iaas : Virtual machines

### Paas: app service

### Saas: Microsoft office 365



### Plan out VNET:
2 Subnets within the Vnet:
* public-subnet (10.0.2.0/24 (256 IP address)) Virtual machine within here
* private-subnet (10.0.3.0/24 (256 IP addresses))



## Commands to create public and private keys for Azure
* "**ls -a**" to check for any .ssh files
* "**mkdir .ssh**" to create the ssh file 
* "**cd .ssh**" to see if your in the file
* "**pwd**" stands for present working directory
* "**ssh-keygen -t rsa -b 4096 -C "vineet.sethi@hotmail.co.uk"**" to create the 2 keys, one being public and one being private.


## Self study task
1. How do we know if something is in the cloud?
   * Access point- If you can access the application, data or service via the internet.
   * Storage location- Cloud storage has distinct URLs and interface for remote access.

Differences:
* On-premises the infrastrucute is owned and managed by the company. Cloud the infrasructure is owned and hosted by cloud provider.
* Location- On premises have physcial servers at the company. Cloud is hosted on remote data centers
* Access- On-premmises is limited to internal networks or VPN connections. Cloud is accessible anywhere.

<br> 

2. * Private cloud: A private cloud is a cloud environment used exclusively by a single organization. It can be hosted on-premises (within the organization's data center) or by a third-party provider.
   * A public cloud is a cloud environment offered by third-party providers (e.g., AWS, Google Cloud, Microsoft Azure) that is shared among multiple customers.
   * A hybrid cloud combines private and public cloud environments, enabling data and applications to be shared between them.
   * Multi-cloud refers to using multiple public cloud providers for different services or purposes.

<br>

3. * Iaas: IaaS provides virtualized computing resources over the internet. It offers the basic building blocks of IT infrastructure, such as servers, storage, and networking, enabling users to manage their own operating systems and applications. - E.g: Azure, AWS
   * Paas: PaaS provides a platform that enables developers to build, test, and deploy applications without worrying about managing the underlying infrastructure. E.g. Google App Engine
   * Saas: SaaS delivers software applications over the internet on a subscription basis. Users access the software through a web browser without worrying about underlying infrastructure or application management. E.g. Office 365

4. Advantage:
   * Cost Efficiency
   * Scalability and Flexibility
   * Accessibility
   * Security
  
  Disadvantage:
  * Dependency on Internet Connectivity
  * Costs Can Add Up
  * Downtime or Outages

5. CapEx (Capital Expenditure): Capital expenditure refers to large, upfront investments made by a business to acquire or upgrade physical assets like infrastructure, hardware, or buildings. These are considered long-term investments and are typically depreciated over time.<br>
OpEx (Operational Expenditure): Operational expenditure refers to ongoing expenses that cover the day-to-day operations of a business. OpEx includes costs for services, subscriptions, and utilities that are paid incrementally (monthly or annually).
1. No, migrating to the cloud is not always cheaper—it depends on several factors, including the business's specific use case, workload patterns, and how effectively resources are managed. While cloud computing offers cost-saving potential through its pay-as-you-go model and elimination of upfront investments, there are scenarios where it may become more expensive than on-premises solutions. 

2. AWS: AWS is the largest and most widely adopted cloud platform globally, offering an extensive suite of cloud services for computing, storage, databases, AI/ML, IoT, and more. It pioneered the modern cloud computing era. What makes them popular: Early Mover Advantage.
  Microsoft Azure: Microsoft Azure is the second-largest cloud provider, offering a broad range of services with a focus on seamless integration with Microsoft's ecosystem, making it a popular choice for enterprises.<br>
  Google Cloud Platform (GCP): Google Cloud is known for its data and analytics expertise, making it a popular choice for businesses looking to leverage big data, machine learning, and modern application architectures.

8. Each of them are the best in different scenarios and different situations. Also depending on the company.
9. What things do you usally need to pay for when using the cloud?  
   * Storage
   * Data Transfer
   * Databases
   * Networking
   * Software as a Service (SaaS)

10. What are the 4 pillars of DevOps and how do you they link to the cloud?
    * Collaboration and Culture: Links- Cloud platforms provide a shared environment where developers, operators, and other stakeholders can work together efficiently. Teams can access the same infrastructure and resources without physical limitations.
    * Automation: Links- The cloud makes it easy to build and deploy automated pipelines for Continuous Integration (CI) and Continuous Deployment (CD) using tools like AWS CodePipeline, Azure Pipelines, and Google Cloud Build.
    * Continuous Integration and Continuous Delivery (CI/CD): Links- The cloud enables easy provisioning of test environments that replicate production, allowing teams to perform robust automated testing.
    * Monitoring and Feedback: Links- Cloud platforms offer robust monitoring and observability tools, such as Azure, AWS


   