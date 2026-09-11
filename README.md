# 🍔 Food Delivery Late Order — APM Case Study

> A Product Management case study focused on identifying the root causes of
> late food deliveries and designing practical product solutions to improve
> delivery reliability and customer experience.

---

## 📌 Case Study Overview

Late food deliveries are one of the common problems in food delivery
products. A delay can negatively affect customer satisfaction, restaurant
ratings, delivery-partner experience, and repeat usage.

This case study explores the problem from an Associate Product Manager (APM)
perspective by understanding the user problem, identifying possible root
causes, prioritizing solutions, defining success metrics, and proposing an
MVP.

**Case Study Type:** Product Management / APM Portfolio Project  
**Domain:** Food Delivery  
**Role:** Associate Product Manager (Case Study)  
**Status:** Portfolio Project

---

## 🎯 Problem Statement

Customers place food orders expecting them to arrive within the estimated
delivery time.

However, some orders arrive significantly later than the promised or
estimated time.

### Key Problem

**How might we reduce late food deliveries while maintaining a reliable
experience for customers, restaurants, and delivery partners?**

---

## 👥 Users & Stakeholders

### Primary Users
- Customers
- Delivery Partners

### Key Stakeholders
- Restaurant Partners
- Customer Support
- Operations Team
- Engineering Team
- Product Team
- Data / Analytics Team

---

## 🔍 Understanding the Problem

A late order can happen because of multiple factors rather than a single
issue.

### Possible Root Causes

1. **Restaurant Preparation Delay**
   - Food preparation takes longer than expected.
   - Restaurant receives multiple orders simultaneously.

2. **Delivery Partner Availability**
   - No nearby delivery partner is available.
   - Partner assignment takes longer than expected.

3. **Traffic & Distance**
   - Heavy traffic affects delivery time.
   - Actual travel time differs from estimated travel time.

4. **ETA Prediction**
   - Estimated delivery time may not accurately reflect real-time
     conditions.

5. **Customer Communication**
   - Customers may not receive timely updates when an order is delayed.

---

## 🧠 Root Cause Analysis

### Example Order Journey

Customer places order  
↓  
Restaurant accepts order  
↓  
Food preparation  
↓  
Delivery partner assignment  
↓  
Pickup  
↓  
Travel to customer  
↓  
Order delivered

### Potential Delay Points

**Restaurant → Partner Assignment → Pickup → Travel → Customer**

The product should identify which stage is responsible for the delay instead
of treating every late order as the same problem.

---

## 💡 Product Opportunity

Instead of only informing customers after an order becomes late, the product
can detect potential delays earlier and take preventive actions.

### Opportunity Areas

- Improve ETA accuracy
- Detect potential delays early
- Improve delivery-partner assignment
- Improve restaurant preparation visibility
- Communicate delays clearly to customers

---

## 🏆 Prioritization

I would prioritize solutions based on:

- Customer impact
- Business impact
- Implementation effort
- Technical feasibility
- Frequency of the problem

### Priority Matrix

| Solution | Impact | Effort | Priority |
|---|---|---|---|
| Early delay detection | High | Medium | 🔴 High |
| Real-time ETA improvement | High | High | 🔴 High |
| Better delay notifications | Medium | Low | 🟢 High |
| Restaurant preparation tracking | High | Medium | 🟠 Medium |
| UI customization improvements | Low | Low | ⚪ Low |

---

## 🚀 Proposed MVP

### Feature: Early Late-Order Detection

The system identifies orders that are likely to become late before the
promised delivery time is exceeded.

### How it works

Order placed
→ Monitor preparation time
→ Monitor partner assignment
→ Monitor travel progress
→ Detect delay risk
→ Notify relevant stakeholders
→ Take corrective action

---

## 📱 Customer Experience

When the system detects a potential delay:

**Before:**

> Order is delayed.

**Proposed:**

> ⚠️ Your order may arrive later than expected due to delivery conditions.
> Updated ETA: 8:45 PM.

The goal is to provide customers with **early, transparent and useful
information** instead of surprising them with a late delivery.

---

## 📊 Product Metrics

### North Star / Primary Metric

**On-Time Delivery Rate**

Percentage of orders delivered within the promised delivery window.

### Supporting Metrics

- Average Delivery Delay
- Percentage of Late Orders
- ETA Accuracy
- Restaurant Preparation Time
- Delivery Partner Assignment Time
- Customer Cancellation Rate
- Customer Support Complaints
- Repeat Order Rate

---

## 🧪 Experimentation

### Hypothesis

If customers receive accurate early delay notifications, customer
frustration and cancellations may decrease.

### A/B Test

**Control Group**
- Existing order tracking experience

**Experiment Group**
- Early delay detection + updated ETA notification

### Success Criteria

The experiment would be considered successful if the experiment group shows:

- Lower cancellation rate
- Lower support complaints
- Better customer satisfaction
- No significant negative impact on repeat orders

---

## ⚠️ Trade-offs & Risks

### Risk 1: False Delay Alerts

Incorrect predictions may unnecessarily worry customers.

**Mitigation:**  
Only trigger alerts when the delay probability crosses a defined threshold.

### Risk 2: Too Many Notifications

Frequent notifications can create notification fatigue.

**Mitigation:**  
Send only meaningful updates when the ETA changes significantly.

### Risk 3: Operational Complexity

Some solutions may require changes across restaurant and delivery
operations.

**Mitigation:**  
Start with a small MVP and gradually expand.

---

## 🗺️ Future Improvements

After validating the MVP, the product could explore:

- ML-based ETA prediction
- Restaurant preparation-time prediction
- Dynamic delivery-partner allocation
- Traffic-aware routing
- Personalized ETA communication
- Automated compensation for eligible delays

---

## 📈 Expected Impact

The proposed solution aims to:

- Improve delivery reliability
- Reduce unexpected late orders
- Improve customer trust
- Reduce cancellations
- Reduce customer support complaints
- Help operations identify bottlenecks earlier

---

## 🧩 Product Thinking Demonstrated

This case study demonstrates my approach to:

- Problem discovery
- User-focused thinking
- Root cause analysis
- Stakeholder identification
- Feature prioritization
- MVP definition
- Product metrics
- Experimentation
- Trade-off analysis
- Data-driven decision making

---

## 🛠️ Skills Applied

**Product Management**
- Product Thinking
- Problem Solving
- Prioritization
- MVP Planning
- Product Metrics
- Experiment Design
- Stakeholder Management

**Analytical Skills**
- Root Cause Analysis
- Funnel Thinking
- Metric Definition
- Hypothesis Formation

---

## 📂 Case Study Structure

```text
food-delivery-late-order-apm-case-study/
│
├── README.md
│
├── research/
│   └── problem-research.md
│
├── analysis/
│   └── root-cause-analysis.md
│
├── prioritization/
│   └── feature-prioritization.md
│
├── solution/
│   └── mvp-proposal.md
│
├── metrics/
│   └── product-metrics.md
│
└── experiments/
    └── ab-test-plan.md
