# 🏨 Hotel Booking Data Analytics Project

**Comprehensive Python analysis of hotel booking data focusing on booking behavior, cancellations, revenue, and customer segmentation.**

## 📊 Project Overview

This project analyzes real-world hotel booking data to uncover patterns in guest behavior, seasonal trends, cancellation drivers, segmentation, revenue and ADR (Average Daily Rate), and operational efficiency. Insights help hotels make data-driven decisions about pricing, marketing, staffing, inventory, and guest experience.

---

## 📂 Dataset

- **Size:** 40,000+ records  
- **Key fields:**
   - Booking dates & lead time
   - Hotel type, customer type
   - Market segment, distribution channel
   - ADR (Average Daily Rate)
   - Room type
   - Cancellation flag, previous cancellations
   - Special requests count
   - Repeat guest indicator

---

## 🛠️ Tools & Technologies

- Python
- pandas, NumPy
- matplotlib, seaborn
- Jupyter Notebook

---

## 🔧 Data Preparation

- Removed duplicates
- Filled missing values using mode
- Converted date columns for analysis
- Encoded categorical variables
- Feature engineered: lead time categories, risk score indicators

---

## 📈 Key Analyses & Insights

### 1️⃣ Booking Pattern Analysis

- Demand peaks during July–August
- Longer lead times = slightly higher cancellation chance
- Seasonal and weekly fluctuations are clear

### 2️⃣ Cancellation Analysis

- Major drivers: Deposit type, Customer type, Lead time, Previous cancellations, Special requests
- No-deposit bookings → much higher cancellations
- Rule-based risk model identifies high-risk bookings

### 3️⃣ Customer Segmentation

- Transient guests (OTAs) = largest volume; highly price-sensitive
- Corporate/Contract guests = stable revenue
