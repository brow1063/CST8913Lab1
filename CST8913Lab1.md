CST 8913 Lab Report 1
Andrew Brown 040818088

Question #1
Motivators for Cloud9's Migration to Azure: 
Cloud9 seeks to migrate to Azure to revolutionize its Video Review Tool (VRT). It needs to process large amounts of unstructured video data for its VRT and manage multiple footage streams at a time, 
leading to large amounts of video storage. This need led them to seek the benefits of AI and machine learning to gain a competitive edge. By migrating to Azure, it can access scalable computing power and storage, 
promising efficient data handling and a more sustainable and cost-efficient future for its operations.

Question #2
Questions to Understand the Infrastructure:
1.	What are the current systems used for video analysis and storage?
2.	How much video data is processed daily? 
3.	Does the video data change in volume depending on the time of year?
4.	What AI and machine learning tools are currently in use?
5.	Are there specific security or data privacy requirements for the video data?

Question #3
RACI Matrix for Migration Stakeholders:
Task	 		Responsible	Accountable	Consulted	Informed
Infrastructure Review	Data Scientist	CTO	        IT Team         Stakeholders
Migration Planning	Cloud Architect	CTO	        Data Scientist	Coaches
Data Migration	        IT Team	        IT Manager	Cloud Architect	All Employees
Testing & Validation	QA Team	Project Manager	        IT Team         Coaches
Go-Live	                Cloud Architect	CTO	        IT Team         All Employees
Post-Migration Support	IT Support	IT Manager	Cloud Architect	End Users

Question #4
Migration Approach: Cloud9 used a phased migration approach:
•	Pilot Migration: Begin by moving the VRT to Azure and testing scalability and performance.
•	Full Migration: Gradually migrate all video processing tasks to Azure, utilizing Azure Batch for computing power and Azure Blob Storage to handle video data.

Question #5
High-Level Schedule:
1.	Weeks 1-2: Assess the current infrastructure and design the migration plan.
2.	Weeks 3-4: Set up Azure Batch and Blob Storage for pilot testing.
3.	Weeks 5-6: Conduct pilot migration and monitor performance.
4.	Weeks 7-8: Complete full migration and begin data processing in Azure.
5.	Week 9: Testing and validation of the new setup.
6.	Week 10: Go live and provide ongoing support.

Question #6
Main Decision Criteria:
•	The ability to handle long-running video processing tasks.
•	On-demand scalability for computing resources.
•	Efficient data storage and retrieval for large video files.
•	Integration with AI and machine learning tools.

