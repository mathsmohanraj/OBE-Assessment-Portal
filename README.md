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

## 🧠 How Graph Theory (Coloring Heuristic) is Applied?
The core mathematical novelty of this system lies in its conflict-resolution engine, based on a Greedy Graph Coloring heuristic (with Chromatic Number \(k=3\)):

* **Vertices (Nodes):** Represent the surplus pool of AI-generated questions.
* **Edges (Conflicts):** Represent a semantic overlap (questions testing the exact same topic/formula) or a cognitive weightage conflict.
* **Colors (\(k=3\)):** Represent the 3 distinct Question Paper Sets (SET-I, SET-II, SET-III).

**How to observe this in the Live Demo:** 
When you select **SET - I** from the dropdown and generate questions, the algorithm assigns the first "color". If you switch the dropdown to **SET - II** or **SET - III** and generate again, the backend coloring algorithm ensures that conflicting or highly overlapping questions from the previous set are avoided. This mathematical filtration guarantees 0% conceptual redundancy across different exam slots.

## 🛠️ How to Test the AI Automation (Admin Mode)
1. Select **"Admin"** at the bottom of the login page and enter the Admin credentials.
2. Go to the **"✨ AI Syllabus Gen"** tab.
3. Select the target parameters and choose the required Question Paper Set.
4. Paste a sample syllabus into the input box (Step 1).
5. Click **"1. Generate Editor Boxes"**.
6. Click **"✨ Auto-Fill from Syllabus"** in each part. Watch the AI instantly generate the questions.
7. Check the **Live OBE Tracker** on the right side for pedagogical balance.
8. Click **"3. Print View"** to render the final A4 assessment paper powered by MathJax.

*(Note: The core backend source code is kept proprietary to protect institutional data privacy and comply with double-blind peer review standards).*
