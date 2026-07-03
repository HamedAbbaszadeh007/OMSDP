4. Users & Roles
This section defines who can use OMSDP and what each user is allowed to do. While the previous section (Stakeholders) identifies everyone who has an interest in the platform, this section focuses on the people and system actors that actually interact with it.
A clear Users & Roles architecture is the foundation for security, authorization, workflows, APIs, and future system expansion. Every feature in the platform should be accessible according to the responsibilities of a specific role.
Objectives
The Users & Roles architecture aims to:
Define all user types.
Specify the responsibilities of each role.
Establish permission boundaries.
Support secure Role-Based Access Control (RBAC).
Prepare the platform for future growth and integration.
Core User Roles
4.1. Public User
A visitor who can access publicly available spatial information without creating an account.
Typical capabilities:
View public maps
Search public spatial data
View municipal information
Access open datasets
4.2. Registered User
A citizen or organization with an authenticated account.
Typical capabilities:
Manage profile
Submit requests
Save favorite locations
Track submitted reports
Access personalized services
4.3. Municipal Staff
Municipal employees responsible for daily operational activities.
Typical capabilities:
Edit operational records
Update municipal information
Process citizen requests
Access internal datasets
4.4. GIS Expert
Professionals responsible for spatial data management.
Typical capabilities:
Create spatial layers
Edit geometries
Manage coordinate systems
Validate spatial data
Perform GIS analysis
Publish map services
4.5. Analyst
Users who transform data into information for decision-makers.
Typical capabilities:
Perform spatial analysis
Generate reports
Create dashboards
Produce statistical summaries
Support planning decisions
4.6. API Consumer
External applications or systems that interact with OMSDP through APIs.
Typical capabilities:
Access approved datasets
Query spatial services
Integrate external applications
Synchronize information
4.7. OMSDP Developer
Developers responsible for maintaining and extending the platform.
Typical capabilities:
Develop software modules
Maintain APIs
Debug services
Deploy new features
Improve system architecture
4.8. System Administrator
Responsible for system security and infrastructure.
Typical capabilities:
Manage users and permissions
Configure servers
Monitor system health
Perform backups
Audit system activity
Manage authentication
4.9. AI Agent
An intelligent software component that assists users and supports municipal decision-making.
Typical capabilities:
Answer natural-language GIS questions
Recommend spatial analyses
Detect anomalies
Summarize datasets
Assist with planning
Provide decision support
Role-Based Access Control (RBAC)
OMSDP follows a Role-Based Access Control (RBAC) model. Permissions are assigned to roles rather than directly to individual users. This approach simplifies security management, improves scalability, and ensures consistent access control across the platform.
Future Extensions
The architecture should support additional roles without major redesign, such as:
Emergency Response Officer
Utility Operator
Environmental Specialist
Surveyor
Data Steward
Smart City Operator
Digital Twin Manager
AI Model Administrator
Summary
The Users & Roles architecture establishes a clear separation of responsibilities across the platform.
It provides the foundation for authentication, authorization, workflows, API security, auditing, and future AI integration, ensuring that OMSDP remains secure, scalable, and adaptable as new requirements emerge.
