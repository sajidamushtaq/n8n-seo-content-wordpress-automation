# n8n SEO Content & WordPress Automation

> **Independent Portfolio Project** — A practical n8n workflow architecture for turning spreadsheet-based keywords into AI-assisted SEO content and publishing it to WordPress through the REST API.
## 📄 Workflow Sample

[View the n8n SEO Content Workflow Sample (PDF)](./n8n-SEO-Content-Workflow-Sample.pdf)

## 🎯 Project Goal

The goal of this workflow is to connect Google Sheets, AI content generation, and WordPress in one reliable automation while keeping every article traceable to its original keyword row.

## ⚙️ Workflow Architecture

```text
Google Sheets
     ↓
Select Ready Keyword Row
     ↓
AI Research Prompt
     ↓
AI Content Generation
     ↓
Validate Required Fields
     ↓
WordPress REST API
     ↓
Create Draft / Publish
     ↓
Write Post ID + URL Back to Sheet
