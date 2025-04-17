# Journaling Data Analysis Projects in reconfigured

Welcome to your guide for using reconfigured to track and organize data analysis work. Whether you're building dashboards, creating reports, or conducting ad-hoc analyses, reconfigured helps you create a journal of your thinking — structured around quests.

This document walks through:

- The core concepts of quests, objectives, and entries
- A quick setup to get started
- Real-world examples of how to structure your data analysis work using reconfigured

## Core Concepts

### Quests

A quest is a loose but defined container for a topic. It's up to you to decide what a quest is, but typically a quest is a question or a desired answer for a question. It could be:

- A full analytical project
- A business question exploration
- A dashboard development project
- A specific data puzzle you're trying to solve

Rule of thumb: If you'd want to revisit, share, or reflect on it later — make it a quest.

### Objectives → Sidequests

Each quest can have objectives, which are automatically treated as linked subquests. This allows you to break the work down into smaller chunks without cluttering the main thread.

We recommend a structure like:

```
Main Quest: Analyze Customer Churn Drivers
├── Objective: Explore customer data
│     → Sidequest: Customer segmentation analysis
├── Objective: Identify behavioral patterns
│     → Sidequest: Pre-churn activity analysis
├── Objective: Build prediction model
│     → Sidequest: Key churn indicators dashboard
```

This keeps your project clean, focused, and expandable as you learn more.

### Entries

Entries are your trail of thought. They can be:

- Long-form notes
- SQL queries
- Analysis results
- Data visualization drafts
- Stakeholder questions
- Links and references
- Uploaded files (e.g. charts, presentations)
- AI chats and summaries

Be verbose. That's the point. Capture the signal before it fades.

