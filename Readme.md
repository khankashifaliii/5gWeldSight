# WeldSight

### 5G-Enabled Robotic Telepresence for Hazardous Inspection

WeldSight is a robotic inspection system designed to reduce the need for humans to physically enter hazardous, elevated, or difficult-to-access environments.

The system combines a portable inspection module, camera-based sensing, Raspberry Pi onboard computing, 5G communication, AI-assisted defect detection, VR telepresence, and a digital inspection dashboard.

The core idea is simple:

> **Send the machine into the hazard. Bring the environment to the expert.**

## What We Built

* **Robotic Inspection Module** — Lightweight module designed for integration with compatible drones or robotic platforms.
* **Pan-Tilt Camera System** — Enables remote viewing and orientation of the inspection camera.
* **5G Communication** — Supports transmission of inspection data between the field system and remote operator.
* **AI-Assisted Inspection** — Computer vision models assist in identifying potential defects such as welding abnormalities and corrosion.
* **VR Telepresence** — Provides an immersive interface for remotely observing the inspection environment.
* **Inspection Dashboard** — Provides live feeds, defect reports, video analysis, inspection records and reporting.

## System Workflow

```text
Inspection Environment
        ↓
Camera & Sensors
        ↓
Raspberry Pi + 5G
        ↓
5G Communication
        ↓
AI-Assisted Analysis
        ↓
Remote Inspector / VR
        ↓
Inspection Reports & Decision
```

## Prototype

WeldSight has been developed as a physical working prototype and demonstrated at the Innovation Exhibition at Delhi Technological University.

The project includes both the physical inspection hardware and a supporting digital platform for demonstrating the complete inspection workflow.

## Demonstrations

🌐 **Live Project Website**
https://5gweldsight.vercel.app/

📺 **Complete Demonstration Playlist**
https://www.youtube.com/playlist?list=PLXbtUDOIGtPg

## Technology Stack

**Hardware:**
Raspberry Pi • Camera Module • Pan-Tilt Mechanism • 5G Modem • Power System

**Software & AI:**
Python • Computer Vision • RF-DETR • DINOv2

**Communication & Edge:**
5G • Edge Computing

**Interface:**
VR/XR • React • Web-based Inspection Dashboard

## Repository Structure

```text
5gWeldSight/
│
├── weldsight/
│   └── Website and platform implementation
│
└── README.md
```

Detailed information about the website architecture and implementation is available inside the `weldsight` directory.

## SIH 2026

**Problem Statement:** 26218
**Theme:** Robotics and Drones
**Project:** WeldSight

WeldSight demonstrates how robotic platforms, communication technologies and AI-assisted inspection can be combined to reduce human exposure to hazardous environments.

---

**Terraform Team**
