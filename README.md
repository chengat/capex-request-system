# Corporate CapEx Request System (Power Platform)

A dual-interface Dataverse solution designed to replace legacy SharePoint workflows for capital expenditure approvals.
### Demo: https://youtu.be/bFEvKRbtdM0
## Architecture
- **Backend:** Microsoft Dataverse (Relational Tables: `CostCenter` 1:N `CapexRequest`).
- **Logic:** Server-side Business Rules for compliance flagging (Amount > $10k triggers VP Audit).
<img width="1308" height="922" alt="image" src="https://github.com/user-attachments/assets/cc881d1d-6505-463d-a7f9-c156475dfde8" />

- **User Interface:** 
  - **Canvas App:** Mobile-optimized interface for field entry.
  - **Model-Driven App:** Admin dashboard for Finance controllers.

## Key Features
- Dynamic "Cost Center" lookup based on Dataverse relationships.
- Automated budget validation logic.
- Role-based views (Standard User vs. Finance Admin).

## Screenshots
# Model Driven Admin Screen
CapexRequests
<img width="1724" height="962" alt="image" src="https://github.com/user-attachments/assets/65469a2f-950c-41cf-89a0-dd6c397197c1" />
<img width="1728" height="961" alt="image" src="https://github.com/user-attachments/assets/e3bd3540-8f4b-4708-ba05-6b9518e4d52b" />

CostCenters
<img width="1728" height="960" alt="image" src="https://github.com/user-attachments/assets/2b5b8f50-9e9c-425b-880b-086fa9cf84e6" />
<img width="1725" height="963" alt="image" src="https://github.com/user-attachments/assets/234534d3-d1e4-4de0-bbdc-30f5318d680f" />

# Canvas Mobile App Screen
<img width="1725" height="960" alt="image" src="https://github.com/user-attachments/assets/e176cf9e-1b5f-4550-b65b-da16bd05bce2" />
<img width="1726" height="962" alt="image" src="https://github.com/user-attachments/assets/4206d77c-01ef-4303-bc80-40de0cb2dbc4" />

# Dataverse ERD (Entity Relationship Diagram)
<img width="804" height="324" alt="image" src="https://github.com/user-attachments/assets/ce793493-c759-4601-adc4-1b6d20bcba21" />
<img width="1724" height="963" alt="image" src="https://github.com/user-attachments/assets/3d5120a3-514c-4658-802c-563954b74b06" />




