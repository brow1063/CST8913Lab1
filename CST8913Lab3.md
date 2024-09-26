Cloud Migration and Cloud Adoption – A Comparative Study of PaaS, IaaS, and SaaS Across Cloud Providers
Lab 3 by:Andrew Brown

Section 1: On-Premises Solution Design

Current Monolithic on prem design:
![Monolithic on prem Diagram](https://raw.githubusercontent.com/brow1063/CST8913Labs/main/Onprem.png)

Components that need to be migrated:
Web Application - PaaS
Database - PaaS
File storage - PaaS
Networking - Cloud-native networking
Email Services - SaaS

Section 2: Migration Strategies

Web Application - PaaS: When considering moving the Web Application to PaaS it will allow for it to be remade as microservices to modernize the application. 

Database - PaaS: When considering moving the database to a PaaS you could use Azure SQL Database. This allows for the company to focus on functionality and not having to hire additional services for customer support.

File storage - PaaS: When moving the File storage to a Paas you could use Azure Blob Storage. This allows for additional scalability and cooperation with other services.

Networking - Cloud-native networking:
If the app is being moved to microsoft Azure then the networking with take place on Azure Virtual Network allowing seemless communication with components on network.

Email Services - SaaS: When moving the email services transitioning to Microsoft365 would simplify email management.

Migration Strategy Plan:
In my prior migration strategies I proposed a strictly cloud forward migration plan but if I were considering a hybrid model and leaving the Database as an IaaS then I would Refactor the Web Application into microservices and deploy them to Azure App Services PaaS allows for simplified infrastructure. The Database will be rehosted to Azure Virtual Machine IaaS allows for greater control and customization. File Storage will remain on prem this allows for sensitive information to remain under lock and key. Networking would remain as cloud native networking or as a VNET since we are working with Azure services this allows for easy communication between the microservices. Finally we would shift the Email Services to Micsoft365 for simplified email management. 



