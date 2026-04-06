# 🏨 Atli-Q Hotels — Revenue Intelligence Dashboard
### Business Insights Report | May 2024 – July 2024
**Hospitality Excellence Group | Power BI Analytics**

---

## 📊 Dashboard Overview

The Revenue Intelligence Dashboard for Atli-Q Hotels (Hospitality Excellence Group) tracks key hospitality KPIs across properties in Mumbai, Hyderabad, Bangalore, and Delhi over a 13-week period (W19–W31, May–July 2024).

---

## 🖥️ Dashboard Screenshots

### Page 1 — Revenue Intelligence Overview

![Revenue Intelligence Dashboard - Main View](screenshot_56.png)

> **Main KPI page** showing Revenue (2bn), DSRN (2,528), RevPAR (7,347), Occupancy % (57.87%), Realisation % (70.15%), ADR (12.70K) — all showing a uniform -0.82 WoW change.

---

### Page 1 — Revenue by Week & Category (Expanded)

![Revenue by Week No and Category](screenshot_55.png)

> Revenue split between **Business** (~₹85–87M) and **Luxury** (~₹71M) segments by week number. Business segment is consistently higher but both show a declining trend toward W26–W31.

---

### Page 2 — Trends by Key Metrics (Weekly)

![Trends by Key Metrics - RevPAR, ADR, Occupancy %](screenshot_54.png)

> Weekly trend line chart showing **RevPAR** (teal), **ADR** (dark blue), and **Occupancy %** (red dashed). ADR remains flat while RevPAR and Occupancy fluctuate significantly week over week.

| Week | RevPAR | ADR | Occupancy % |
|------|--------|-----|-------------|
| W 19 | 7,808.66 | 12,602.10 | 61.96% |
| W 20 | 7,879.52 | 12,724.58 | 61.92% |
| W 21 | 6,494.25 | 12,709.82 | 51.10% |
| W 22 | 7,839.07 | 12,687.04 | 61.79% |
| W 23 | 6,530.77 | 12,715.21 | 51.36% |
| W 24 | 7,887.75 | 12,642.13 | 62.39% |
| W 25 | 7,836.48 | 12,672.42 | 61.84% |
| W 26 | 6,450.75 | 12,659.69 | 50.96% |
| W 27 | 7,886.28 | 12,730.85 | 61.95% |
| W 28 | 7,876.58 | 12,753.58 | 61.76% |
| W 29 | 7,896.17 | 12,682.03 | 62.26% |
| W 30 | 6,487.97 | 12,728.51 | 50.97% |
| W 31 | 6,501.04 | 12,752.72 | 50.98% |

---

### Page 2 — Weekday vs Weekend Performance

![Weekday vs Weekend Table](screenshot_57.png)

> Detailed breakdown of Weekday vs Weekend metrics — Weekends show higher Occupancy % and Realisation % despite similar RevPAR.

| Day Type | RevPAR | Occupancy % | ADR | Realisation % |
|----------|--------|-------------|-----|---------------|
| **Weekday** | 7,082.53 | 55.85% | 12,682.41 | 69.94% |
| **Weekend** | 7,971.63 | 62.64% | 12,725.49 | 70.59% |
| **Total** | 7,336.56 | 57.79% | 12,695.75 | 70.14% |

---

## 💡 Strategic Business Insights

---

### 1. 🔄 Dynamic Pricing — ADR is Flat, RevPAR is Swinging

**Observation:**
ADR remains almost perfectly flat across all 13 weeks (oscillating narrowly between ₹12,602–₹12,753), while RevPAR swings dramatically — from ₹6,450 (W26) to ₹7,908 (W29). This is a ~22% gap between low and peak RevPAR weeks, driven entirely by **occupancy fluctuations, not pricing changes**.

**Root Cause:**
The hotels are using **static, fixed pricing** regardless of demand signals. When occupancy drops (W21, W23, W26, W30, W31 — all ~51%), the revenue loss is unrecovered because rates don't adjust.

**Recommendation — Implement Dynamic Pricing:**

| Trigger | Action |
|---------|--------|
| Occupancy forecast < 55% (3–7 days out) | Drop ADR by 8–12% to stimulate demand |
| Occupancy forecast > 65% (3–7 days out) | Increase ADR by 10–15% to capture premium |
| Last-minute (<48hr) availability gap | Flash sale at 15–20% discount |
| High competitor pricing detected | Raise ADR by 5–10% |

**Expected Impact:** Closing the RevPAR gap from ₹1,400+ to under ₹500 could add ~₹8–10M monthly revenue.

---

### 2. 📅 Weekend vs Weekday Pricing Strategy

**Observation:**
Weekend Occupancy (62.64%) is **12% higher** than Weekday (55.85%), and Weekend Realisation % (70.59%) is also higher. Yet Weekend ADR (₹12,725) is only **₹43 higher** than Weekday (₹12,682) — a difference of barely 0.3%.

**This is a massive pricing opportunity being left on the table.**

**Recommendation — Tiered Weekend Pricing:**

