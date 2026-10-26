# 🦷 Dental Clinic Business Analytics | Google Sheets + Google Slides

Analysis of a simulated dental clinic over its first 12 months: rebuilding the financial report, finding why the clinic is unprofitable, evaluating doctors and forecasting the next quarter (Q5).

- 📊 **Analysis:** [Google Sheets](https://docs.google.com/spreadsheets/d/1HirgSGmQyDkyut0Tbyt33bY2YiRJNPQ64lCFjXsM1eM/edit?usp=sharing)
- 📈 **Dashboard:** [Google Sheets](https://docs.google.com/spreadsheets/d/1nBxaIzVmdQDiFV2SsiFZGGmtnVKa6qiqTSpfbhRSnW0/edit?usp=sharing)
- 🎞️ **Presentation:** [Google Slides](https://docs.google.com/presentation/d/1qiJ3AAICLfp9Nr5oGQCsy61osObyi1qwvCFCDVj3DdY/edit?usp=sharing) · [PDF version](Dental_Clinic_Project_Hetman.pdf)

---

## 🎯 Goal

Understand the clinic's operating results, identify weak spots and propose a strategy to maximize profitability in Q5.

## 🧰 Tools

| Tool | Used for |
|---|---|
| **Google Sheets** | Rebuilding the REPORT sheet (attraction, retention, monetization, NPS, expenses, profit), formulas (e.g. `COUNTIFS`, `SUMIFS`, `AVERAGEIF`), pivot tables, charts, forecast scenarios |
| **Google Slides** | Custom theme, dashboard slide, charts from Sheets, gauge charts from add-ons, table, speaker notes |

## 🏥 Business Context

| Quarter | Doctors | Strategy | Revenue | Cumulative profit |
|---|---|---|---|---|
| Q1 | 2 | Active marketing | €137,265 | −€49,485 |
| Q2 | 2 | First-visit discount | €152,795 | −€59,363 |
| Q3 | 3 | Referral program | €230,899 | −€70,715 |
| Q4 | 4 | No discount | €300,757 | −€70,558 |

## 🔍 Key Findings

- The clinic was **in the red for the whole year: cumulative profit −€70,558**; only 2 of 12 months were profitable (M6 +€187, M12 +€3,382).
- Revenue grew from **€19,798 (M1) to €106,309 (M12)** and visits from 78 to 452, but expenses grew just as fast (~€103K/month at the end), leaving a margin of about 3%.
- **Main cost drivers:** high marketing spend at the start, then growth of staff and service costs as the clinic scaled from 2 to 4 doctors.
- The first-visit discount lowered the average check (**€254 → €202**) and cut revenue by 16.6% in M4.

### 👩‍⚕️ Doctor evaluation

| Doctor | Active | NPS | Retained / Lost | Profit per visit | Material cost | Verdict |
|---|---|---|---|---|---|---|
| **DOCTOR_013** | 12 months | 59% | 89% / 29% | €135 | 37% | 🥇 Loyalty leader – scale |
| **DOCTOR_010** | 3 months | 50% | 36% / 83% | €161 | 32% | 🥈 Highest profit, retention risk |
| **DOCTOR_018** | 12 months | 33% | 82% / 34% | €153 | 31% | ⚠️ Unstable – monitor |
| **DOCTOR_014** | 6 months | 30% | 54% / 60% | €148 | 38% | ❌ Weakest link |

## ⚠️ Weak Spots

- **Thin margin:** costs grow with every new doctor, so extra revenue barely turns into profit.
- **Poor retention and loyalty** for DOCTOR_014 (NPS 30%, 60% lost) and DOCTOR_010 (83% lost – but only 3 months of data, so many first-time patients may simply not have needed a repeat visit yet).
- **Material costs** are highest for DOCTOR_014 (38%) and DOCTOR_013 (37%) vs 31–32% for the others.
- **Discounts** reduce the average check and did not fix profitability.

## 💡 Recommendations

**For doctors**
- **DOCTOR_013:** give more patients and use as the training standard (and reduce material costs).
- **DOCTOR_010:** train service and communication, limit first-time patients.
- **DOCTOR_018:** work on quality and service, do not scale until it improves, monitor reviews.
- **DOCTOR_014:** urgent training and lower workload; replace if there is no improvement.

**For the business (Q5)**
- Raise the average check by about 5% (€235 → €247) instead of using discounts.
- Keep visits at or above ~465 per month by improving retention rather than buying new clients.
- Bring material costs closer to the 31–32% benchmark.
- Do not add more doctors until quality and retention issues are fixed.

## 📈 Q5 Forecast

| Scenario | Assumptions | Monthly profit | Result |
|---|---|---|---|
| **Optimistic** | 465 visits, ACV +5% (€247), revenue €114,739, expenses €102,927 | ≈ €11.8K | Cumulative balance turns positive |
| **Pessimistic** | 452 visits, no ACV growth, revenue €106,309 | €3,382 | Balance improves slowly and stays negative within the forecast period |

## 👤 Author

**Viktoriia Hetman**
[GitHub](https://github.com/hetman07) · [LinkedIn](https://www.linkedin.com/in/viktoriia-hetman-1376631b6)
