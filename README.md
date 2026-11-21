# Chili-Overseas-Funnel-Analysis
# Inbound Travel Acquisition Funnel & Landing Page CRO Analysis (Chili Case Study)

An empirical business analysis project examining overseas customer acquisition efficiency on TikTok and landing page conversion bottlenecks for **Chili** (`travel.chili.sh.cn`), an inbound local-lifestyle O2O platform in China.

## 1. Executive Summary & Core Findings
- **Dataset & Methodology**: Scraped and deduplicated **400 public TikTok videos** across `#chinatravel` and three targeted search queries (`China travel tips`, `China citywalk`, `Shanghai local experience`). Videos were coded into three commercial content categories and evaluated via non-parametric **Kruskal-Wallis tests**.
- **Utility Outperforms High-Ticket Experiences in Lead Intent**: Utility-driven videos (payment, visa, transit hacks; $n=176$) achieved a median actionable intent rate (saves + shares + comments) of **4.21%** (median save rate: **2.76%**), **2.2x higher** than high-ticket curated experience videos ($n=63$, median intent rate: **1.91%**, $p < 0.001$).
- **Landing Page Conversion Friction**: Heuristic audit of `travel.chili.sh.cn` identified an acquisition mismatch: the landing page leads exclusively with high-ticket experiences ($39–$368) and enforces app-download redirection without capturing high-intent utility traffic via web-based lead magnets.

## 2. Repository Structure
- `chili_tiktok_funnel_analysis.ipynb`: Python (`pandas`, `scipy`, `matplotlib`) data cleaning, content coding, statistical testing, and visualization notebook.
- `chili_tiktok_clean_data.csv`: Deduplicated analytical dataset ($N = 400$) formatted for Tableau Public dashboarding.
- `Chili_Funnel_Benchmark.png`: Restrained monochrome benchmark chart comparing shallow engagement vs. actionable intent rates.
