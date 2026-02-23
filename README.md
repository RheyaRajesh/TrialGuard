# TrialGuard 🛡️💰

**TrialGuard** is a SaaS Trial Abuse Detection & Revenue Protection Platform  
Helping SaaS companies maximize trial profitability while minimizing abuse damage.

It continuously decides for each trial user whether to:  
**✅ Allow** • **🐢 Throttle** • **⛔ Block** • **🚩 Flag**

Based on smart, privacy-respecting signals:

- 🖐️ **Behavioral Fingerprinting** — non-PII usage pattern tracking  
- 🔥 **Resource Drain Detection** — spotting shared resource abuse  
- ⚖️ **ROI Scoring** — real-time value vs. cost & risk calculation  

## ✨ Core Features

- 🏗️ **Multi-Tenant Architecture** — clean logical separation per customer  
- 📊 **Modern Dashboard** — real-time admin interface (Streamlit)  
- 🧪 **Simulation Engine** — built-in traffic generator with realistic profiles:  
  • Normal users • Abusive users • High-value legitimate users  
- 🐍 **Pure Python Backend** — minimal dependencies, no external database required  

## 🚀 Quick Start

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/TrialGuard.git
    cd TrialGuard
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Launch the app 🎉 
    ```bash
    streamlit run app.py
    ```

Navigate to `http://localhost:8501` in your browser.

### 📌Key Pages
-   **Overview Dashboard**: Monitoring stats and live decision feed.
-   **Trial User Analyzer**: Deep dive into specific user scores and reasons.
-   **Resource Drain Monitor**: Visualizing backend load.
-   **Tenant Configuration**: Adjusting thresholds and weights.

## ⚖️License

[MIT](LICENSE)

