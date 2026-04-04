# GigShield AI 🛡️
### AI-Powered Parametric Insurance for India’s Gig Economy

**Problem Statement:** Safeguarding platform-based delivery partners against income loss caused by external disruptions (weather, pollution, social events) using parametric automation and weekly pricing.

---

## 1. Strategy & Persona
**Target Persona:** Food Delivery Partners (e.g., Swiggy, Zomato) operating in Tier 1 and Tier 2 cities in India.
- **Why this persona?** They are highly exposed to weather (rain, heatwaves) and environmental (pollution) disruptions that directly impact their ability to complete deliveries and earn incentives.
- **Workflow:** 
    1. **Onboarding:** One-click registration via Platform ID (Swiggy/Zomato).
    2. **Risk Profiling:** AI-driven assessment based on the worker's historical delivery zones.
    3. **Policy Selection:** Simple weekly premium plans.
    4. **Monitoring:** Real-time data feed (Weather/Traffic/Events).
    5. **Automated Payouts:** Instant claim initiation when parametric triggers are met.

## 2. Weekly Premium Model
Gig workers operate on weekly payout cycles. Our model aligns with this:
- **Pricing:** Dynamic weekly premiums (₹50 - ₹150) based on localized risk factors.
- **Coverage:** Replaces pro-rated hourly earnings lost during the disruption period.
- **Justification:** Avoids long-term financial commitments and provides immediate flexibility for a transient workforce.

## 3. Parametric Triggers
Our platform uses objective, verifiable data to trigger claims:
- **Environmental:**
    - **Heavy Rain:** Rainfall > 10mm/hr in the operating zone.
    - **Heatwave:** Temperature > 45°C for 3+ consecutive hours.
    - **Air Quality (AQI):** AQI > 400 (Severe category).
- **Social:**
    - **Local Strikes/Curfews:** Verified via local government APIs or news scraping.

## 4. AI/ML Integration
- **Dynamic Premium Calculation:** Regressive models to predict weekly risk based on historical disruption patterns.
- **Fraud Detection:** 
    - **GPS Spoofing Check:** Validation of the worker's location during the trigger period.
    - **Anomaly Detection:** Cross-referencing claim volume with platform-wide delivery delays.

## 5. Tech Stack
- **Frontend:** React + TypeScript + Vite (Fast, responsive, and mobile-friendly).
- **Styling:** Vanilla CSS / Tailwind CSS (Premium, dark-mode focused UI).
- **State Management:** React Context / Zustand.
- **Data Visuals:** Lucide-react icons, Leaflet for zone mapping.
- **Simulated APIs:** Mocked weather and platform backend.

## 6. Development Plan
- **Phase 1:** Ideation, Persona Research, and Initial Prototype (Current).
- **Phase 2:** Automated Triggers, Dynamic Pricing, and Zero-Touch Claim UI.
- **Phase 3:** Fraud Detection, Mock Payment Integration, and Admin Dashboard.

---
*Developed for Guidewire DEVTrails 2026*
