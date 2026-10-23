# 📊 AI Business Insights Generator

### Transform Business Data into Actionable Insights with Generative AI

An interactive business intelligence application that combines data analytics, visualization, and Generative AI to transform business datasets into meaningful insights. Built with Python and Streamlit, the application enables users to analyze sales and profitability, explore business performance, and generate AI-powered recommendations using Google's Gemini API.

🚀 **[Launch Live Application](https://businessinsightsnarrative-dashboard-exdizufpuafpfto5e2gggt.streamlit.app/)**

📂 **[View GitHub Repository](https://github.com/ay3944013-glitch/Business_insights_narrative-dashboard)**

---

## 📌 Project Overview

Businesses generate large amounts of data, but converting that data into meaningful business decisions can be challenging.

The **AI Business Insights Generator** addresses this challenge by combining traditional data analytics with AI-powered business interpretation.

Users can upload a business dataset in CSV format, explore key performance indicators (KPIs), analyze business performance, and ask questions about their data. The application uses Google's Gemini API to generate structured business insights, identify potential risks and opportunities, and suggest actionable recommendations.

The goal is to make business analytics more accessible by transforming numerical data into understandable business narratives.

## ✨ Key Features

### 📂 1. Business Dataset Upload

* Upload business datasets in CSV format.
* Load data for analysis using Pandas.
* Preview uploaded records before analyzing the dataset.

### 📈 2. KPI Analysis

Calculate and display important business performance indicators, including:

* **Total Sales:** Overall sales generated.
* **Total Profit:** Total profit earned.
* **Total Orders:** Number of unique orders.
* **Total Customers:** Number of unique customers.
* **Average Discount:** Average discount percentage.

### 📊 3. Business Performance Analysis

* Explore business performance through interactive visualizations.
* Analyze sales and profitability.
* Compare category-level performance.
* Identify leading and underperforming business segments.
* Examine regional performance to understand business trends.

### 🤖 4. AI-Powered Business Insights

* Generate insights using Google's Gemini API.
* Ask business-related questions about the uploaded dataset.
* Interpret business KPIs using AI-generated analysis.
* Explore potential reasons behind business performance.
* Identify business risks and opportunities.
* Receive recommendations to support decision-making.

### 🧠 5. Business Rules and Context

* Incorporate predefined business rules into AI prompts.
* Provide additional context for business analysis.
* Guide the AI toward more relevant business interpretations.

### 📝 6. Structured AI Reports

Generate business analysis containing sections such as:

* Executive Summary
* Key Insights
* Possible Reasons
* Risks
* Opportunities
* Recommendations

### 📥 7. Report Export

Access the generated business insight report for further review and reuse.

---

## 🌐 Live Demo

### 👉 [Try the AI Business Insights Generator](https://businessinsightsnarrative-dashboard-exdizufpuafpfto5e2gggt.streamlit.app/)

Explore the application to see how business data can be transformed into analytical summaries and AI-generated recommendations.

## 🛠️ Technology Stack

| Technology                | Purpose                                          |
| ------------------------- | ------------------------------------------------ |
| Python                    | Core programming language                        |
| Streamlit                 | Interactive web application interface            |
| Pandas                    | Data loading, manipulation, and KPI calculations |
| Plotly                    | Interactive data visualizations                  |
| Google Gemini API         | AI-powered business insight generation           |
| Google Generative AI SDK  | Integration with the Gemini model                |
| python-dotenv             | Environment variable management                  |
| Git                       | Version control                                  |
| GitHub                    | Source code hosting                              |
| Streamlit Community Cloud | Application deployment                           |

---

## ⚙️ Installation and Setup

Follow these steps to run the project on your local machine.

### Prerequisites

* Python installed on your system.
* Git installed on your system.
* A Google Gemini API key.

### Step 1: Clone the Repository

```bash
git clone https://github.com/ay3944013-glitch/Business_insights_narrative-dashboard.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Business_insights_narrative-dashboard
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### Step 4: Install Dependencies

Install the required packages:

```bash
pip install -r requirements.txt
```

### Step 5: Configure the Gemini API Key

Create a `.env` file in the project root directory.

Add the following configuration:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Replace `your_gemini_api_key` with your actual API key.

You can obtain an API key through [Google AI Studio](https://aistudio.google.com/).

**Security:** Never upload your `.env` file or expose your API key in a public GitHub repository.

### Step 6: Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to access the application.

---

## 🔄 How the Project Works

The application follows an AI-assisted business analytics workflow.

```text
        Business Dataset
          (CSV Upload)
               |
               v
       Data Loading with
           Pandas
               |
               v
        Dataset Preview
               |
               v
      KPI Calculations
               |
               v
    Business Performance
         Analysis
               |
               v
     Business Question
         + KPIs
               |
               v
       Gemini API
      AI Processing
               |
               v
     Business Insights
               |
               v
   Risks, Opportunities,
     Recommendations
               |
               v
       Insight Report
```

### Workflow Explanation

1. **Data Input:** The user uploads a business dataset in CSV format.
2. **Data Processing:** Pandas loads the dataset for analysis.
3. **KPI Calculation:** The application calculates key business metrics.
4. **Business Analysis:** The application derives performance indicators and supporting information.
5. **User Query:** The user enters a business-related question.
6. **AI Processing:** The Gemini API receives a prompt containing business KPIs, business rules, and the user's question.
7. **Insight Generation:** The AI generates a structured business analysis.
8. **Reporting:** The application displays the generated insights and provides report output.

---

## 💡 Example Use Case

Imagine a retail business wants to understand its sales and profitability.

A user uploads the business dataset and asks:

**Business Question:**

> What are the main factors affecting profitability, which category performs best, and what actions could improve business performance?

The application can use the available business metrics and AI-generated analysis to provide:

* An executive summary of business performance.
* Key findings from the available KPIs.
* Potential explanations for observed performance.
* Possible business risks.
* Opportunities for improvement.
* Recommendations for business decision-makers.

*Note: The quality and accuracy of the results depend on the uploaded dataset, available metrics, business rules, and AI-generated interpretation.*

---

## 🎯 Business Value

This project demonstrates how data analytics and Generative AI can work together to support business decision-making.

Key benefits include:

* Reduces the effort required to interpret business metrics manually.
* Makes analytical findings easier to understand.
* Helps users explore business questions in natural language.
* Converts numerical KPIs into structured business narratives.
* Supports the identification of potential risks and opportunities.
* Demonstrates practical applications of AI in business intelligence.

---

## ⚠️ Limitations

* The application currently accepts CSV datasets.
* The business KPI calculations depend on the expected column names in the dataset.
* AI-generated explanations may contain incorrect assumptions or interpretations.
* Results should be validated against the original data before making business decisions.
* A valid Gemini API key and available API service are required for local execution.
* The application uses predefined business rules rather than automatically discovering all business-specific requirements.

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

* Support for Excel files and additional data sources.
* Flexible column mapping for different business datasets.
* Advanced data quality checks and missing-value handling.
* Automated anomaly detection.
* Sales and profit forecasting.
* Natural-language questions across a wider range of business metrics.
* Downloadable PDF and Excel reports.
* More advanced business recommendations.
* Additional interactive filters and visualizations.

---

## 👨‍💻 Author

**Ankit Yadav**

* **GitHub Profile:** [ay3944013-glitch](https://github.com/ay3944013-glitch)
* **Project Repository:** [Business Insights Narrative Dashboard](https://github.com/ay3944013-glitch/Business_insights_narrative-dashboard)
* **Live Application:** [AI Business Insights Generator](https://businessinsightsnarrative-dashboard-exdizufpuafpfto5e2gggt.streamlit.app/)

---

## ⭐ Support

If you find this project useful, consider giving the repository a star on GitHub.

**Built with Python, Streamlit, and Generative AI to turn business data into actionable insights.**
