# 🛡️ CyberInvest Pro

CyberInvest Pro is an intelligent, AI-powered web application designed to simplify and optimize cybersecurity investment decisions. It bridges the gap between complex academic theories and practical business needs by translating an organization's unique context into a clear, actionable, and verifiable investment strategy powered by Google's Gemini AI.

### Live Demo

**[View the Live Project Here](https://expdeath.github.io/Cyberinvestpro/)**

*(Note: You will need to add your own API key to the URL as described in the "How to Run" section below.)*

-----

## Features

  * **Dynamic Dashboard:** Get a "single pane of glass" overview with 10 interactive KPIs, a budget allocation pie chart, and a 6-month risk reduction trend chart.
  * **AI-Powered Analysis:** Input your budget, industry, goals, and a detailed asset inventory to receive a tailored investment plan.
  * **Predictive Risk Assessment:** Forecast future risks based on your new investment plan and get specific mitigation steps for different business domains.
  * **Built-in Validation:** Every recommendation includes an AI-generated **Rationale** and is mapped to the **NIST Cybersecurity Framework**, making the AI's logic transparent and verifiable.
  * **Fully Interactive UI:** Click on any metric, chart, or result to get a detailed explanation in a clean, modern pop-up modal.
  * **Robust Error Handling:** The application features an API retry mechanism and a cancellation button for a smooth user experience.

-----

## Getting Started

To run this project, you only need a modern web browser and a Google AI API key.

### 1\. Get a Gemini API Key

You need to generate your own personal API key from Google AI Studio. It's a free and straightforward process.

1.  Visit the **[Google AI Studio](https://aistudio.google.com/)** website.
2.  Sign in with your Google account.
3.  Click on **"Get API key"** (usually on the top left).
4.  Click **"Create API key in new project"**.
5.  Copy the generated API key string. **Keep this key private and secure.**

### 2\. How to Run the Application

This application reads the API key from the browser's URL to keep it secure and out of the source code.

1.  Open the `https://expdeath.github.io/Cyberinvestpro/` in your web browser.
2.  In the browser's address bar, append your API key as a query parameter named `apiKey`.

Your final URL should look exactly like this, with your key at the end:

```
https://expdeath.github.io/Cyberinvestpro/?apiKey="YOUR_PERSONAL_API_KEY"
```

## Technical Stack

  * **Frontend:** HTML5, CSS3, Vanilla JavaScript
  * **AI Engine:** Google Gemini Pro (`gemini-2.5-flash`)
  * **Data Visualization:** Chart.js
  * **Prompt Engineering:** The application relies on highly structured, template-based prompts with a `temperature` of 0 to ensure the AI provides consistent and reliable JSON data.
