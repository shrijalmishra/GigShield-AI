# GigShield AI+ (AI-Powered Income Protection for Gig Workers)

## Problem Statement

Delivery partners in India (Zomato, Swiggy, etc.) face income loss due to external disruptions like heavy rain, extreme heat, pollution, and curfews. These events reduce working hours and lead to 20–30% loss of income. Currently, there is no proper income protection system for them.

---
## Market Crash Scenario

A recent simulated attack revealed that a group of delivery partners exploited insurance systems using GPS spoofing. By faking their location in high-risk zones, they triggered false payouts without actually working, draining the system’s funds.

This highlights a critical challenge:
Simple GPS-based validation is not sufficient.

Our solution addresses this by introducing advanced anti-spoofing and multi-layer validation techniques.


## Persona & Scenario

Persona: Food Delivery Partner (Zomato/Swiggy)

Example:
Rahul is a delivery partner earning ₹500 per day. Due to heavy rain, he is unable to work and loses his daily income. Our system ensures he gets compensated automatically.

---

## Solution Overview

GigShield AI+ is an AI-powered parametric insurance platform that protects delivery workers from income loss.

It uses a hybrid model:

* Detects disruptions automatically
* Verifies actual income loss using AI
* Provides instant payout

No manual claims. No paperwork.

---

## Workflow

1. User registers and allows location access
2. AI calculates risk score
3. Weekly premium is assigned
4. User activates policy
5. System monitors weather and activity
6. Disruption detected
7. AI checks income drop
8. Claim triggered automatically
9. Instant payout to user

---

## Weekly Premium Model

* Low Risk: ₹20/week → ₹500 coverage
* Medium Risk: ₹35/week → ₹800 coverage
* High Risk: ₹50/week → ₹1200 coverage

Premium is dynamically calculated using AI based on location and risk.

---

## Parametric Triggers

* Rainfall > 50mm
* Temperature > 45°C
* AQI > 300
* Curfew detected

Payout is triggered only if:

* Disruption occurs AND
* Income drops more than 20%

---

## AI/ML Approach

Instead of complex machine learning models, our system uses a rule-based and data-driven approach to simulate AI behavior:

* **Income Prediction (Simple Logic)**
  Expected income is calculated using the average of past earnings (last 7 days).

* **Dynamic Premium Calculation**
  Premium is adjusted based on risk factors such as weather conditions and location.

* **Fraud Detection (Logic-Based)**
  Detects anomalies using:

  * Sudden location jumps
  * No movement patterns
  * No delivery activity

* **Risk Scoring System**
  Each claim is assigned a score based on multiple factors to decide payout level.

This approach ensures simplicity, efficiency, and feasibility for initial implementation.


---

## Fraud Detection

* GPS location verification
* Activity tracking
* Duplicate claim detection
* Pattern analysis

---

## Adversarial Defense & Anti-Spoofing Strategy

To address advanced fraud scenarios such as GPS spoofing and coordinated fake claims, our system introduces a multi-layered AI-based defense mechanism.

### 1. Differentiation: Real vs Fake Worker

Our system does not rely only on GPS location. Instead, it analyzes behavior and activity patterns:

* **Movement Pattern Analysis**
  Real delivery partners show continuous movement, stops, and realistic travel speeds. Fake users often show static or unnatural movement patterns.

* **Order Activity Verification**
  The system checks whether the worker is actively accepting or completing deliveries during the disruption.

* **Consistency Check**
  Compares expected work behavior with actual activity to identify anomalies.

---

### 2. Multi-Source Data Validation

To detect spoofing, the system uses multiple data points beyond GPS:

* Device motion data (accelerometer patterns)
* Network consistency (sudden jumps in location)
* Historical work patterns
* Delivery activity logs (simulated)
* Area-level validation (are nearby workers also affected?)

This ensures strong validation and reduces fake claims.

---

### 3. Fraud Ring Detection

Our system identifies coordinated fraud attempts by:

* Detecting unusual spikes in claims from the same area
* Identifying similar behavior patterns across multiple users
* Flagging synchronized claim attempts

---

### 4. UX Balance (Protecting Honest Workers)

To avoid unfair rejection of genuine claims:

* Claims are **flagged, not immediately rejected**
* Partial payouts can be provided instantly
* Final verification happens in the background
* Users receive clear notifications

---

### 5. AI-Based Risk Scoring

Each claim is assigned a fraud risk score:

* **Low Risk** → Instant payout
* **Medium Risk** → Partial payout + verification
* **High Risk** → Flagged for review

---

### Conclusion

By combining behavioral analysis, multi-source data validation, and AI-driven risk scoring, our system effectively prevents large-scale fraud while ensuring fair treatment of genuine workers.


## Tech Stack

Frontend: React.js
Backend: Node.js
Database: Supabase
APIs: Weather API, Maps API
Payments: Razorpay (test mode)
AI Logic: Rule-based predictive system (simulated AI)

---

## Platform Choice

We chose a mobile-first platform because delivery partners primarily use smartphones. This allows real-time tracking, notifications, and easy access.

---

## Unique Features

* Hybrid parametric + income validation model
* Zero-touch automatic claims
* Pre-disruption alerts
* Hyperlocal pricing
* Reward system for no claims

---
## Accessibility & Affordability Features

To ensure the platform is accessible to all gig workers, including those with limited financial capacity, we introduce the following:

*Micro-Premium Model
Users can pay small daily amounts (e.g., ₹5/day) instead of a full weekly payment.

*Freemium Onboarding
New users receive a 1-week free trial to understand the benefits of the platform.

*Platform Partnership Support
Collaboration with platforms like Swiggy/Zomato to subsidize or partially cover premiums for workers.

*Pay-Later Coverage Option
Users can activate coverage even with low balance, and the premium can be deducted later from earnings.

*Loyalty Rewards System
Users with fewer claims receive discounts or bonus coverage in future weeks.

---
## Development Plan

Phase 1: Ideation and planning
Phase 2: Core system development
Phase 3: Advanced features and optimization

---

## Conclusion

GigShield AI+ provides a fair, accurate, and automated way to protect gig workers from income loss using AI and parametric insurance.

