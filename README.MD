# 🚂 IRCTC Sprint — Problem Discovery & Design Engineering Audit

A comprehensive civic-tech audit of India's largest railway booking platform, identifying critical UX, performance, accessibility, and infrastructure issues affecting millions of users every day.

---

## 📌 Project Overview

IRCTC handles:

* **8+ Crore registered users**
* **12+ Lakh bookings daily**
* **₹400+ Crore daily transaction volume**
* **6000+ train routes**
* Millions of concurrent users during Tatkal booking hours

Despite operating at massive scale, the platform suffers from recurring usability, performance, and reliability issues that directly impact users attempting to book train tickets.

This project conducts a structured design engineering audit of the platform and proposes scalable solutions backed by technical implementation plans.

---

# 🎯 Project Goal

The goal of this sprint is to:

* Identify critical user experience failures
* Analyze broken user journeys
* Quantify impact and frequency
* Propose technically feasible solutions
* Design improved user flows and wireframes
* Explore AI-driven enhancements
* Prioritize solutions using product strategy frameworks

---

# 🧩 Sprint Structure

## Part A — Problem Discovery

Six real, evidence-based UX and infrastructure failures documented from live platform exploration.

### Deliverables

* Problem Identification
* User Journey Mapping
* Frequency Analysis
* Root Cause Analysis
* Impact Assessment
* Affected User Segments

---

## Part B — Design Engineering Solutions

Each identified problem is transformed into:

* Feature Specification
* Technical Architecture Plan
* Wireframe Design
* AI Enhancement Proposal
* Success Metrics
* Effort vs Impact Prioritization

---

# 📂 Repository Structure

```text
irctc-sprint/
│
├── README.md
│
├── part-a/
│   ├── PROBLEMS.md
│   
│
├── part-b/
│   ├── SPECS.md
│   ├── AI-FEATURE.md
│   └── MATRIX.md
│
├── assets/
│   ├── screenshots/
│   ├── wireframes/

```

---

# 🌐 Platform Explored

| Category          | Details                                                   |
| ----------------- | --------------------------------------------------------- |
| Website           | irctc.co.in                                               |
| Analysis Date     | June 2026                                                 |
| Devices Tested    | Desktop, Mobile                                           |
| Browser           | Google Chrome                                             |
| Resolution        | 1536×872                                                  |
| Mobile Simulation | Responsive Testing                                        |
| Flows Explored    | Search, Booking, Payment, Waitlist, Profile, Cancellation |

---

# 🔍 Part A Findings

## Problem 1 — Tatkal Booking System Failure

### Issue

Server becomes unresponsive when Tatkal booking opens.

### Impact

* Session timeouts
* Booking failures
* Payment uncertainty

### Severity

🔴 Critical

---

## Problem 2 — Search Filters Reset

### Issue

Applied filters disappear after refresh and often show incorrect results.

### Impact

* Increased search time
* Incorrect train selection

### Severity

🟠 High

---

## Problem 3 — Seat Selection Loss

### Issue

Selected seats are not preserved during booking flow.

### Impact

* Wrong berth allocation
* Poor travel experience

### Severity

🟠 High

---

## Problem 4 — Payment Status Ambiguity

### Issue

Users receive no real-time visibility after payment initiation.

### Impact

* Duplicate payments
* Refund requests
* User panic

### Severity

🔴 Critical

---

## Problem 5 — Waitlist Information Gap

### Issue

Users cannot understand confirmation chances.

### Impact

* Poor decision-making
* Increased uncertainty

### Severity

🟡 Medium

---

## Problem 6 — Accessibility Challenges

### Issue

Platform lacks adequate support for elderly and differently-abled users.

### Impact

* Exclusion of vulnerable user groups

### Severity

🟠 High

---

# 🚀 Part B Solutions

For every identified problem:

## Feature Specification Includes

* Problem Statement
* User Story
* Proposed Solution
* Technical Architecture
* API Requirements
* Database Changes
* Edge Cases
* Success Metrics

---

## Example Features

### Smart Tatkal Queue System

Virtual waiting room with:

* Queue Position
* Estimated Wait Time
* Auto Slot Reservation
* Real-Time Updates

---

### Persistent Search Filters

Session-based filter storage ensuring:

* No filter loss
* Faster searches
* Better consistency

---

### Live Payment Tracker

Real-time transaction visibility using:

* Payment State Updates
* Gateway Status Monitoring
* Automatic Recovery

---

# 🤖 AI Proposal

## Waitlist Confirmation Predictor

### Objective

Predict the probability of waitlisted tickets getting confirmed.

### Inputs

* Historical cancellations
* Route popularity
* Seasonal demand
* Train occupancy

### Outputs

```text
Current Status: WL 12

Confirmation Probability:
87%

Recommended Alternative:
Train 12618
Probability: 93%
```

### Benefits

* Better travel planning
* Reduced uncertainty
* Higher user confidence

---

# 📊 Impact vs Effort Matrix

| Solution           | Impact | Effort | Priority      |
| ------------------ | ------ | ------ | ------------- |
| Tatkal Queue       | High   | High   | Major Project |
| Payment Tracker    | High   | Medium | Quick Win     |
| Filter Persistence | High   | Low    | Quick Win     |
| Seat Preservation  | High   | Medium | Quick Win     |
| WL Predictor       | High   | High   | Major Project |
| Accessibility Mode | Medium | Medium | Fill-In       |

---

# 📈 Expected Outcomes

| Metric                 | Current  | Target |
| ---------------------- | -------- | ------ |
| Tatkal Success Rate    | 40%      | 70%    |
| Payment Complaints     | High     | -50%   |
| Filter Failures        | 30%      | <5%    |
| Seat Allocation Errors | 25%      | <2%    |
| User Satisfaction      | Moderate | High   |

---

# 📚 Key Learnings

* Designing for scale is different from designing for aesthetics.
* Government platforms require resilience over visual complexity.
* UX and system architecture are deeply interconnected.
* AI features should solve real user problems, not exist as gimmicks.

---

# 👨‍💻 Author

**Rahul A B**

Design Engineering & AI Sprint

Kalvium RAB Program

2026

---

# 📜 License

This project is developed for educational and research purposes under the Kalvium Design Engineering Sprint Program.

---

⭐ If you found this project insightful, consider giving the repository a star.
