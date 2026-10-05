# Devlab Week 2 — SQL, Markets & Customer Analytics

Three datasets, three different business questions.

This week focused on moving beyond basic exploration and using data to compare performance, profitability, customer behavior, and market structure.

The projects cover:

- Superstore profitability with SQL
- Regional video game market analysis
- UK e-commerce customer and revenue analysis

---

## 01 · Superstore Profitability — SQL

**Dataset:** Sample Superstore  
**Rows:** 9,994  
**Period:** 2014–2017  
**Main tools:** MySQL, SQL, Jupyter

### What was analyzed

- regional and sub-category profitability
- discount impact
- shipping performance
- customer value
- year-over-year sales growth
- loss-making product groups

### What stood out

The biggest issue was not weak sales, but **revenue converting poorly into profit** in specific areas.

Examples:

- discounts above 20% were associated with much weaker profitability
- Tables generated losses in multiple regions
- Copiers produced the highest total profit
- 2016 and 2017 showed strong sales growth after a slight decline in 2015

**Business question:**  
Where is strong sales activity failing to generate healthy profit?

---

## 02 · Video Game Market Analysis

**Dataset:** Video Game Sales  
**Cleaned rows:** 16,327  
**Main tools:** Python, pandas, Matplotlib, Seaborn

### What was analyzed

- genre performance
- platform rankings
- publisher rankings
- regional sales structure
- yearly sales trends
- top-selling games
- regional genre preferences

### What stood out

Global rankings hide important regional differences.

- Action leads globally and in North America / Europe
- Role-Playing has a much stronger relative position in Japan
- Nintendo leads publishers
- PS2 leads platforms
- 2008 is the strongest year in the dataset

**Business question:**  
How do platform, genre, and regional preferences shape market performance?

---

## 03 · UK E-commerce Customer & Revenue Analysis

**Dataset:** UK Online Retail  
**Raw rows:** 541,909  
**Clean positive-sales rows:** 397,924  
**Identified customers:** 4,339  
**Main tools:** Python, pandas, Jupyter

### What was analyzed

- customer revenue
- order frequency
- average order value
- country contribution
- monthly sales
- cancellations
- basket behavior
- product demand

### What stood out

The business is highly concentrated.

- the UK contributes roughly 82% of cleaned revenue
- November 2011 is the strongest revenue month
- the top 5 customers account for about 11.7% of revenue
- cancellation behavior varies significantly by country

**Business question:**  
Which customers, markets, products, and periods drive revenue — and where does transaction behavior create risk?

---

## What changed from Week 1?

Week 1 was mainly about:

`inspect → clean → explore`

Week 2 moved further into:

`query → compare → validate → interpret`

The main shift was from understanding datasets to using them to answer more specific business questions.

---

## Repository Structure

```text
01-superstore-sql-sales-profit-analysis/
02-video-game-regional-sales-analysis/
03-uk-ecommerce-customer-revenue-analysis/
```

---

## Tools Used

`SQL` `MySQL` `Python` `pandas` `Matplotlib` `Seaborn` `SQLAlchemy` `Jupyter`

---

## Main Takeaway

Different datasets require different methods, but the analytical objective stays the same:

> identify what is driving performance, test whether the pattern is real, and explain why it matters.
