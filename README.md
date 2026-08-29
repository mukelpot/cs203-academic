# Adaptive Academic Planner — UI Mockup

A rough, clickable front-end sketch of the Adaptive Academic Planner
(SMU Human-AI Collaborative Software Development project).

**Everything is fake, hardcoded sample data. There is no backend yet.**
The point is to show what the product will feel like: the dashboard, the
adaptive calendar, risk forecasting, the BOSS bidding assistant, university
info monitoring, and the AI advisor with accept / reject / modify controls.

## How to run it

No installation needed — it's one plain HTML file.

1. Download or clone this repository.
2. Double-click `index.html`. It opens in your browser.

## The demo story

On the **Overview** tab, click **"Simulate: CS301 deadline moves Fri 4 Sep → Tue 1 Sep"**.
This walks through the project's core adaptation pipeline:

change detected → plan recalculated → risk forecast updated → AI recommendation → student accepts/rejects/modifies

Click **Reset demo** in the orange banner to go back to the normal state.

## What's real vs. mocked

| Piece | Status |
|---|---|
| UI layout, tabs, interactions | Working (plain HTML/CSS/JS) |
| All data (modules, deadlines, risks, bids) | Hardcoded sample data |
| Backend (Spring Boot), database, AI, RAG | Not built yet — see project plan |

## Planned stack (for the real system)

Java + Spring Boot backend · React frontend · PostgreSQL · LLM API · cloud deployment
