Comparison Lab (Google Cloud, AWS and Azure)
By Andrew Brown

# Cloud Resource Descriptions and Comparison Table:

| #  | Description | AWS (Service Name) | Azure (Service Name) | Google Cloud (Service Name) |
|----|-------------|--------------------|----------------------|----------------------------|
| 1  | A compute service that provides scalable virtual machines for running applications. | EC2 | Virtual Machines | Compute Engine |
| 2  | An object storage service used to store and retrieve data, commonly used for backups and static website content. | S3 | Blob Storage | Cloud Storage |
| 3  | A managed relational database service that supports multiple database engines like MySQL, PostgreSQL, and SQL Server. | RDS | Azure SQL Database | Cloud SQL |
| 4  | A serverless compute service that allows you to run code in response to events without provisioning or managing servers. | Lambda | Azure Functions | Cloud Functions |
| 5  | A virtual private network service that allows you to create isolated networks within the cloud provider's infrastructure. | Virtual Private Cloud | Virtual Network | Virtual Private Cloud |
| 6  | A content delivery network (CDN) service that delivers data, videos, applications, and APIs to customers around the world with low latency. | CloudFront | Azure CDN | Cloud CDN |
| 7  | A managed NoSQL database service designed for low-latency, high-scale applications. | DynamoDB | Cosmos DB | Firestone |
| 8  | A block storage service for use with virtual machines, offering persistent storage for data. | Elastic Block Store | Managed Disks | Persistent Disks |
| 9  | A managed container orchestration service based on Kubernetes. | Elastic Kubernetes Services | Azure Kubernetes Services | Google Kubernetes Engine |
| 10 | A service for managing user access and encryption keys to secure cloud resources. | Identity and Access Management | Azure Active Directory | Cloud IAM |
| 11 | A platform that automates application deployment and scaling without needing to manage infrastructure. | Elastic Beanstalk | App Service | App Engine |
| 12 | A service that provides monitoring and logging of applications and infrastructure, offering insights into resource usage and performance. | CloudWatch | Azure Monitor | Cloud Monitoring and Logging |
| 13 | A domain name system (DNS) service that routes traffic globally and translates domain names to IP addresses. | Route 53 | Azure DNS | Cloud DNS |
| 14 | A load balancing service that distributes incoming network traffic across multiple targets, improving application availability. | Elastic Loud Balancing | Azure Load Balancer | Cloud Load Balancing |
| 15 | A service that automatically scales your cloud infrastructure based on demand, ensuring resources are available as needed. | Auto Scaling | Virtual Machine Scale Sets | Instance Groups with Autoscaling |
| 16 | A message queuing service that enables applications to send and receive messages between different components. | Simple Queue Service | Azure Queue Storage | Pub/Sub |
| 17 | A managed real-time data streaming service that collects and processes large amounts of data from various sources. | Kinesis | Azure Event Hubs | Dataflow |
| 18 | A fully managed, highly scalable data warehouse service optimized for analytics and large-scale queries. | Redshift | Azure Synapse Analyitics | BigQuery |
| 19 | A service that automates the execution of workflows and allows the integration of different cloud services in a sequence of steps. | Step Functions | Azure Logic Apps | Cloud Workflows |
| 20 | A service that integrates multiple data sources and enables data migration, transformation, and movement across platforms. | AWS Glue | Azure Data Factory | Dataflow |
| 21 | A data catalog and governance service that helps manage metadata across your data estate, supporting compliance and security. | AWS Glue Data Catalog | Azure Purview | Data Catalog |
| 22 | A set of machine learning and AI services that provide pre-built models, APIs, and tools for developers to easily implement AI in their apps. | SageMaker | Azure Machine Learning | Vertex AI |
| 23 | A service that allows you to define and deploy infrastructure using code, automating the management of cloud resources. | CloudFormation | Azure Resource Manager | Deployment Manager |
| 24 | A fully managed CI/CD service that automates the building, testing, and deployment of applications to production environments. | CodePipeline | Azure DevOps | Cloud Build |
| 25 | A desktop as a service (DaaS) offering that allows you to deploy virtual desktops in the cloud and access them remotely. | WorkSpaces | Azure Virtual Desktop | Google CLoud Workstations |
| 26 | A backup and disaster recovery service that helps to protect your data by creating backups and replicas of your cloud resources. | AWS Backup | Azure Backup | Google Cloud Backup |
| 27 | A service designed for big data analytics, allowing organizations to store, process, and analyze large datasets in real time. | Elastic MapReduce | HDInsight | Dataproc |
| 28 | A file storage service for storing and sharing files with users, typically used in shared file systems across applications. | Elastic File System | Azure Files | Filestore |
| 29 | A service that helps you transcode, process, and stream media content such as video and audio. | MediaConvert | Azure Media Services | Transcoder API |
| 30 | A real-time communication service used for sending notifications, emails, and text messages to users and devices. | Simple Notification Service | Azure Notification Hubs | Firebase Cloud Messaging |

Cloud Services Comparison:
When comparing the three companies AWS, Azure, and Google Cloud, it's clear that all three platforms provide similar core functionalities, including computing, storage, databases and security. Although the main functionalities are similar, they differ in names across the platforms. For example, when it comes to computing services which allow users or companies to rent virtual servers that scale to the demand of the service, AWS uses EC2, Azure uses Virtual Machines, and Google Cloud uses Compute Engines. Storage is the shared functionality that stores files, unstructured data, and information backups, using S3 for AWS, Blob Storage for Azure, and Cloud Storage for Google Cloud. The next shared functionality is databases AWS RDS, Azure SQL Database, and Google Cloud SQL, which all provide a fully managed relational database service that supports popular database engines like MySQL and PostgreSQL. Finally, the last shared functionality is security, which allows the platforms to control resource access; the resources used for this are AWS, which uses Identity and Access Management; Azure, which uses Active Directory; and Google Cloud, which uses Cloud IAM.

Key Differences
Now that we have gone over some of the shared similarities, AWS, Azure, and Google Cloud have their own differences and advantages. AWS offers greater flexibility with services like Elastic Beanstalk, which simplifies the deployment and scaling of web applications for the user. Microsoft Azure functions well with the Microsoft ecosystem, which then allows access to a variety of tools, which is ideal for businesses that already rely on Windows Server, SQL Server, or .NET applications. Lastly, Google Cloud excels with the use of data analytics
particularly with BigQuery, which is specifically designed for large-scale data analysis.
