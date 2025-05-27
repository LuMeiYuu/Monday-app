# Monday-app
# 📈 Sales Tracker & Slack Notifier (Monday App Integration)

This is a custom Monday.com app integration that automatically scans a board for sales data, groups results by agent and week, and sends a Slack message when an agent's total weekly sales exceed a defined threshold.

---

## 🚀 Features

- ✅ Fetches sales data from any Monday board
- 📅 Groups sales by **agent** and **week number**
- 📊 Compares against a user-defined **sales threshold**
- 🔔 Sends Slack notifications for agents who exceed the threshold
- 🕒 Runs automatically on a **weekly schedule** via Monday automation

---

## 🛠️ Tech Stack

- **Node.js + Express** backend
- **Monday Apps SDK** & GraphQL API
- **Slack Incoming Webhooks**
- Hosting: Vercel, Render, or any Node-compatible platform

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sales-tracker-monday.git
cd sales-tracker-monday
