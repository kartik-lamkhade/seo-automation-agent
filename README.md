# 🚀 SEO Automation Agent (n8n)

## 📌 Overview

This project is an AI-powered SEO Automation Agent built using **n8n**.
It automates keyword research, competitor analysis, and SEO content generation using real APIs and stores results in Google Sheets.

---

## ⚙️ Workflow Architecture

1. **Keyword Input**

   * User provides a target keyword

2. **SERP Analysis**

   * Fetches top search results using SerpAPI

3. **Competitor Data Extraction**

   * Extracts titles and links from top-ranking pages

4. **AI Content Generation**

   * Uses OpenRouter (LLM) to generate SEO-optimized content:

     * SEO Title
     * Meta Description
     * H1, H2, H3
     * FAQ Section
     * Local SEO (Pune-focused)
     * Content Gap Analysis

5. **Data Storage**

   * Stores generated content in Google Sheets automatically

---

## 🛠️ Tools & APIs Used

* **n8n** → Workflow automation
* **SerpAPI** → Google search results
* **OpenRouter API** → AI content generation (free tier)
* **Google Sheets API** → Data storage & reporting

---

## 📊 Output

The workflow generates structured SEO content and stores it in Google Sheets with:

* Keyword
* Title
* Full Blog Content
* Timestamp

---

## ▶️ How to Run

1. Import `workflow.json` into n8n
2. Add your API keys:

   * SerpAPI key
   * OpenRouter API key
3. Connect Google Sheets account
4. Run the workflow using Manual Trigger

---

## 🚀 Future Improvements

* Integrate Google Search Console API for real ranking data
* Add advanced keyword scoring (difficulty vs intent)
* Auto-publish blogs to CMS (WordPress/Git)
* Internal linking and SEO optimization engine
* Live dashboard for tracking performance

---

## ✅ Conclusion

This project demonstrates a fully working SEO automation pipeline using no-code tools, real APIs, and AI-generated outputs. It focuses on practical implementation, scalability, and real-world SEO use cases.

---
