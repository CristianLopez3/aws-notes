# What is cloud computing?

Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

### Deployment models for cloud computing

When selecting a cloud strategy, a company must consider factors such as required cloud application components, preferred resource management tools, and any legacy IT infrastructure requirements.

The three cloud computing deployment models are cloud-based, on-premises, and hybrid. 

### Cloud Based Deployment

* Run all parts of the application in the cloud.
* Migrate existing applications to the cloud.
* Design and build new applications in the cloud.


In a cloud-based deployment model, you can migrate existing applications to the cloud, or you can design and build new applications in the cloud. You can build those applications on low-level infrastructure that requires your IT staff to manage them. Alternatively, you can build them using higher-level services that reduce the management, architecting, and scaling requirements of the core infrastructure.

For example, a company might create an application consisting of virtual servers, databases, and networking components that are fully based in the cloud


###  On Premise Deployments

* Deploy resources by using virtualization and resource management tools.
* Increase resource utilization by using application management and virtualization technologies.

On-premises deployment is also known as a private cloud deployment. In this model, resources are deployed on premises by using virtualization and resource management tools.

For example, you might have applications that run on technology that is fully kept in your on-premises data center. Though this model is much like legacy IT infrastructure, its incorporation of application management and virtualization technologies helps to increase resource utilization.


### Hybrid Deployment

* Connect cloud-based resources to on-premises infrastructure.
* Integrate cloud-based resources with legacy IT applications.

In a hybrid deployment, cloud-based resources are connected to on-premises infrastructure. You might want to use this approach in a number of situations. For example, you have legacy applications that are better maintained on premises, or government regulations require your business to keep certain records on premises.

For example, suppose that a company wants to use cloud services that can automate batch data processing and analytics. However, the company has several legacy applications that are more suitable on premises and will not be migrated to the cloud. With a hybrid deployment, the company would be able to keep the legacy applications on premises while benefiting from the data and analytics services that run in the cloud.

| **Aspect**               | **Cloud-Based Deployment**                                                                 | **On-Premise Deployment**                                                         | **Hybrid Deployment**                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Infrastructure**        | Hosted entirely on a cloud provider's infrastructure (e.g., AWS, Azure, GCP).             | Hosted on physical servers located on the organization's premises.               | Combination of cloud and on-premise infrastructure.                                                   |
| **Scalability**           | Highly scalable; resources can be added or removed on-demand.                             | Limited by available hardware; scaling requires purchasing and setting up new hardware. | Offers flexibility; cloud resources can be scaled on-demand, while on-premise remains static.          |
| **Cost Structure**        | Pay-as-you-go model; operational expenditure (OPEX).                                       | High upfront capital expenditure (CAPEX) for hardware and maintenance.           | Mix of CAPEX (on-premise) and OPEX (cloud).                                                           |
| **Control**               | Limited control over infrastructure; managed by the cloud provider.                       | Full control over infrastructure, security, and data.                            | Control over on-premise components; cloud resources managed by the provider.                          |
| **Security**              | Depends on the cloud provider's security measures and configurations.                     | Full control over security measures; sensitive data stays on-site.               | Sensitive data can remain on-premise, while less critical workloads use cloud security.                |
| **Performance**           | Performance depends on internet connectivity and cloud provider's data center proximity.  | Performance depends on local network and hardware efficiency.                    | Critical workloads can run on-premise for high performance, while others leverage cloud resources.     |
| **Maintenance**           | Minimal; handled by the cloud provider.                                                   | Requires dedicated IT staff for maintenance and updates.                         | On-premise components require maintenance; cloud components are managed by the provider.              |
| **Compliance**            | May face challenges with data residency and compliance requirements.                      | Easier to comply with strict regulatory requirements.                            | Can meet compliance needs by keeping sensitive data on-premise while leveraging cloud for flexibility. |
| **Disaster Recovery**     | Cloud providers offer built-in disaster recovery options.                                  | Requires investment in backup and disaster recovery solutions.                   | Cloud can provide disaster recovery for on-premise systems.                                           |
| **Deployment Speed**      | Fast; applications can be deployed quickly using cloud resources.                         | Slower; requires setup and configuration of physical infrastructure.             | Faster than on-premise but slower than full cloud deployment.                                         |
| **Use Case**              | Suitable for startups, businesses prioritizing agility, and global scalability.           | Ideal for organizations with strict data control and compliance needs.           | Best for businesses needing both on-premise control and cloud flexibility.                            |



## Benefits of cloud computing

Consider why a company might choose to take a particular cloud computing approach when addressing business needs.

To learn more about the benefits, expand each for the following six categories.

## Quizz

1. **_What is cloud computing:_**

    a. Backing up files that are stored on desktop and mobile devices to prevent data loss
    
    b. Deploying applications connected to on-premises infrastructure

    c. Running code without needing to manage or provision servers

    d. **On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing**

The correct response option is On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing.

 
The other response options are incorrect because:

* It is possible to back up files to the cloud, but this response option does not describe cloud computing as a whole.
* Deploying applications connected to on-premises infrastructure is a sample use case for a hybrid cloud deployment. Remember that cloud computing also has cloud and on-premises (or private cloud) deployment models.
* AWS Lambda is an AWS service that lets you run code without needing to manage or provision servers. This description does not describe cloud computing as a whole. AWS Lambda is explained in greater detail later in the course.

2. **_What is another name for on-premises deployment_**?

    a. **Private Cloud**
    
    b. Cloud based application

    c. Hybrid deployment.

    d. AWS cloud.

The correct response option is Private cloud deployment.

The other response options are incorrect because:

* Cloud-based applications are fully deployed in the cloud and do not have any parts that run on premises.
* A hybrid deployment connects infrastructure and applications between cloud-based resources and existing resources that are not in the cloud, such as on-premises resources. However, a hybrid deployment is not equivalent to an on-premises deployment because it involves resources that are located in the cloud.
* The AWS Cloud offers three cloud deployment models: cloud, hybrid, and on-premises. This response option is incorrect because the AWS Cloud is not equivalent to only an on-premises deployment.

3. **_How does the scale of cloud computing help you to save costs?_**

    a. You do not have to invest in technology resources before using them.
Incorrectly selected

    b. **The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.**

    c. Accessing services on-demand helps to prevent excess or limited capacity.
Correctly unselected

    d. You can quickly deploy applications to customers and provide them with low latency.

The correct response option is The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.

 

This answer describes how customers can benefit from massive economies of scale in cloud computing.


The other response options are incorrect because:

* Not having to invest in technology resources before using them relates to Trade upfront expense for variable expense.
* Accessing services on-demand to prevent excess or limited capacity relates to Stop guessing capacity.
* Quickly deploying applications to customers and providing them with low latency relates to Go global in minutes.