# PetroCredit Risk & Stress-Testing Engine 🛢️💳

An automated counterparty credit scoring, macro-economic stress-testing, and AI-driven risk memorandum generation platform designed for global commodity and energy trading environments (Glencore-style risk workflows).

## 🚀 Project Overview
In international energy trading and oil supply chains, counterparty risk management requires continuous financial statement analysis, real-time commodity exposure monitoring, and rapid stress-testing against market volatility (such as Brent Crude price shocks and FX currency fluctuations). 

**PetroCredit Risk Engine** automates this end-to-end workflow: pulling live market data, computing credit leverage ratios, running severe downward stress tests, and employing an autonomous Gemini AI agent to draft institutional-grade credit risk memorandums.

---

## 🛠️ Tech Stack & Architecture
* **Python (Pandas, NumPy):** Handles data ingestion, balance sheet calculations, and quantitative credit scoring rules.
* **Yahoo Finance API (`yfinance`):** Dynamically fetches live market spot rates for Brent Crude (`BZ=F`) and USD/ZAR (`USDZAR=X`).
* **Google GenAI API (Gemini 3.8 Flash):** Acts as the AI Risk Agent, analyzing counterparty vulnerabilities and writing credit committee recommendations.
* **Google Colab & Drive:** Serves as the zero-cost cloud execution and storage environment.

---

## 📊 Core Features
1. **Automated Financial Ratio Analysis:** Automatically computes Debt-to-EBITDA, Interest Coverage, and Current Ratios from counterparty financial statements.
2. **Macro Commodity Stress Testing:** Simulates a 30% downside shock in Brent Crude prices to evaluate liquidity and debt-servicing compression under stress.
3. **Automated Risk Grading:** Categorizes energy counterparties into risk tiers (Grade A, B, or Watchlist Grade C).
4. **AI Credit Risk Memorandums:** Automatically packages quantitative results into a professional credit risk memo outlining recommended risk mitigants (such as Letters of Credit or parental guarantees).

---

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload or paste the `PetroCredit_Risk_Engine.ipynb` notebook script.
3. Insert your free Gemini API key from [Google AI Studio](https://aistudio.google.com/).
4. Click **Run** to execute the pipeline, generate the credit scorecard, and view the AI-generated Credit Committee Memorandum!
