# 💼 Investment Assistant using GenAI

**Unleash the power of Gen-AI in your investment strategies!** Our advanced investment advisor application leverages cutting-edge Generative AI to elevate stock analysis and provide you with insightful investment recommendations. Built with Streamlit, this platform integrates real-time financial data from Yahoo Finance (yfinance) and the latest news from DuckDuckGo (DDGS) to craft comprehensive investment reports just for you.

## 🚀 Key Features

- **📈 Real-time Data Integration:** Seamlessly fetch current stock prices, historical data, and key financial metrics with yfinance.
- **🧠 AI-powered Report Generation:** Utilize Groq’s AI to generate detailed and professional investment reports that rival the expertise of a senior Goldman Sachs analyst.
- **📰 News Aggregation:** Stay informed with the latest news articles relevant to your chosen stock, curated using DuckDuckGo search.
- **📊 Analyst Recommendations:** Get the latest insights with recent analyst upgrades and downgrades to make well-informed decisions.
- **📄 PDF Report Download:** Download your AI-generated investment reports as professionally formatted PDFs for easy sharing and offline viewing.

## 🌍 Use Cases

### Individual Investors
Empower individual investors with advanced tools and insights typically reserved for financial professionals. Make informed decisions based on comprehensive AI-generated reports.

### Financial Advisors
Enhance the services offered by financial advisors with detailed, real-time reports and recommendations, allowing them to provide clients with up-to-date and accurate investment advice.

### Investment Clubs
Facilitate group discussions and collective decision-making in investment clubs with easily shareable and professionally formatted reports.

### Educational Institutions
Support finance and investment courses with practical tools and real-world data, helping students to better understand market dynamics and investment strategies.

### Corporate Finance Teams
Assist corporate finance teams in performing detailed stock analysis for strategic investment decisions, mergers, acquisitions, and portfolio management.

## 🌟 Impact

Transform your investment research with AI-generated insights and professional-grade reports, significantly enhancing the efficiency and quality of your decision-making process. This tool can:

- **Increase Accuracy:** Reduce human error and bias with AI-driven analysis.
- **Save Time:** Quickly generate comprehensive reports, freeing up time for strategic planning.
- **Enhance Knowledge:** Stay updated with the latest market trends and news.
- **Improve Decision-Making:** Make better-informed decisions with detailed, data-driven insights.

## 🛠 Technologies Used

- Python
- Streamlit
- Generative AI (Groq)
- yfinance
- DuckDuckGo Search
- ReportLab
- dotenv

## 🛠 Installation

Follow these steps to set up and run the project locally:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/investment-assistant.git
    cd investment-assistant
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:** Create a `.env` file in the project root and add your Groq API key:
    ```
    GROQ_API_KEY=your_groq_api_key
    ```

5. **Run the application:**
    ```sh
    streamlit run app.py
    ```

## 🎯 Usage

- Open the application in your browser. By default, it runs at [http://localhost:8501](http://localhost:8501).
- Enter a stock ticker symbol in the input field and click the "Generate Investment Report" button.
- View the generated investment report on the web interface.
- Click the "Download Report as PDF" button to save the report as a PDF file.

## 🤝 Contributing

We welcome contributions to enhance the functionality and features of this project. To contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch-name
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch-name
    ```
5. Open a pull request on GitHub.

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

## 📬 Contact

For any inquiries or feedback, please contact:

**Your Name**  
Email: [your- anuragsahu4328@gmail.com](mailto:anuragsahu4328@gmail.com)  
---

**Elevate your investment strategies with AI – happy investing!**
