# Analyst Pre-Interview Task – Kent Police  

**Task:** “Is there an Anti-Social Behaviour (ASB) problem in Kent and, if so, what would you recommend to Kent Community Safety Partners to prevent ASB?”  
**Submitted to:** Kent Police & Kent Community Safety Team  
**Position:** Analyst (North Division) – Interview Task  
**Date:** June 2025  
**Outcome:** Not successful in role, but **positively reviewed by the analytics team**.  

---

## 📘 Project Overview  
This pre-interview project analysed whether **Anti-Social Behaviour (ASB)** constitutes a problem in Kent.  
Using **Police.UK open data (May 2022 – Apr 2025)** and **ONS population estimates**, I evaluated ASB trends across time and geography, comparing Kent’s performance to national levels.  

The analysis approached the idea of a “problem” in a **multi-dimensional way**:  
- **Temporal trends:** Is ASB worsening over time?  
- **National comparison:** Is Kent overrepresented relative to its population?  
- **Geographic disparities:** Are specific districts hotspots?  

The task also showcased **domain immersion**, combining statistical analysis with practical, community-driven insights (including boxing as a diversionary strategy).  

---

## 🔍 Methodology  
- **Data collection:** Police.UK monthly CSVs on ASB (35 months); ONS mid-2023 population estimates.  
- **Processing:** Cleaned and aggregated in Python (`Kent_ASB.ipynb`).  
- **Analysis:**  
  - Time-series of monthly ASB incidents.  
  - Seasonal decomposition (summer peaks, winter troughs).  
  - One-sample **t-test** (Kent’s share of UK ASB vs population share).  
  - One-proportion **z-tests** (ASB proportions in 2023, 2024, and combined).  
  - District-level comparisons (raw counts vs per-1,000 residents).  

---

## 📊 Key Findings  
- **Seasonal patterns:** Summer peaks (July–August >3,000 incidents) and winter troughs (~1,500).  
- **Trend:** No sustained rise, but ASB has plateaued at a **moderately high level**.  
- **National comparison:** Kent consistently **overrepresented** in ASB, with share of incidents (~2.88%) significantly exceeding population share (~2.78%, p < 0.05).  
- **Geographic hotspots:** Gravesham, Thanet, Swale, and Medway exceeded 50 incidents per 1,000 residents.  
- **Volatility:** Recent upticks in March–April 2025 warn against assuming long-term decline.  

---

## ⚠️ Limitations  
- Police.UK data is **based on recorded incidents**, which may underreport actual ASB due to variation in reporting behaviour and recording practices.
- No data/profile on **offender demographics** (e.g. age, gender, ethnicity, education, employment); cannot confirm whether ASB comes from the youth.
- **Population denominators** use mid-2023 estimates, not dynamically updated yearly figures.  
- Analysis relied on **observational data only**, with no experimental evidence of causal drivers.  
- Hotspot identification highlights relative concentrations but **does not explain underlying causes**.  

---

## 🛠️ Recommendations  
- **Target hotspots:** Focus resources on Gravesham, Thanet, Swale, and Medway.  
- **Seasonal focus:** Scale up interventions during summer peaks (extra patrols, youth engagement).  
- **Community partnerships:** Expand **structured activities like boxing clubs** as diversionary strategies.  
  - Backed by initiatives such as **Dyfed-Powys Police’s INTACT programme** and other police-funded boxing projects, which showed reductions in reoffending and significant cost savings.  
- **Sustained monitoring:** Keep policy adaptive to fluctuations and resistant to complacency.  

---

## 📂 Files  
- 📄 [Written Report (PDF)](https://github.com/shuja-ali298/kent_police/blob/main/asb_kent_police_subhan_ali.pdf)  
- 📘 [Python Notebook – Analysis Code](https://github.com/shuja-ali298/kent_police/blob/main/Kent_ASB.ipynb)  

---

## 📌 Skills Demonstrated  
- Time-series & hypothesis testing (t-tests, z-tests).  
- Spatial & comparative analysis (Kent vs national).  
- Identifying **data limitations**, ensuring cautious interpretation and productive, sensitive implementation. 
- Translating statistical insight into **actionable recommendations**.  
- Domain immersion: linking analysis with real-world prevention strategies (e.g., boxing as early intervention).  
