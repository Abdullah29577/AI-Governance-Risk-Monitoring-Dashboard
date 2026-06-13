AI-Governance-Risk-Monitoring-Dashboard

Enterprise AI Governance & Risk Monitoring Dashboard

Project Overview

This project demonstrates the design and development of an enterprise-style AI Governance & Risk Monitoring solution using Power BI.

The dashboard was created to simulate how organizations monitor AI governance processes, regulatory compliance, risk oversight activities, issue management, remediation tracking, and executive reporting.

The solution provides stakeholders with visibility into AI inventory management, governance review cycles, regulatory impact assessments, third-party AI oversight, operational issues, and remediation progress.


Key Metrics:

Total AI Use Cases
Critical Risk Count
Pending Approvals
Compliance Score
Approved Use Cases

Visualizations:

AI Risk Distribution
AI Use Cases by Department
Approval Status Overview
Regulatory Impact Exposure
2. Governance & Compliance Monitoring



Key Metrics:

Overdue Reviews
Current Reviews
High Regulatory Impact Models
Third Party Models

Visualizations:

Review Status Distribution
Third Party AI Models
Monitoring Frequency Overview
Regulatory Impact by Department
3. Issues & Remediation Management

Provides operational oversight of governance findings and corrective actions.

Key Metrics:

Open Issues
High Severity Issues
Overdue Remediations
Completed Actions

Visualizations:

Issue Severity Distribution
Issue Category Analysis
Remediation Completion Status
Remediation Priority Distribution
Overdue Remediations by Owner
Data Model

The solution uses a relational data model consisting of:

AI_Inventory

Stores AI use case information including:

Department
Risk Rating
Approval Status
Review Status
Regulatory Impact
Monitoring Frequency
Third Party Model
Issues_Register

Tracks governance findings and issues including:

Issue Severity
Issue Category
Root Cause
Status
Risk Impact
Remediation_Tracker

Tracks remediation activities and corrective actions including:

Action Owner
Priority
Due Date
Completion Status
Days Overdue

Relationships were implemented using a one-to-many star schema design centered around AI use cases.

Key Skills Demonstrated
Power BI Dashboard Development
Data Modeling
DAX Measure Creation
Risk Reporting
Governance Monitoring
Compliance Analytics
KPI Development
Executive Reporting
Issue Management
Remediation Tracking
Data Visualization
Dataset



This project uses a synthetic dataset designed to emulate enterprise AI governance and risk management processes. No confidential or proprietary organizational data was used.
