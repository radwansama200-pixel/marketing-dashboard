# Marketing Performance Dashboard

An interactive dashboard that turns ad-spend data into a clear budget decision.

**Live demo:** https://radwansama200-pixel.github.io/marketing-dashboard/

## What it shows
- 8 KPIs: revenue, ad spend, ROAS, CAC, conversion rate, AOV, orders, profit after ads
- Revenue vs. spend trend, with a tap/hover tooltip per day
- ROAS by channel (Meta, TikTok, Google, Email) against a break-even line
- Channel table with status: good / medium / loss
- An auto-generated recommendation on where to move budget

## Design choices
- Break-even ROAS is calculated from an assumed 40% profit margin (1 / 0.40 = 2.5x), not a fixed number
- Mobile-first, supports light and dark mode
- Single HTML file, no dependencies

## Notes
- Data is randomly generated for demonstration only
- Revenue attribution depends on the client's attribution model; channels can double-count the same order

## Built by
Samaa El Iraqi, Data Analyst
Google Data Analytics | Microsoft PL-300
