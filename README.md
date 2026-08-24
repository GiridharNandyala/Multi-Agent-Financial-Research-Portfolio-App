# 📈 Multi-Agent Financial Research & Portfolio Analytics App

## 📌 Problem Statement & Motivation
Analyzing financial markets and individual equities typically forces investors, quantitative analysts, and financial researchers to navigate across multiple fragmented platforms—sourcing raw pricing on one portal, technical indicators on another, and sentiment metrics elsewhere. This manual pipeline is inefficient and time-intensive.

To address this workflow bottleneck, I engineered the **Multi-Agent Financial Analytics App**. Operating on multi-agent architectural concepts, this platform automates real-time data ingestion, technical analysis, multi-asset comparative evaluation, and market sentiment extraction into a unified executive dashboard.


<!-- BADGES / BUTTONS SECTION -->
[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Streamlit_App-red?style=for-the-badge&logo=streamlit)](https://giridhar-multi-agent-financial-research-portfolio-app.streamlit.app/)
[![LinkedIn Post](https://img.shields.io/badge/💼_LinkedIn-Post-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/giridhar-nandyala-5758662b2_python-dataanalysis-streamlit-ugcPost-7497533252426162176-cTpZ/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEs70akBeCLfAOvC2nnAC0kHj16JNBTXqJM)

---

---

## 💡 Real-World Value & Business Impact
* **Automated Data Aggregation:** Eliminates manual platform switching by compiling financial metrics, news feeds, and charting tools into a centralized interface.
* **Data-Driven Decision Making:** Enables structured asset evaluation using technical moving averages, side-by-side relative performance overlays, and sentiment metrics rather than nominal price movements alone.
* **Instant Executive Reporting:** Converts real-time analytics into portable, standardized PDF documentation with one click for client reporting and internal research workflows.

---

## 🚀 Key Features

* **Real-Time Market Metrics:** Displays live equity pricing, 52-week high/low boundaries, P/E ratios, and dynamic day-change deltas.
* **Interactive Technical Analysis:** Custom interactive charts built with Plotly, featuring automated 20-day Simple Moving Average (SMA) technical overlays.
* **Multi-Stock Comparison Engine:** Normalized percentage-return charting engine for evaluating comparative asset performance side-by-side.
* **AI Agent Insights:** Automated synthesis breaking down fundamental operational health, market news sentiment scoring, and strategic portfolio positioning recommendations.
* **Live News Feed Aggregator:** Real-time news parser rendering direct hyperlinked external sources for target stock tickers.
* **Automated PDF Export:** Programmatically generates downloadable financial summary reports using `reportlab`.

---

## 🛠️ Tech Stack & Architecture

* **Frontend & UI:** Streamlit
* **Data Ingestion:** YFinance API
* **Data Processing & Analytics:** Pandas, NumPy
* **Data Visualization:** Plotly Graph Objects
* **Document Engine:** ReportLab (Automated PDF Generator)

---

## ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/financial-agent-app.git](https://github.com/YOUR_USERNAME/financial-agent-app.git)
   cd financial-agent-app

   1.Install dependencies:
   pip install -r requirements.txt
   
   2.Launch the application:
   streamlit run app.py