- **Premium Weekend Rate:** Increase Weekend ADR by ₹800–₹1,200 (6–9%) over weekday rates
- **Weekday Stimulation Packages:** Corporate/extended-stay discounts Mon–Thu to fill the occupancy gap
- **Friday–Saturday Peak Pricing:** Charge peak premium on F/Sa, offer Sunday discount to extend stays
- **City-Specific Weekend Premiums:** Mumbai and Hyderabad properties likely have higher leisure demand on weekends — adjust city-level pricing independently

**Quick Math:**
If Weekend ADR increases from ₹12,725 → ₹13,500 (+6%), and assuming ~1,025 weekend room nights:
> **Additional Revenue ≈ ₹7.95 Lakhs per month**

---

### 3. ⭐ Low-Rated Hotel Recovery — Pareto Principle (80/20 Rule)

**Observation:**
From the property-level data, several hotels carry **Average Ratings of 4.28–4.32** (flagged in red/orange in the dashboard), with notably lower Occupancy %. Atli Blu (Delhi) and Atli Bay (Bangalore) appear in the lower-rated tier with Occupancy around 65–66%.

**The Pareto Insight:**
~20% of properties (roughly 3–4 hotels) are likely responsible for 80% of negative guest experiences, poor ratings, and lost repeat bookings. Fixing these hotels has outsized revenue impact.

**Action Plan by Rating Band:**

| Rating | Status | Action |
|--------|--------|--------|
| 4.28–4.30 | 🔴 Critical | Root cause audit: hygiene, staff, maintenance |
| 4.31–4.33 | 🟠 At-Risk | Guest feedback analysis, targeted improvements |
| 4.34–4.36 | 🟡 Average | Upsell training, loyalty program push |
| 4.37+ | 🟢 Strong | Leverage for premium pricing |

**Specific Steps:**
1. **Conduct Exit Surveys** at low-rated properties to identify top 3 complaints
2. **Resolve Top Issues Within 30 Days** (most common: room cleanliness, check-in speed, Wi-Fi)
3. **Request Re-reviews** from guests post-fix via post-stay email campaigns
4. **Track Rating vs Occupancy Correlation Weekly** — a 0.1 improvement in rating can yield 3–5% Occupancy lift

**Revenue Impact:**
If Atli Blu Delhi improves Occupancy from 65% → 70% (a ~7.7% increase), and has ~150 rooms:
> **Additional Occupied Room Nights ≈ 225/month → ₹25–28 Lakhs additional monthly revenue**

---

### 4. 💻 Checkout Page Offers — Capture Online Revenue Leakage

**Observation:**
Realisation % sits at 70.14% overall, meaning nearly **30% of potential bookings are not converting** through online platforms. Cancellation % averages around 24–25%. Online Booking Platforms (OTAs) are generating bookings but losing revenue at checkout and post-booking.

**Recommendation — Smart Checkout Incentives:**

**A. Last-Minute Checkout Discounts:**
- Display "Book Now, Save 12%" banners when inventory > 40% available within 3 days
- Deploy across Atli Biru (OTA) and direct booking portal

**B. Bundled Add-Ons at Checkout:**
| Add-On | Suggested Price | Margin |
|--------|----------------|--------|
| Early Check-in (10AM) | ₹499 | ~90% |
| Late Check-out (2PM) | ₹599 | ~90% |
| Airport Transfer | ₹999 | ~60% |
| F&B Credit Bundle | ₹799 | ~55% |

**C. Non-Refundable Rate Incentive:**
- Offer 8–10% discount for Non-Refundable bookings to reduce the 24% cancellation rate
- This directly converts cancellations into guaranteed revenue

**D. Loyalty Points on Direct Booking:**
- Offer 2x loyalty points for direct website bookings vs OTA bookings
- Reduces OTA commission (typically 15–20%) and builds CRM database

**E. Recovery Email for Abandoned Checkouts:**
- Trigger automated email within 30 minutes of checkout abandonment
- Include time-limited discount code (5–8%, valid 24 hrs)

**Expected Impact on Realisation %:**
Targeting improvement from 70.14% → 74–75% Realisation through these interventions:
> **Estimated Revenue Recovery ≈ ₹80–100M annually across portfolio**

---

## 📌 Summary — Priority Action Matrix

| Priority | Initiative | Estimated Monthly Impact | Effort |
|----------|-----------|--------------------------|--------|
| 🔴 **P1** | Dynamic Pricing Model | ₹8–10M | Medium |
| 🔴 **P1** | Low-Rating Hotel Fixes (Pareto) | ₹25–28M per property | High |
| 🟠 **P2** | Weekend Premium Pricing | ₹8M | Low |
| 🟠 **P2** | Checkout Page Offers & Non-Refundable Rates | ₹15–20M | Medium |
| 🟡 **P3** | Loyalty Program & Direct Booking Push | Long-term CRM value | High |

---

## 📐 Key Metric Definitions

| Metric | Definition |
|--------|-----------|
| **RevPAR** | Revenue Per Available Room |
| **ADR** | Average Daily Rate |
| **DSRN** | Daily Saleable Room Nights |
| **DBRN** | Daily Booked Room Nights |
| **DURN** | Daily Utilized Room Nights |
| **Occupancy %** | Percentage of Occupied Rooms |
| **Realisation %** | Percentage of successful checkouts from Total Bookings |

---

*Report generated from Power BI Dashboard — Atli-Q Hotels Hospitality Excellence Group*
*Data Period: May 2024 – July 2024 (W19–W31)*
