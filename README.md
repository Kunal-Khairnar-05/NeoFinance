---
title: NeoFinance
emoji: 🚀
colorFrom: green
colorTo: gray
sdk: gradio
sdk_version: 5.23.1
app_file: app.py
pinned: false
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

### **📌 NeoFinance: Gemini Financial Chatbot**  
*NeoFinance is an AI-powered solution designed to bridge the financial literacy gap in India and help millions of new investors make informed decisions. Our intelligent chatbot interacts with users, answering investment questions and guiding them to suitable financial products. Users can request stock predictions for different timeframes, historical stock price, currency exchange, crypto exchange rate, stock info, top 10 gainers and lossers and also calculate loan and martgage payment. The solution is partially developed on Project IDX.*

*Leveraging transformer-based deep learning, the solution provides highly accurate stock forecasts, empowering investors with data-driven insights. By automating financial guidance through AI, our system ensures scalability, addressing the massive influx of new investors without manual intervention. This project revolutionizes investment decision-making, making financial knowledge accessible, actionable, and personalized for every user.*  

#### **Problem Statement: GenAI-Powered Financial Assistant for Better Investing Decisions**

---

### **🔹 Features (Updated for Financial Literacy & Decision-Making)**  
- 📈 **Fetch historical financial data:** Stocks, currencies, crypto, and commodities (gold, silver, copper, platinum) to help users analyze trends.  
- 🔮 **Stock price prediction & insights:** Uses transformers to forecast stock prices and provides **educational explanations** on market factors affecting the trend.  
- 🏢 **Company stock info retrieval:** Displays stock details **along with financial ratios** (P/E ratio, dividend yield, etc.) to help users evaluate investments.  
- 📊 **Top 10 daily gainers and losers:** Offers a summary of why certain stocks are moving up or down and **educates users on market volatility**.  
- 🏦 **Loan and mortgage calculator:** Computes monthly payments, total costs, and interest, **while explaining financial concepts like APR and amortization**.  
- 🎓 **Financial literacy tips:** Provides AI-powered insights on investment strategies, risk management, and wealth-building habits.  
- 💡 **Smart decision assistance:** Offers **personalized financial advice** based on the user's profile, risk appetite, and market conditions.

---
### **Preview**
| | |
|:-------------------------:|:-------------------------:|
<img width="1604" alt="" src="https://github.com/user-attachments/assets/edfe0575-99ba-43b3-9831-e74798d5f95d">  Stock Information| <img width="" src="https://github.com/user-attachments/assets/16ccc832-5759-4f58-bcbf-c2a596349f45"> Historic Exchange Rates |
<img width="1604" alt="" src="https://github.com/user-attachments/assets/4f46b606-d9dc-4f99-ba97-f37ef485ee3b"> Predict Price| <img width="" src="https://github.com/user-attachments/assets/a6452a18-fd76-463b-9e2e-3a6c07562fd4">Graphs Display |
<img width="" src="https://github.com/user-attachments/assets/76299820-cee6-410c-ad15-af1b463597b1"> Perticular Stock History | <img width="" src="https://github.com/user-attachments/assets/f2dcaa34-4447-41bd-ae93-53a0e21b18f2"> Top Losers |
<img width="" src="https://github.com/user-attachments/assets/111e6693-8a6f-4217-ae7a-dcf8116f7687"> Bitcoin Price | <img width="" src="https://github.com/user-attachments/assets/1c8b5683-78d6-45fb-8e6d-84d56d82ea77"> Raw predictions |
<img width="" src="https://github.com/user-attachments/assets/0dde38a9-b2c1-4d1d-b978-c89bd3bb602d"> Top Gainers |<img width="" src="https://github.com/user-attachments/assets/cec80cd1-c730-4011-9c0b-29ca09f4cebe"> Calculate Mortgage |

---

### **🚀 Getting Started**  

#### **1️⃣ Installation**  
```bash
git clone https://github.com/hano0709/NeoFinance.git
cd NeoFinance
```
If you are using windows (CMD, not powershell):
```bash
python -m venv myenv
myenv\Scripts\activate
```
And for MAC and Linux
```bash
python -m venv myenv
source myenv/bin/activate
```
Then downloading the dependencies:
```bash
pip install -r requirements.txt
```

#### **2️⃣ API Setup**  
In order to setup the API keys, create a .env file and write the following details:  
```bash
GEMINI_API_KEY1="Your_Gemini_Api_Key"
ALPHA_API_KEY1="Your_Alpha_Vantage_Api_Key"
CLOUDINARY_CLOUD_NAME="Your_Cloudinary_Cloud_Name"
CLOUDINARY_API_KEY="Your_Cloudinary_Api_Key"
CLOUDINARY_API_SECRET="Your_Cloudinary_Api_Secret"
```

#### **3️⃣ Running the Bot**  
For windows:
```bash
python app.py
```

For Mac/Linux:
```bash
python3 app.py
```
From here you should get some links which will redirect you to the gradio interface which contains the chatbot.
---

### **Contributors:**
- **Hano Varghese:** Team leader, built the transformer for prediction and gradio interface.
- **Ruhan Dave:** Integrated Gemini using function calling, developed all functions except stock info and prediction.
- **Kunal Khairnar:** Web Development, Documentation, PPT. 
