# GigShield AI+ (AI-Powered Income Protection for Gig Workers)

## Problem Statement

Delivery partners in India (Zomato, Swiggy, etc.) face income loss due to external disruptions like heavy rain, extreme heat, pollution, and curfews. These events reduce working hours and lead to 20–30% loss of income. Currently, there is no proper income protection system for them.

---

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

## AI/ML Integration

* Predict expected income using past data
* Calculate dynamic weekly premium
* Detect fraud (GPS spoofing, fake claims)
* Predict future disruptions

---

## Fraud Detection

* GPS location verification
* Activity tracking
* Duplicate claim detection
* Pattern analysis

---

## Tech Stack

Frontend: React.js
Backend: Node.js
AI/ML: Python
Database: MongoDB
APIs: Weather API, Maps API
Payments: Razorpay (test mode)

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

Micro-Premium Model
Users can pay small daily amounts (e.g., ₹5/day) instead of a full weekly payment.

Freemium Onboarding
New users receive a 1-week free trial to understand the benefits of the platform.

Platform Partnership Support
Collaboration with platforms like Swiggy/Zomato to subsidize or partially cover premiums for workers.

Pay-Later Coverage Option
Users can activate coverage even with low balance, and the premium can be deducted later from earnings.

Loyalty Rewards System
Users with fewer claims receive discounts or bonus coverage in future weeks.

---
## Development Plan

Phase 1: Ideation and planning
Phase 2: Core system development
Phase 3: Advanced features and optimization

---

## Conclusion

GigShield AI+ provides a fair, accurate, and automated way to protect gig workers from income loss using AI and parametric insurance.
# GigShield-AI
