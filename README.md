# RiskLens
A RAG-Powered Solution for Enterprise SR Management
Project: RiskLens - A RAG-Powered Solution for Enterprise SR Management

Business Problem

Nowadays enterprises are struggling in the service space. There are millions of tickets generated via phone, social media, emails, X, Facebook, and tools like JIRA, ServiceNow, etc...Our idea focuses on the need to address large amounts of duplicate tickets, slow routing, and disconnected collaboration around Service Request in a large enterprise. Some of the major impacts of the slow resolution of tickets could be Customer Dissatisfaction, Lost Productivity, Increased Support Costs, Security Vulnerabilities, Operational Disruptions, and Damaged Brand Reputation.

Solution

RiskLens is an AI RAG Powered Tool that can extract, analyze, search, and assign, tickets and related data making an efficient SR resolution tool

Workflow

A significant challenge in identifying risks within tickets is distinguishing between business, domain, and technological risks associated with Tickets. Our workflow incorporates a robust cleansing and enrichment process. When a user searches for a specific ticket, Risk Lens locates similar tickets, identifies the risk classification, and suggests potential assignees.

Key Features:

Whisperer does a detailed search on the query provided

Knowledge whisperer finds all the relevant content in the installation documents, troubleshooting guides, security documents, project contacts eg. What are the security implications of this downtime on the Postgres database system It shows the related documents, data, and source documents This is powered by Gemini RAG

Resolution Whisperer - Risk lens finds the nearest solution and associated risks, priority, etc.. from the earlier solve rickets of the same category This is powered by Gemini Falsk - Long Context

SQL whisperer - Risk Lens is also intelligent enough to figure out if the query needs to retrieve transactional data like counts/ metrics for the ticketing database. This is particularly useful for manager/auditor Roles

Assignee whisperer - Risk Lens finds the most suitable agent who has solved similar tickets earlier with corresponding feedback. This extends on top of resolution Whisperer by checking the available agent based on the shift proximity and assignment dates.

Metrics Whisperer - helps the managers and business leaders understand the state of the system including distribution of bug priorities, frequently occurring tucket categories, anomalies in ticket count per month, etc

Benefits

Improved efficiency: Streamlines SR management processes by automating risk assessment and classification. Enhanced decision-making: Enables informed decisions based on accurate risk assessments and data-driven insights. Reduced costs: Minimizes operational disruptions and support costs by proactively addressing potential risks. Enhanced customer satisfaction: Improves overall customer experience by resolving SRs more efficiently and effectively.

Conclusion

By leveraging generative AI and advanced data processing techniques, RiskLens our RAG-powered solution efficiently handles large volumes of Tickets, identifies potential risks proactively, and makes informed decisions
