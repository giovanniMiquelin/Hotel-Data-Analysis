# Hotel-Data-Analysis
Hotel Data Analysis Project



# Securing the Stay: Unpacking Hotel Cancellations

## 📊 Project Overview

Hotel cancellations can significantly impact revenue forecasting, capacity planning, and overall hotel operations. This project analyzes hotel booking data to identify the key factors associated with reservation cancellations and develop data-driven strategies to improve guest retention.

The analysis focuses on booking behavior, customer engagement, lead time, market segments, deposit types, and previous customer history to understand what distinguishes canceled bookings from completed stays.

## 🎯 Objectives

* Identify the main factors associated with hotel cancellations.
* Compare canceled and non-canceled bookings.
* Analyze cancellation patterns across hotel types and market segments.
* Examine the relationship between customer engagement and cancellations.
* Develop practical strategies to reduce cancellation risk.

## 📁 Dataset

The dataset contains **119,390 hotel booking records** across two hotel categories:

| Hotel Type    |    Bookings |    Share |
| ------------- | ----------: | -------: |
| City Hotels   |      79,330 |     ~66% |
| Resort Hotels |      40,060 |     ~34% |
| **Total**     | **119,390** | **100%** |

The dataset contains **32 features** covering booking timing, guest information, market segments, and financial characteristics. The overall cancellation rate in the dataset was **37.0%**, with an Average Daily Rate (ADR) of **$101.83**.

## 🔎 Key Variables

Some of the primary variables analyzed include:

* **Lead Time** — Number of days between booking and arrival.
* **Is Canceled** — Indicates whether a reservation was canceled.
* **Market Segment** — Describes how the booking was acquired.
* **Deposit Type** — Indicates the type of financial commitment associated with the reservation.
* **Average Daily Rate (ADR)** — Average room revenue per night.

## 📈 Key Findings

### 1. Lead Time Is a Major Cancellation Indicator

Bookings made far in advance showed substantially higher cancellation rates.

* **0–7 day lead time:** 9.63% cancellation rate
* **301–365 day lead time:** 69.81% cancellation rate

This suggests that reservations with very long lead times represent a significantly different risk profile from short-notice bookings.

### 2. Market Segment Matters

The **Groups** market segment had the highest cancellation rate in the analysis:

* **Groups:** 61.06% cancellation rate
* Average lead time: **187 days**

This makes the relationship between group bookings, long lead times, and cancellations an important area for further investigation.

### 3. Customer Engagement Is Associated With Lower Cancellation Rates

Customer interaction with a reservation showed a strong relationship with completed stays.

Bookings with:

* **0 special requests:** 47.7% cancellation rate
* **1 special request:** 22.0% cancellation rate

Similarly:

* **0 booking changes:** 41.0% cancellation rate
* **At least 1 change:** 14.0% cancellation rate

These patterns suggest that more engaged guests were substantially more likely to complete their stays.

### 4. Previous Stays Are Associated With Higher Retention

Returning guests showed higher stay-completion rates than first-time guests:

* **1 prior stay:** 94.9% stay completion
* **First-time guests:** 62.0% stay completion

This indicates that customer history may be useful when identifying cancellation risk and developing retention strategies.

### 5. Pricing and Guest Composition Had Limited Impact

Within the available data, **Average Daily Rate (ADR)** and family size showed relatively little difference between canceled and non-canceled bookings compared with variables such as lead time and customer engagement.

## 💡 Recommendations

Based on the analysis, the project proposes four strategic approaches:

### 1. Prioritize Shorter Booking Windows

Encourage shorter lead-time bookings through targeted promotions and use automated reminders for reservations made far in advance.

### 2. Increase Customer Engagement

Encourage guests to interact with their reservations by:

* Selecting room preferences
* Adding special requests
* Updating booking information
* Providing relevant pre-arrival information

The goal is to turn passive reservations into more committed bookings.

### 3. Leverage Loyalty and Previous Stays

Use loyalty-oriented strategies to encourage repeat customers and strengthen brand trust. Potential approaches include rewards, upgrades, or benefits for returning guests.

### 4. Investigate Group and Non-Refundable Bookings

The unusually high cancellation rate associated with the **Groups** segment and non-refundable bookings requires additional research before changing policies. The project recommends examining the underlying structure of these bookings and their relationship with deposit policies.

## 🧠 Main Takeaway

> **Commitment and active engagement are key to minimizing cancellations.**

The analysis suggests that hotels may benefit from focusing not only on predicting which customers will cancel, but also on identifying ways to increase engagement after a reservation is made.

Long lead times, previous cancellation behavior, market segment, booking changes, special requests, and customer history provide useful signals for understanding cancellation behavior.

## 🛠️ Skills Demonstrated

* Data Analysis
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Pattern Identification
* Business Intelligence
* Customer Behavior Analysis
* Hospitality Analytics
* Data-Driven Decision Making
* Business Recommendations

## 👥 Team

* Wonder Kahozi
* Suni Davis
* Giovanni Miquelin

## 📑 Presentation

**Project:** *Securing the Stay: Unpacking Hotel Cancellations*

The accompanying presentation contains the full analysis, visualizations, findings, and recommendations.

## 📚 Sources

* Hotel booking dataset used for the analysis.
* Supporting research and project presentation.
* Additional source material referenced in the project presentation.
