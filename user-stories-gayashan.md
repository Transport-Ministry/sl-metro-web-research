# Metro System Research & Brainstorming
**Researcher:** Enuka Gayashan Balasooriya  
**Date:** 2026-03-10  
**Branch:** `doc/gayashan-research`

---

## 1. Global Benchmarking
I reviewed three major transit systems to identify the "Golden Standard" for the Sri Lankan context.

| # | Country | System Name | Key UX Strength |
|---|---------|-------------|-----------------|
| 1 | Singapore | [SimplyGo](https://www.simplygo.com.sg/) | **Minimalism:** Fare-first design that isn't overwhelming. |
| 2 | London | [TfL](https://tfl.gov.uk) | **Transparency:** Real-time disruption alerts and status. |
| 3 | Tokyo | [Tokyo Metro](https://www.tokyometro.jp/en) | **Granularity:** Deep station-level info and landmark mapping. |

---

## 2. User Stories & Requirements
*Refining the system based on local ground realities and the "No-Surprise" travel model.*

### 🟦 1. The Daily Passenger (Commuter)
**Focus:** Speed, clarity, and stopping the "change money" arguments.

* **Real-time Tracking (High Priority):** As a passenger, I want to see exactly where my bus or train is on a live map so I don't have to stand at the halt for an hour wondering if it's coming.
* **Fare Calculator (High Priority):** As a passenger, I want to enter my start and end stages to see the exact price (e.g., Rs. 34.00) before I board, so I can have the exact change ready.
* **Language Options (High Priority):** As a Sri Lankan user, I want to switch the entire site between Sinhala, Tamil, and English instantly so I don't get confused by technical terms.
* **Station Guide (Medium Priority):** As a passenger, I want to know if a station has a clean washroom, an ATM, or a nearby landmark so I can plan my stops better.
* **Delay Alerts (Medium Priority):** As a passenger, I want a quick "Alerts" section on the homepage to see if a specific route is blocked by traffic or a breakdown.

### 🟩 2. The System Admin (The Controller)
**Focus:** Keeping data accurate and the fleet running smoothly.

* **Fare Management (High Priority):** As an admin, I need a simple dashboard to update the price-per-stage whenever the government changes fuel prices, so the website stays accurate.
* **Route Control (High Priority):** As an admin, I want to add new routes or temporary "shuttle" paths for special events (like Poya days) without touching the code.
* **Driver Assignment (Medium Priority):** As an admin, I need to see which driver/conductor is logged into which vehicle so I can monitor who is actually on the road.
* **Passenger Feedback (Low Priority):** As an admin, I want to see a log of complaints or suggestions sent by users so we can improve specific bus routes.

### 🟧 3. The Driver or Conductor (The Provider)
**Focus:** Providing data without it being a distraction.

* **Trip Toggle (High Priority):** As a driver, I want a big "Start Trip" and "End Trip" button on my phone so my location only shows on the public map when I am actually working.
* **Incident Reporting (Medium Priority):** As a conductor, I want a 2-click way to report a "Breakdown" or "Heavy Traffic" so that passengers waiting at the next halts are automatically notified.

### 🟨 4. The Tourist (The Visitor)
**Focus:** Making the system "tourist-friendly" like Japan’s Metro.

* **Digital Passes (Medium Priority):** As a tourist, I want to see how to get a "Day Pass" or "Weekly Card" so I don't have to figure out local cash every single time I travel.
* **Landmark Mapping (Medium Priority):** As a tourist, I want the system to suggest which station I should get down at to reach popular places like Galle Face or Sigiriya.

---

## 3. UI/UX Observations for Sri Lanka
* **Color Scheme:** Use consistent branding (Saffron/Maroon/Teal) to reflect national identity.
* **Mobile-First:** 90% of users will access this via phone while at a bus halt.
* **Low Data Mode:** The site should be lightweight to accommodate slow mobile connections.

---

## 4. Personal Opinion
I think Sri Lanka's metro website should prioritize **simplicity and mobile-first design**. The Singapore model is the best reference because it balances simplicity with useful features. The most critical feature for us is **multilingual support** to ensure inclusivity for all citizens.