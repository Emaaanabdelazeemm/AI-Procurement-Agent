# AI Procurement Agent System

## Overview

An AI-powered multi-agent system that automates the procurement process by searching, analyzing, and recommending the best products based on company requirements and value-for-price strategy.

The system uses specialized AI agents to:
- Generate optimized search queries.
- Search for products across e-commerce websites.
- Extract product information automatically.
- Compare products and generate procurement recommendations.
- Create a professional HTML procurement report.

---

## Workflow

```
Company Requirements
        |
        v
Search Query Recommendation Agent
        |
        v
Search Engine Agent
        |
        v
Web Scraping Agent
        |
        v
Product Analysis & Ranking
        |
        v
Procurement Report Generation
```

---

## Features

### Search Query Recommendation Agent
Generates specific product search queries based on company needs, target country, and product requirements.

### Search Engine Agent
Finds relevant e-commerce product pages and filters irrelevant results.

### Web Scraping Agent
Extracts structured product details including:
- Product name
- Price
- Specifications
- Product URL
- AI recommendation ranking

### Procurement Report Agent
Generates a professional HTML report containing product comparisons and recommendations.

---

## Technologies Used

- Python
- CrewAI
- Google Gemini LLM
- Pydantic
- Web Scraping APIs
- Search APIs
- Bootstrap CSS

---

## Project Structure

```
AI-Procurement-Agent/
│
├── README.md
├── AI_Procurement_Agent_Workflow.ipynb
├── requirements.txt
└── output/
    └── procurement_report.html
```

---

## Example Use Case

A company wants to purchase a product with the best value-for-price strategy.

The system automatically searches available products, extracts details, compares options, and generates a procurement report with recommendations.

---

## Future Improvements

- Add more e-commerce platforms.
- Implement real-time price tracking.
- Add product review analysis.
- Deploy as a web application.
