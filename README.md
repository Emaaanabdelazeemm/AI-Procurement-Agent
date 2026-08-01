# AI Procurement Multi-Agent System

An AI-powered **multi-agent procurement system** built with **CrewAI** and **Google Gemini** that automates the entire procurement workflow. Specialized AI agents collaborate to generate search queries, search the web, extract product information, analyze and rank products, and generate a professional HTML procurement report based on a **value-for-price** strategy.

---

## Generated Report

The system generates a professional HTML procurement report with product details, pricing, and AI-powered recommendations.

<p align="center">
  <img width="900" alt="Generated Procurement Report" src="https://github.com/user-attachments/assets/6c209036-ab4e-4c21-934c-34194bca5f13" />
</p>

---

## Multi-Agent Workflow

```text
Company Requirements
        │
        ▼
Search Query Recommendation Agent
        │
        ▼
Search Engine Agent
        │
        ▼
Web Scraping Agent
        │
        ▼
Product Analysis Agent
        │
        ▼
Procurement Report Agent
        │
        ▼
HTML Procurement Report
```

---

## Features

- Multi-agent workflow powered by CrewAI.
- AI-generated search queries based on procurement requirements.
- Automated web search across e-commerce websites.
- Intelligent web scraping for structured product information.
- AI-based product comparison and ranking.
- Professional HTML procurement report generation.

---

## Tech Stack

- Python
- CrewAI
- Google Gemini
- Pydantic
- Tavily Search API
- ScrapeGraphAI

---

## Project Structure

```text
AI-Procurement-Agent-System/
│
├── README.md
├── AI_Procurement_Agent_Workflow.ipynb
└── output/
    └── procurement_report.html
```

---

## Future Improvements

- Support additional e-commerce platforms.
- Real-time price monitoring.
- Product review analysis.
- Deploy as a web application.
