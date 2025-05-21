# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

# Answer

When deciding between Azure App Service and Azure Virtual Machines (VMs) for hosting an application, Azure App Service is often the more appropriate choice for several reasons:

Azure App Service is a Platform as a Service (PaaS) offering, which means Microsoft manages the underlying infrastructure, allowing developers to focus on writing code and deploying applications without worrying about servers, storage, and networking. It provides built-in scalability features, enabling applications to automatically scale based on demand, which is particularly useful for web applications with variable traffic patterns. This contrasts with VMs, which require manual intervention for scaling.

Cost efficiency is another advantage of Azure App Service. It includes many built-in features such as load balancing, auto-scaling, and patch management, which can make it more cost-effective compared to managing and maintaining VMs. Additionally, Azure App Service simplifies the deployment process with features like continuous integration and continuous deployment (CI/CD) pipelines, streamlining the process of deploying updates and new features.

Security and compliance are also strong points for Azure App Service, as it includes built-in security features such as SSL/TLS certificates, authentication and authorization, and compliance with various industry standards. This reduces the burden on developers to implement and manage security measures.

From a usability perspective, Azure App Service is designed to be user-friendly, abstracting much of the complexity associated with managing infrastructure. It integrates seamlessly with other Azure services, allowing developers to build comprehensive solutions without needing to manage the underlying infrastructure. Automatic updates and maintenance of the underlying infrastructure ensure that applications are always running on the latest and most secure platform.

In summary, Azure App Service is often a more appropriate choice for hosting applications due to its managed infrastructure, scalability, cost efficiency, simplified deployment, and built-in security features. It allows developers to focus on building and optimizing their applications without the need to manage the underlying infrastructure, making it a more efficient and effective option for many use cases.
