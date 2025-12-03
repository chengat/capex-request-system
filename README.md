# Corporate CapEx Request System (Power Platform)

A dual-interface Dataverse solution designed to replace legacy SharePoint workflows for capital expenditure approvals.

## Architecture
- **Backend:** Microsoft Dataverse (Relational Tables: `CostCenter` 1:N `CapexRequest`).
- **Logic:** Server-side Business Rules for compliance flagging (Amount > $10k triggers VP Audit).
- **User Interface:** 
  - **Canvas App:** Mobile-optimized interface for field entry.
  - **Model-Driven App:** Admin dashboard for Finance controllers.

## Key Features
- Dynamic "Cost Center" lookup based on Dataverse relationships.
- Automated budget validation logic.
- Role-based views (Standard User vs. Finance Admin).

## Screenshots
![Canvas App Screen](link_to_image)
![Model Driven Admin Screen](link_to_image)
![Dataverse ERD](link_to_image)
