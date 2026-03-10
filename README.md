# Software_Quality_Plan_RuknuddinAsrari

## Test Strategy & Quality Plan — Student Registration System

> **QA Onboarding Assessment Submission**
> Prepared by: Ruknuddin Asrari | Date: March 2026 | Version: 1.0

---

## 📋 Project Overview

This repository contains the complete **Test Strategy and Quality Plan** for a web-based **Student Registration System (SRS)**. The system includes five core modules:

| Module | Description |
|---|---|
| Student Signup | New user registration with validation |
| Login | Secure authentication and session management |
| Course Enrollment | Browse and enroll in available courses |
| Profile Update | Edit personal and academic information |
| Admin Dashboard | Centralized management and monitoring |

---

## 📁 Repository Structure

```
Software_Quality_Plan_RuknuddinAsrari/
│
├── Test_Plan_Document.pdf          # Full Test Plan (Scope, Objectives, Approach, Environment, Criteria)
├── Risk_Analysis_Quality_Metrics.pdf  # Risk Register (6 risks) + Quality Metrics definitions
└── README.md                       # This file — project overview and approach
```

---

## 🎯 My Approach

### 1. Understanding the System
I began by breaking down the five modules of the SRS and identifying the key user flows — from student registration through course enrollment — as well as admin-level workflows. This informed the scope and test objectives.

### 2. Test Planning
I structured the Test Plan following the **Software Testing Life Cycle (STLC)**:
- Requirement Analysis → Test Planning → Test Design → Execution → Defect Reporting → Test Closure

The plan covers **Functional, Regression, Integration, and Performance testing**, with clear Entry and Exit Criteria to govern quality gates.

### 3. Risk Identification
I identified **6 project risks** spanning requirements quality, environment stability, resource availability, security vulnerabilities, performance under load, and data integrity. Each risk includes a **probability/impact rating** and **concrete mitigation strategies**.

### 4. Quality Metrics
Four industry-standard metrics were defined with formulas, usage guidance, and target thresholds:
- **Defect Density** — module quality indicator
- **Test Coverage** — ensures all requirements are tested
- **Pass Percentage** — real-time quality gauge
- **Defect Leakage** — measures post-release escapes

---

## 📊 Quality Standards Applied

- STLC-aligned test phases
- OWASP Top 10 referenced for security testing
- IEEE 829-inspired documentation structure
- JIRA for defect tracking; Selenium + JMeter for automation/performance

---

## 📬 Contact

For questions regarding this submission, please contact: **your.email@example.com**
