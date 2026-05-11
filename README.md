# CyberFort Nexus — Architecture Course Project

## Overview
Architecture design project for the Global Dev Experts Software Architecture course,
taught by Avraham Poupko.

CyberFort Nexus is an on-premises enterprise cyber threat detection platform. 
This repository documents the architectural design of the system using the 
C4 model and a formal High Level Design (HLD) document.

## Deliverables

| Milestone | Due | Description | Status |
|-----------|-----|-------------|--------|
| MS1 | Week 5 | Preliminary Solution Diagram | 🟡 In Progress |
| MS2 | Week 9 | Requirements | ⚪ Not Started |
| MS3 | Week 13 | Full HLD + Data + Security + Performance Diagrams | ⚪ Not Started |
| MS4 | End of course | Final Submission | ⚪ Not Started |

## Diagrams

### C4 Context Diagram (Level 1)
`cyberfort-nexus-preliminary-solution-diagram-c4-context.jpg`
High-level view of CyberFort Nexus and its relationships with external systems and actors.

### C4 Container Diagram (Level 2)
`cyberfort-nexus-preliminary-solution-diagram-c4-container.jpg`
Internal containers of CyberFort Nexus showing the five main components and their interactions.

## Architecture Approach
- **Modelling notation:** C4 Model (Context → Container → Component)
- **Design tool:** Miro
- **HLD template:** Markdown

## System Summary
CyberFort Nexus consists of three core subsystems:
- **Threat Detection Sensors** — File Analysis, C&C Detection, and Network Forensics
- **ACI (Automatic Cyber Investigator)** — Correlates alerts into cyber incidents
- **Investigation Portal** — Web UI for SOC analysts to investigate threats

