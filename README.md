# ✈️ Flight Operations Performance Dashboard — Power BI

An interactive Power BI dashboard designed to monitor and analyse flight operations across major airlines. The dashboard provides real-time visibility into flight delays, risk classifications, airline performance, and ticket pricing trends.

---

## 📸 Dashboard Preview

![Flight Operations Dashboard](dashboard_screenshot.png)

---

## 📊 Key Metrics (KPI Cards)

| Metric | Description |
|---|---|
| **Total Flight Fact** | Total number of flights tracked |
| **High Risk Flights Fact** | Count of flights classified as high risk |
| **Delayed Flight Fact** | Total number of delayed flights |
| **Average Delay Fact** | Average delay duration in minutes |

---

## 📈 Visuals Included

| Visual | Description |
|---|---|
| **Donut Chart** | Total flights by Delay Risk category (High / Medium / Low / No Risk) |
| **Bar Chart** | Total flights by Airline Name |
| **Scatter Plot** | Ticket Price vs Delay Minutes by Year and Flight Status |
| **KPI Cards** | Summary metrics at a glance |

---

## 🔍 Filters & Slicers

- **Airline Name** — Air India, British Airways, Emirates, IndiGo, Qatar Airways, Singapore Airlines, SpiceJet, Vistara
- **Destination** — Filter by destination country/city
- **Delay Risk** — High Risk / Low Risk / Medium Risk / No Risk

---

## 🗃️ Data Fields Used

| Field | Description |
|---|---|
| `AirlineName` | Name of the airline carrier |
| `Destination` | Flight destination |
| `FlightStatus` | On-time / Delayed |
| `Delay_Min` | Delay duration in minutes |
| `DelayRisk` | Risk classification of the flight |
| `TicketPrice` | Price of the ticket |
| `Year` | Year of the flight |

---

## 🛠️ Tools & Features Used

- **Power BI Desktop** — Dashboard design & data modelling
- **DAX** — Calculated measures for KPI cards and risk classification
- **Power Query** — Data transformation and cleaning
- **Slicers** — Interactive filtering by airline, destination, and risk
- **Donut Chart, Bar Chart, Scatter Plot** — Visual storytelling

---

## 💡 Key Insights

- Ability to identify which airlines have the highest rate of delayed flights
- Correlation analysis between ticket price and delay duration
- Risk-based segmentation helps operations teams prioritise high-risk flights
- Year-wise flight status trends reveal seasonal or operational patterns

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `Flight_Operations_Dashboard.pbix` | Main Power BI project file |
| `dashboard_screenshot.png` | Dashboard preview image |
| `dataset.csv` | Source dataset (if applicable) |
| `README.md` | Project documentation |

---

## 🚀 How to Run

1. Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free)
2. Clone or download this repository
3. Open `Flight_Operations_Dashboard.pbix` in Power BI Desktop
4. Interact with slicers to filter by airline, destination, or delay risk

---

## 👩‍💻 Author

**Sanjana Dandu** — Data Analyst | Mumbai, India  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sanjana%20Dandu-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanjana-dandu)
[![GitHub](https://img.shields.io/badge/GitHub-SANJUDANDU-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SANJUDANDU)
