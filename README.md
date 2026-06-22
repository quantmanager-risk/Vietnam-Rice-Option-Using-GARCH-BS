# Vietnam Rice Export Option Pricing Framework (GARCH-Black-Scholes Engine)

A data-driven, econometric financial engineering project that modernizes option pricing for the Vietnamese agricultural sector using actual export prices from VFA (2010–2026).

## 🚀 Key Features
- **Dynamic Volatility Sensor:** Replaces the flawed static volatility assumption of classic Black-Scholes with a **GARCH(1,1)-GED** model to capture volatility clustering and leptokurtic (fat-tail) risks.
- **LRNVR Duan (1995) Bridge:** Maps physical market parameters into a locally risk-neutral valuation relationship.
- **Comprehensive Backtesting:** Compares the dynamic engine against traditional BSM, measuring performance using **RMSE/MSE** metrics and validating results with a **Paired Sample T-test**.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Wrangling:** Pandas, NumPy
- **Econometrics & Modeling:** `arch`, `scipy.stats`, `statsmodels`
- **Visualization:** Matplotlib, Seaborn

## 📈 Results Highlight
- **Volatility Clustering Captured:** High-stress market periods (e.g., 2023–2025 export shocks) dynamically adjusted option premiums.
- **Risk Mitigation:** The GARCH-BS model acts as a reliable "volatility shield" for rice exporters to protect profit margins and serve as a reference architecture for the Vietnam Commodity Exchange (MXV).

## 🏃 How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone [https://github.com/quantmanager-risk/Vietnam-rice-option-pricing-garch-bs.git](https://github.com/quantmanager-risk/Vietnam-rice-option-pricing-garch-bs.git)
