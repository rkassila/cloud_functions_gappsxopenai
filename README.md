# Cloud Functions + Google Apps Script + OpenAI

**Automated Sales Reporting with AI Insights**

[![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/apps-script)

## Overview

This repository contains code to **automate sales report generation** using:
- **Google Cloud Functions** (Python) for data processing and AI analysis
- **Google Apps Script** for Google Sheets integration and presentation creation
- **OpenAI** for intelligent insights and analysis

## Features

✅ **Automated Report Generation** - Create professional sales reports with a single click <br>
✅ **AI-Powered Insights** - Get intelligent analysis of your sales data <br>
✅ **Visual Data Representation** - Automatic graph generation and embedding <br>
✅ **Google Slides Integration** - Direct presentation creation from Google Sheets <br>
✅ **No Storage Quota Issues** - Images embedded directly in presentations

## 🛠 Setup Instructions

### Prerequisites

- Google Cloud Platform account
- Google Workspace account
- OpenAI API key
- Apps Scripts function to call GCP functions

### Cloud Function Setup

1. Deploy the function from `generating-sales-presentation/`
2. Set environment variables:
   - `OPENAI_API_KEY`: Your OpenAI API key
   - `SERVICE_ACCOUNT_JSON`: Your GCP service account credentials
3. Configure:
   - Runtime: Python 3.9

## Technical Details

- **Graph Generation**: Uses `matplotlib` and `seaborn` in Cloud Functions
- **AI Analysis**: Powered by OpenAI
- **Presentation Creation**: Handled by Google Apps Script
- **Image Handling**: Base64 encoding for direct embedding