You can use tags on quests to group work by theme, topic, or status (e.g. #dashboard, #finance, #segmentation, #adhoc).

## Getting Started in 5 Minutes

Here's a quick way to start using reconfigured for your data analysis work right now:

1. **Create your first quest**: "Explore Q2 Business Metrics"
2. **Add a simple objective**: "Analyze 3 key performance trends"
3. **Make your first entry**: Write down what you're currently working on or thinking about
4. **Create a second quest** for a specific analysis or dashboard you're building
5. **Link useful resources** you've found as entries

Remember that the goal is to build a useful trail of your thinking that you can return to later.

## Quick Setup

One of the most common data analysis projects is building an executive dashboard — let's use that as an example.

Here's a starter layout you can copy-paste into a new data analysis quest:

```markdown
# Quest: Build Executive KPI Dashboard

**Tags:** #dashboard #executive

## Summary
Create a comprehensive yet focused dashboard for the executive team to track business health across departments. Should provide high-level metrics with drill-down capability for deeper insights.

## Objectives
- [ ] Gather requirements from stakeholders
- [ ] Define key metrics and dimensions
- [ ] Source and validate data
- [ ] Design dashboard layout
- [ ] Build initial version in Tableau
- [ ] Collect feedback and iterate
- [ ] Document data sources and calculations
```

## Example Entries for Your Data Analysis Journal

Below are examples of entries you might create while working on your data analysis projects:

### Entry Types for Dashboard Example

#### Daily Log
> Spent the morning cleaning revenue data — found discrepancies between marketing and finance reporting.
> Traced it to currency conversion timing. Aligned on using finance numbers as single source of truth.

#### Analysis Notes
> Exploring MoM revenue trends for the past 12 months.
> - Overall growth: 3.2% monthly average
> - Product A: Strong seasonality with Q4 peaks
> - Product B: Steady growth but slowing (8% → 4%)
> Will try cohort analysis next to see if customer vintage explains the slowdown.

#### SQL Query
> Query to calculate customer lifetime value by acquisition channel:
> ```sql
> SELECT 
>   acquisition_channel,
>   COUNT(DISTINCT customer_id) AS customers,
>   AVG(lifetime_revenue) AS avg_ltv,
>   PERCENTILE_CONT(0.5) WITHIN GROUP (ORDER BY lifetime_revenue) AS median_ltv
> FROM customer_metrics
> GROUP BY acquisition_channel
> ORDER BY avg_ltv DESC;
> ```
> Key insight: Organic search has 3x higher LTV than paid social, despite fewer customers.

#### Link Reference
**Title:** Effective Data Storytelling Guide  
**Link:** https://www.storytellingwithdata.com/blog/2020/1/27/what-is-a-kpi  
**Note:** Great framework for selecting executive metrics that drive decisions rather than just reporting.

---

## Examples: Data Analysis Quests You Might Create

### Business Questions

| Quest Name                              | Purpose                                        |
| --------------------------------------- | ---------------------------------------------- |
| What's driving customer churn?          | Analyze patterns in churned customers          |
| Marketing channel ROI                   | Compare effectiveness across spend categories  |
| Product feature usage correlation       | Link feature adoption to retention outcomes    |

### Dashboard Development

| Quest Name                  | Purpose                        |
| --------------------------- | ------------------------------ |
| Sales Performance Dashboard | Track pipeline, conversion, forecasts |
| Marketing Attribution Board | Channel performance visualization |

### Data Discovery

| Quest Name                       | Purpose                       |
| -------------------------------- | ----------------------------- |
| Customer Segmentation Analysis   | Identify behavioral clusters  |
| Pricing Elasticity Exploration   | Test price sensitivity hypotheses |

### Reporting & Automation

| Quest Name                           | Purpose                        |
| ------------------------------------ | ------------------------------ |
| Monthly Executive Report            | Template and process for recurring reporting |
| Marketing Campaign Tracker           | Automated performance monitoring |

### Data Deep Dives

| Quest Name                               | Purpose                       |
| ---------------------------------------- | ----------------------------- |
| Conversion Funnel Breakdown              | Step-by-step analysis of drop-offs |
| Seasonal Trend Analysis                  | Multi-year pattern identification |

### Tool & Process Development

| Quest Name                        | Purpose                   |
| --------------------------------- | ------------------------- |
| Looker Block Development          | Reusable analysis components |
| A/B Test Analysis Framework       | Standardized evaluation methodology |

### Learning Projects

| Quest Name               | Purpose                         |
| ------------------------ | ------------------------------- |
| Learn R for Statistical Analysis | Practice exercises and notes |
| Tableau Advanced Visualizations  | Techniques for complex charts |

---

## Structuring Objectives & Sidequests

Use **objectives** to break your main quest into manageable pieces.
Each objective becomes a linked quest where you can explore deeply without polluting the main timeline.

### Example Structure

**Main Quest:** Marketing channel optimization

**Objectives → Sidequests:**

- Establish baseline metrics → `Current CAC and LTV by channel`
- Deep-dive top channels → `Google Ads performance analysis`
- Analyze conversion paths → `Multi-touch attribution model`
- Test budget scenarios → `Spend reallocation modeling`
- Generate recommendations → `Channel strategy recommendations`

This makes your work navigable, modular, and easier to revisit or share.

---

## Additional Entry Types for Data Analysis Work

Here are more examples of entry types that are useful in data analysis projects:

### Visualization Documentation

**Uploaded:** conversion_funnel_chart.png  
**Note:** Shows 42% drop-off between signup and first action. Significantly higher on mobile (62%).

### Insight Documentation

> Customer retention finding:
> Users who connect at least one integration in the first week have 78% higher 90-day retention.
> The effect is strongest for small business segment (2.3x difference).
> Recommendation: Prioritize first-week integration experience in onboarding flow.

### Stakeholder Meeting Notes

**Meeting:** Business Review with VP Sales  
**Date:** June 15, 2024  
**Key Questions:**
> - Why did East region underperform in Q2?
> - Are enterprise deals taking longer to close?
> - Which sales reps are most effective with product-led leads?
> Action Items: Create territory-adjusted performance dashboard, analyze sales cycle by lead source

### AI Assisted Summaries

**Prompt:** Summarize key insights from our customer segmentation analysis  
**Response:** Your analysis identified four distinct segments: power users (12%), occasional users (45%)...

### Methodology Notes

> Cohort analysis approach:
> - Defining cohorts by signup month
> - Tracking retention on a 30-day rolling basis
> - Excluding users with less than 30 days tenure
> - Normalizing for seasonal effects using YoY comparison
> Result: After controlling for seasonality, we still see a 12% improvement in retention for cohorts after the new onboarding flow launched.

---

## Common Use Cases for Data Analysts

| When to use reconfigured | Why it helps |
|--------------------------|-------------|
| Defining metrics and KPIs | Document definitions, calculations, and business context in one place |
| Exploring complex datasets | Track your queries, findings, and next questions methodically |
| Building data visualizations | Document design choices, stakeholder feedback, and iterations |
| Answering business questions | Maintain context and trail of analysis as you explore |
| Preparing for data reviews | Gather insights, visualizations, and talking points in linked entries |
| Working across multiple data sources | Keep query references and join logic accessible |

## Tips from Experienced Data Analysts

- **Use screenshots liberally**: Capture visualization drafts, interesting data patterns, and error messages
- **Create daily log entries**: Track what you're analyzing to maintain context between sessions
- **Link to query repositories**: Reference specific SQL or notebooks when you make discoveries
- **Use structured tags**: Build a consistent tagging system (e.g., #finance, #customer, #forecast)
- **Create a "Data dictionary" quest**: Collect field definitions, business rules, and calculation methodologies
- **Document data quirks**: Keep notes on data limitations, special cases, and workarounds

## Final Thoughts

Don't overthink structure early on. Start with a single quest. Use objectives to break it down. Let sidequests emerge naturally as your thinking evolves.

The most important habit is consistent capture. Be verbose. Be messy. That's how questions become insights.

Welcome to the journal for the chronically curious.