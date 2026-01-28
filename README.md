# Gatekeeper Auth | Enterprise Access Automation Portal 🛡️

![Version](https://img.shields.io/badge/version-1.0.0-emerald)
![Role-Based Access](https://img.shields.io/badge/Security-RBAC-blue)
![Real Estate Tech](https://img.shields.io/badge/Industry-Real%20Estate-orange)

## 📌 Executive Summary
In high-stakes financial environments, manual access provisioning is a liability. **Gatekeeper Auth** is a specialized automation POC designed to streamline the invoicing application access process for global real estate operations (APAC/EMEA). 

By replacing manual email chains with a logic-driven workflow, Gatekeeper Auth reduces provisioning time by **30-40%** and ensures 100% compliance with regional data governance.



## ⚡ The Problem: "The Manual Tax"
* **Regional Silos:** Fragmented approval hierarchies across APAC and EMEA.
* **Security Risks:** High probability of "Privilege Creep" and unauthorized access due to human error.
* **Productivity Loss:** New hires facing 3-5 day delays for simple invoicing rights.
* **Audit Gaps:** No centralized, real-time audit trail for "who approved what."

## 🚀 The Solution: Automated Governance
Gatekeeper Auth provides a unified interface that routes requests based on **business logic**, not manual intervention.

### Key Features:
* **Smart Verification:** Domain-locking for `@cbre.com` ensures only internal users can trigger requests.
* **Mirror-Access Engine:** "By Reference" feature allows new users to replicate a peer's permissions, reducing decision fatigue.
* **Intelligent Routing:** Automatically identifies if a request needs a *Finance Controller* (Read-only) vs. a *Regional Business Leader* (Transactional).
* **Dynamic Team Management:** Scalable UI for joining existing teams or creating new regional cost centers.

## 🛠️ Technical Stack
* **Frontend:** HTML5, Tailwind CSS (for enterprise-grade UI)
* **Icons:** Lucide-React
* **Typography:** Plus Jakarta Sans
* **Logic:** Vanilla JavaScript (Request routing and validation engine)

## 📊 Business Impact (PM Perspective)
| Metric | Before Automation | With Gatekeeper Auth |
| :--- | :--- | :--- |
| **Provisioning Time** | 48 - 72 Hours | < 5 Minutes (Request Phase) |
| **Compliance Risk** | High (Human-led) | Low (Rule-based validation) |
| **Audit Readiness** | Manual Log Retrieval | Real-time Digital Audit Trail |
| **User Experience** | Friction-heavy | Seamless / Intuitive |
