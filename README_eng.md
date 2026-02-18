# Product Funnel Analysis (SaaS Freemium, Synthetic Data)

## About the Project

This project models user behavior in a digital product funnel:

visit → signup → trial_start → purchase  

The dataset is fully synthetic and generated programmatically.  

The main goal of the project is to practice and demonstrate:

- funnel construction  
- user drop-off analysis  
- first-touch attribution modeling  
- basic unit economics  
- working with event-based logs  

---

## What Was Simulated

Scenario: A marketing campaign for a SaaS product with free registration and trial.

Each user:

- first lands on the website (visit)  
- may register (signup)  
- may start a trial (trial_start)  
- may complete a purchase (purchase)  

Additionally:

- users may perform repeat visits  
- events strictly follow funnel logic (no skipped stages)  
- each user is assigned a first-touch source (ads, organic, email, referral)

---

## What Was Done

### 1. Data Generation

- simulated realistic user journey logic  
- defined transition probabilities between funnel stages  
- added repeat visits  
- generated revenue for purchases  
- validated data consistency and integrity  

---

### 2. Event Analysis

- calculated daily event volume  
- verified distribution of event types  
- visualized campaign activity dynamics  

---

### 3. Funnel Analysis

- calculated unique users at each funnel stage  
- computed step-by-step conversions and drop-offs  
- built a waterfall diagram of user losses  
- identified the stage with the highest relative drop  

---

### 4. Channel Analysis (First-Touch Attribution)

Users were attributed to the source of their first visit.

For each channel, the following metrics were calculated:

- number of acquired users  
- conversion to purchase  
- total revenue  
- ARPU (average revenue per user)  
- ARPPU (average revenue per paying user)

This allows comparison of traffic quality across acquisition channels.

---

## Skills Demonstrated

- working with event-based datasets  
- product funnel construction  
- conversion analysis  
- first-touch attribution modeling  
- basic monetization metrics  
- data visualization  

---

## Tech Stack

Python  
Pandas  
NumPy  
Matplotlib
