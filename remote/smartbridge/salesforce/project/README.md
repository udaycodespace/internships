# 🌍 Salesforce Carbon Footprint Tracker

A Salesforce CRM solution that helps organizations capture, manage, automate, and analyze carbon emission data for sustainability reporting and ESG compliance.

![Salesforce](https://img.shields.io/badge/Salesforce-CRM-00A1E0?logo=salesforce&logoColor=white)
![Apex](https://img.shields.io/badge/Apex-Backend-blue)
![LWC](https://img.shields.io/badge/Lightning-Web%20Components-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Architecture

```mermaid
flowchart LR

A[Emission Sources]
B[Salesforce CRM]
C[Automation]
D[Reports & Dashboards]
E[Business Decisions]

A --> B
B --> C
C --> D
D --> E
```

## Project Snapshot

```text
Industry      → Sustainability / ESG
Platform      → Salesforce CRM
Backend       → Apex
Frontend      → Lightning Web Components
Automation    → Flows • Triggers • Validation Rules
Goal          → Carbon Emission Management
```

## Problem

Organizations often manage carbon emissions across spreadsheets, ERP systems, and third-party tools, making reporting inconsistent, time-consuming, and difficult to audit.

## Solution

This project centralizes emission records inside Salesforce and automates validation, tracking, reporting, and notifications to provide a single source of truth.

## Features

- Carbon emission management
- Custom Salesforce objects
- Apex business logic
- Lightning Web Components
- Flow automation
- Validation Rules
- Reports & Dashboards
- REST API integration
- Role-based security
- Audit-ready records

## Tech Stack

```mermaid
mindmap
  root((Salesforce))
    Apex
    LWC
    SOQL
    Flows
    Triggers
    REST API
    Named Credentials
    SFDX
```

## Development Journey

```mermaid
timeline
    title Project Roadmap

    Requirement Analysis
      : Business Understanding

    CRM Configuration
      : Objects
      : Fields
      : Security

    Development
      : Apex
      : LWC
      : Automation

    Integration
      : REST APIs
      : Named Credentials

    Deployment
      : Testing
      : Reports
      : Final Demo
```

## Repository Structure

```text
force-app/
config/
manifest/
scripts/
docs/
```

## Demo

🎥 **Project Walkthrough**

https://drive.google.com/file/d/1_tq5sqcE4iIgMsderQ1Jk-SDYqrqJ5Wc/view?usp=sharing

## Author

**Somapuram Uday**