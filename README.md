# Design of an Automated OBE Portal via Google Apps Script

Welcome to the demonstration page for our Automated Outcome-Based Education (OBE) Assessment Portal. 

## 🚀 Live Demonstration
The software is deployed securely on the Google Apps Script serverless platform. 
🔗 **[Click Here to Access the Live OBE Portal](https://script.google.com/macros/s/AKfycbxZfC6UHTQwoZ9SDChVPjQ5WFWQA95mNajSa1SO7gYFrjnM0KJf4-7jMZyEkfeb3hpC/exec)**

## ⚖️ Comparative Demonstration Setup (A/B Testing)
To practically demonstrate the efficiency of our proposed AI-integrated system compared to traditional methods (as discussed in Section V of our paper), this demo features a dual-mode evaluation setup:

### 1. Traditional Manual Mode (Staff Login)
* **Username:** `staff01`
* **Password:** `pass123`
* **Purpose:** Log in here to experience the conventional manual process. Reviewers can type questions manually and test the real-time Bloom's tracking. This highlights the time-consuming nature, cognitive load, and difficulty of manually balancing the assessment rubrics without AI assistance.

### 2. Proposed AI-Automated Mode (Admin Login)
* **Admin ID:** `admin`
* **Password:** `admin123`
* **Purpose:** Log in here and click the **"✨ AI Syllabus Gen"** tab to test the core novelty of this research. By using the **"Auto-Fill from Syllabus"** feature, the Gemini API instantly parses the text, generates questions, and maps them to Bloom's levels. This demonstrates a massive reduction in manual drafting time and highlights the seamless Graph Coloring integration.

## 🛠️ How to Test the AI Automation (Admin Mode)
1. Select **"Admin"** at the bottom of the login page and enter the Admin credentials.
2. Go to the **"✨ AI Syllabus Gen"** tab.
3. Select the target parameters and Question Paper Set.
4. Paste a sample syllabus into the input box (Step 1).
5. Click **"1. Generate Editor Boxes"**.
6. Click **"✨ Auto-Fill from Syllabus"** in each part. Watch the AI instantly generate the questions.
7. Click **"3. Print View"** to render the final A4 assessment paper powered by MathJax.
