# Stakeholders (Explanation)
In the OMSDP Architecture Book, Stakeholders means all individuals, groups, or systems that have an interest in the platform or are affected by it.
This section is important because it defines who the system is for, who uses it, and who influences it. Without clearly identifying stakeholders, the system can become unclear, over-engineered, or disconnected from real needs.
Main idea
Stakeholders answer this question:
“Who cares about this system, and how are they involved?”
Types of stakeholders in OMSDP
For your municipal spatial data platform, stakeholders can be grouped into several categories:
##  Primary Users (Direct users of the system)
These people interact with OMSDP directly.
Public citizens (view maps, search services, report issues)
Registered users (submit requests, access personal data)
Municipal staff (use data for daily work)
GIS experts (manage spatial datasets, perform analysis)
## Decision Makers
These stakeholders use the system for planning and policy.
City managers
Urban planners
Municipal directors
Analysts
They don’t always use the system daily, but they depend on its outputs.
## System Operators (Internal technical roles)
These people maintain and develop the system.
OMSDP developers
System administrators
Database administrators
DevOps / infrastructure engineers
## External Systems (Non-human stakeholders)
Other systems that interact with OMSDP:
ERP systems
Utility management systems
IoT sensors (future smart city data)
Government national GIS platforms
##  AI Agent (Special stakeholder)
In your architecture vision, AI is not just a tool — it is a first-class actor:
Assists users in querying spatial data
Detects anomalies in datasets
Supports decision-making
Acts as an interface between humans and complex GIS data
Why this section is important
Defining stakeholders helps you:
Design the system around real users (not assumptions)
Separate responsibilities clearly (who does what)
Decide what features are necessary vs unnecessary
Plan user roles and permissions later (RBAC)
Ensure scalability for future integration (AI, IoT, ERP)

Simple summary
Stakeholders = everyone who uses, manages, influences, or depends on OMSDP
