Unified Operations Dashboard Prototype
EIS Project — Person 5 Deliverable
Prototype • Architecture • System Integration Overview
📌 Overview

This repository contains the working prototype developed for the Enterprise Information Systems (EIS) course.
As Person 5, my responsibilities included:

Building the Unified Operations Dashboard prototype

Designing the System Architecture Diagram

Demonstrating how different EIS systems (ERP, CRM, HRMS, WMS) connect into a central dashboard

Preparing visual evidence (screenshots) for project submission

This prototype represents a single, unified view of workforce utilisation, service quality, and warehouse performance — based on the pain points identified through interviews during Phase 1.

📊 Prototype Features
✔ Workforce & Service Health

Total Employees

Average Attendance

Average CSAT Score

Tickets Resolved

✔ Warehouse Throughput

Pick Accuracy

Orders Per Hour

✔ Integration Badges

Each KPI card shows which enterprise system provides that data:

SAP SuccessFactors (HRMS)

Biometric Attendance System

Zendesk CRM

Warehouse Management System (WMS)

ERP modules for throughput

✔ Real-Time EIS Connectivity Panel

Shows:

Number of connected enterprise systems

Current data sources

Integration status

Live sync indicator

🏗 System Architecture

The architecture diagram (included as architecture-diagram.png) shows how:

CRM

HRMS

ERP

WMS

Digital Wallet
connect to a central EIS Integration Layer, which then powers the unified dashboard.

PlantUML version included in /architecture/architecture.puml.

🖥 Screenshots

Located in the /screenshots folder:

Dashboard Top View

KPI Cards

Integration Panel

Full-page dashboard capture

🛠 Tech Stack

React (JavaScript)

Vite / Bun

CSS for custom styling

Simple mock API integration (JSON-based)

Frontend-only prototype

⚙ How to Run Locally
npm install
npm run dev


Or, if using Bun:

bun install
bun dev

📁 Folder Structure
SCM-Frontend/
   src/
      pages/
      services/
      App.jsx
      main.jsx
   screenshots/
   architecture-diagram.png
   README.md

🎯 Purpose in the Final EIS Project

This prototype supports:

✔ Phase 3 — Prototype / Working Code
✔ Phase 4 — Final Presentation Demo
✔ Shows how unified data improves decision-making
✔ Demonstrates integration across multiple enterprise systems

📢 End of README
