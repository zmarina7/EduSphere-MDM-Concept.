📁EduSphere MDM (Mobile Device Management)

Subtitle: A Centralized Policy Framework for Educational Device Security



📝 Overview

EduSphere is a conceptual MDM (Mobile Device Management) solution designed mainly for boarding schools. It addresses the challenge of "Digital Distraction" by allowing school administrators to centrally manage, monitor, and restrict device usage during academic hours while fostering student self-development.



🛡 Key Security Features

Remote Policy Enforcement: Simulates the ability to "lock" or "hide" non-educational applications (TikTok, IG, Games) across 620+ devices via a single dashboard.



Role-Based Access Control (RBAC): Distinct entry points for Administrators (Directors,use 123456 password to try) and Users (Students, use any number or name for just trial), protected by credential-based authentication.

Privacy-Preserving Analytics: High-level usage tracking that focuses on "Time-on-Task" rather than intrusive content monitoring, adhering to ethical surveillance standards.



Student Growth Module: An integrated suite for study planning and career mapping, shifting the focus from "Restriction" to "Productivity."



⚙️ Technical Logic (The MDM Layer)

While the current front-end serves as the Management Console, the proposed backend utilizes:



Android Management API / Apple MDM: To push XML/JSON configuration profiles to enrolled devices.



App-Level Sandboxing: Restricting background data for blacklisted Package IDs.



Local Storage Persistence: Ensuring student study plans are saved securely on the client-side for offline access.



This project aims to support Ethiopia's Digital Sovereignty by creating localized, secure infrastructure for our schools. It reduces reliance on foreign management tools while ensuring our students remain focused, disciplined, and goal-oriented.

