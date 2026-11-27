# Customer Health & Churn-Risk Dashboard

A Customer Success tool that scores accounts, flags churn risk, quantifies the revenue at stake, and suggests a margin-aware retention offer with a ready-to-send email.

**Live demo:** https://github.com/SheisJOY/Customer-Health-dashboard)

## The problem
CS teams often ask "which accounts should I call first?" This tool answers with data and dollars instead of gut feeling.

## What it does
- Scores each account from 0 to 100 using seat usage (40%), NPS (25%), open support tickets (20%) and days since last login (15%).
- Groups accounts as Healthy, Watch or At risk.
- Shows annual revenue at risk and estimated loss, and ranks accounts by dollars so the biggest saves come first.
- Suggests a retention discount (never above 10%) with the resulting profit margin and the break-even save rate, assuming a 25% margin.
- Drafts a retention email for each account that can be copied in one tap.

## How I built it
I built this by "vibe coding": I described the business problem and the changes I wanted in plain English, and Claude generated the code. I directed the product decisions, such as the scoring weights, ranking by revenue impact, and the discount guardrails.

## What I learned
Having my  Words perfectly translated into code is so cool. Will tweak some more as inspired.

## Note
All accounts and revenue figures are fictional sample data.
