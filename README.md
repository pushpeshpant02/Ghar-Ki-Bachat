# Ghar-Ki-Bachat
“Paisa samjho, sahi se chalo — Ghar ki bachat yahi se shuru.”


An AI-powered personal finance companion for Indian families to track expenses, learn finance in simple language, and get smart savings &amp; investment guidance/ Paise ka hisaab, bachat ki kitaab — track kharchas, samjho finance, aur banao sahi paisa plans.

🔴 Problem

Most Indian households struggle with personal finance because:

  No proper tracking of daily expenses
  Financial concepts (GST, SIP, insurance, EMI) are confusing
  Multiple apps needed → leads to confusion
  People fall into loan traps, scams, high EMIs
  Professional advisors are too expensive
      ➡️ There is no single, simple platform for guidance + tracking + learning.

💡 Solution — Ghar Ki Bachat

Ghar Ki Bachat is an AI-assisted personal finance platform designed for Indian families.

It works as:

📒 Expense Tracker

📚 Financial Tutor (Easy Hinglish)

🤖 Smart Advisory Bot (Safe suggestions)

👨‍👩‍👧 Family Budget Planner


🎯 What Makes It Different--

| Feature               | Why it matters                       |
| --------------------- | ------------------------------------ |
| All in one system     | No need for 4-5 different apps       |
| Hinglish content      | Easy for everyone to understand      |
| AI risk detection     | Prevents mistakes before they happen |
| Designed for families | Budgets & goals for entire house     |
| Affordable            | Cheaper than professional advisors   |


⚙️ Key Features

1️⃣ Expense & Income Tracker

  Daily inputs (manual/voice input)
  Auto-categorization: Food, Rent, Travel, Medical, Education, EMI, etc.
  Monthly summary & behavior insights

2️⃣ Smart Financial Dashboard

Shows:

  Income vs Expense ratio
  Saving % every month
  Overspending alerts
  Category-wise breakdown

3️⃣ Learning Center (Simple Finance)

  GST, SIP, FD, EMI basics explained
  Hinglish notes + examples
  Real-life case studies for Indian families

4️⃣ Personalized Guidance

Recommendations based on:
  Age, earnings, risk capacity
  Goals → Child education, emergency fund, retirement
  No risky stock tips — only safe, rule-based guidance.

5️⃣ Risk & Scam Alert System

  Identifies:
  Too many loans/EMIs
  Loan repayment stress
  Suspicious investment schemes
  Declining savings trend

📌 User Flow
flowchart TD
    A[User Registers] --> B[Add Income & Expenses]
    B --> C[Dashboard Insights]
    C --> D{Financial Health Status?}
    D -->|Healthy| E[Continue Tracking & Learning]
    D -->|Risky| F[Alerts + Actionable Suggestions]
    F --> G[Plan Improvements: SIP, Budget, Goals]
    G --> C


🏗️ System Architecture
                 ┌──────────────────────────┐
                 │ Ghar Ki Bachat App (UI) │
                 │ Flutter / React         │
                 └───────────┬─────────────┘
                             │
                             ▼
      ┌────────────────────────────────────────────┐
      │             Backend API Server             │
      │      Node.js / Django + REST Endpoints     │
      └──────┬─────────────┬────────────┬──────────┘
             │             │            │
     ┌───────▼───┐   ┌─────▼────┐  ┌────▼─────────────────┐
     │ Database   │   │ ML Engine │  │ Risk/Rule Engine     │
     │ (Mongo/SQL)│   │ Python AI │  │ Alert + Safety Checks│
     └──────┬─────┘   └────┬─────┘  └──────────┬───────────┘
            │              │                    │
            ▼              ▼                    ▼
    ┌──────────────┐ ┌──────────────┐ ┌────────────────────┐
    │ Expense Data  │ │ Suggestions  │ │ Notifications/Alerts│
    └──────────────┘ └──────────────┘ └────────────────────┘

📊 Data Flow
User Input → Categorization → DB Storage → AI Insight Layer → Dashboard + Alerts


🛠️ Tech Stack
| Layer     | Tech                    |
| --------- | ----------------------- |
| Frontend  | Flutter / React         |
| Backend   | Node.js / Django        |
| Database  | MongoDB / PostgreSQL    |
| AI Engine | Python + Scikit-learn   |
| Cloud     | AWS / Firebase / Vercel |
| Auth      | Firebase / JWT          |




