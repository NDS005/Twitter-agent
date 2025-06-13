# Twitter-agent
A  workflow using n8n that retrieves and summarizes trending tweets for any user-defined topic. Built with X (Twitter) scraping logic and customizable output channels
# 🐦 Trending Tweets Agent using n8n

This project is a AI agent that scrapes trending tweets related to any topic using [n8n](https://n8n.io/). It provides real-time sentiment snapshots or updates about public discourse from X (formerly Twitter).

---

## 🌍 Objective

To create an agent that retrieves and summarizes trending tweets for any user-defined topic using simple automation.

---

## 🧠 How It Works

1. **Input**: The user enters a topic like *"AI Agents"* or *"Warpspeed Hackathon"*
2. **Scraping**: The agent scrapes recent tweets related to the topic using an X/Twitter API (or scraping node)
3. **Output**: Tweets are formatted into a readable structure and sent via Telegram, Gmail, Notion, or stored in Google Sheets

---

## ⚙️ Tools & Technologies

* **n8n** (Visual workflow builder)
* **Twitter API / scraping tools**
* Optional: Email, Telegram, Notion, or Google Sheets for output

---


## 🧪 How to Try It

1. Recreate the workflow manually in your n8n instance
2. Set up scraping logic or Twitter API access
3. Add formatting, then push output to your preferred channel

---

