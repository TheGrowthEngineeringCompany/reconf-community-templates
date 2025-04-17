# Journaling Product Analytics Projects in reconfigured

Welcome to your guide for using reconfigured to track and organize product analytics work. Whether you're analyzing user behavior, measuring feature performance, or building dashboards, reconfigured helps you create a journal of your thinking — structured around quests.

This document walks through:

- The core concepts of quests, objectives, and entries
- A quick setup to get started
- Real-world examples of how to structure your product analytics work using reconfigured

## Core Concepts

### Quests

A quest is a loose but defined container for a topic. It's up to you to decide what a quest is, but typically a quest is a question or a desired answer for a question. It could be:

- A full product analytics project
- A deep dive into a specific metric
- A cohort analysis experiment
- A question about user behavior you're trying to answer

Rule of thumb: If you'd want to revisit, share, or reflect on it later — make it a quest.

### Objectives → Sidequests

Each quest can have objectives, which are automatically treated as linked subquests. This allows you to break the work down into smaller chunks without cluttering the main thread.

We recommend a structure like:

```
Main Quest: Analyze New Feature Adoption
├── Objective: Define key metrics
│     → Sidequest: Adoption metrics framework
├── Objective: Segment user behavior
│     → Sidequest: Behavioral cohort analysis
├── Objective: Identify drop-off points
│     → Sidequest: Funnel analysis with heatmaps
```

This keeps your project clean, focused, and expandable as you learn more.

### Entries

Entries are your trail of thought. They can be:

- Long-form notes
- Hypotheses
- SQL queries and results
- Dashboard screenshots
- Metric definitions
- Links and references
- Uploaded files (e.g. charts, heatmaps)
- AI chats and summaries

Be verbose. That's the point. Capture the signal before it fades.

You can use tags on quests to group work by theme, topic, or status (e.g. #retention, #adoption, #funnel, #dashboard).

## Getting Started in 5 Minutes

Here's a quick way to start using reconfigured for your product analytics work right now:

1. **Create your first quest**: "Explore Product Metric Ideas"
2. **Add a simple objective**: "Research 3 potential north star metrics"
3. **Make your first entry**: Write down what you're currently working on or thinking about
4. **Create a second quest** for a specific analysis or dashboard you're building
5. **Link useful resources** you've found as entries

Remember that the goal is to build a useful trail of your thinking that you can return to later.

## Quick Setup

One of the most common product analytics projects is analyzing user retention — let's use that as an example.

Here's a starter layout you can copy-paste into a new product analytics quest:

```markdown
# Quest: Analyze User Retention

**Tags:** #retention

## Summary
Understand why users churn after onboarding and identify key behaviors that correlate with higher retention. Goal is to increase 30-day retention by 15%.

## Objectives
- [ ] Define retention metrics
- [ ] Segment users by acquisition channel
- [ ] Analyze feature usage patterns
- [ ] Build retention cohort heatmap
- [ ] Identify key retention behaviors
- [ ] Present findings to product team
- [ ] Track implemented changes
```

## Example Entries for Your Product Analytics Journal

Below are examples of entries you might create while working on your product analytics projects:

### Entry Types for Retention Analysis Example

#### Daily Log
> Spent the morning cleaning user events data — found inconsistencies in mobile app tracking.
> Created cohort analysis by signup date. Seeing a drop in 30-day retention for users acquired through the new ad campaign.

#### Hypothesis
> I suspect users who complete 3+ actions in their first session have significantly higher retention.
> Will segment by first-session activity count and compare retention curves.

#### Metrics Snapshot
> Weekly retention by cohort:
> Week 1: 45%, Week 2: 28%, Week 3: 22%, Week 4: 18%.
> Seeing much higher drop-off in the first week than expected.

#### Link Reference
**Title:** Retention analytics framework — Amplitude blog  
**Link:** https://amplitude.com/blog/retention-analytics  
**Note:** Great framework for distinguishing between new user and core user retention metrics.

---

## Examples: Product Analytics Quests You Might Create

### Research & Discovery

| Quest Name                              | Purpose                                        |
| --------------------------------------- | ---------------------------------------------- |
| Product metrics benchmarking            | Research industry standards for our metrics    |
| How competitors track engagement        | Reverse engineer competitor analytics approach |
| Mapping customer journey touchpoints    | Identify key moments in the user experience    |

### Data Exploration & Segmentation

| Quest Name                  | Purpose                        |
| --------------------------- | ------------------------------ |
| EDA: mobile app events      | Patterns, frequency, common paths |
| Power user identification   | Define and find our power users |

### Funnel Analysis

| Quest Name                       | Purpose                       |
| -------------------------------- | ----------------------------- |
| Checkout Funnel Analysis         | Find and fix conversion bottlenecks |
| Onboarding Completion Analysis   | Track step-by-step completion rates |

### Behavioral Analysis

| Quest Name                           | Purpose                        |
| ------------------------------------ | ------------------------------ |
| Feature adoption correlation         | Link feature usage to retention |
| Engagement scoring development       | Create weighted engagement score |

### Experimentation & Testing

| Quest Name                               | Purpose                       |
| ---------------------------------------- | ----------------------------- |
| A/B Test: New Pricing Page               | Track metrics across variants |
| Feature flag impact: In-app messaging    | Analyze impact on engagement  |

### Dashboard Development

| Quest Name                        | Purpose                   |
| --------------------------------- | ------------------------- |
| Executive KPI Dashboard           | High-level business health |
| Feature adoption tracking board   | Usage metrics by feature   |

### Learning Projects

| Quest Name               | Purpose                         |
| ------------------------ | ------------------------------- |
| Learn SQL window functions | Link tutorials, examples, notes |
| Experiment: Cohort retention in Looker | Build practice dashboard |

---

## Structuring Objectives & Sidequests

Use **objectives** to break your main quest into manageable pieces.
Each objective becomes a linked quest where you can explore deeply without polluting the main timeline.

### Example Structure

**Main Quest:** Analyze subscription upgrade patterns

**Objectives → Sidequests:**

- Define upgrade metrics → `Subscription upgrade funnel definition`
- Segment users → `User segmentation by plan and usage`
- Build upgrade journey → `User paths before upgrade events`
- Identify triggers → `Correlation analysis: actions vs upgrades`
- Test promotions → `A/B test design for upgrade offers`

This makes your work navigable, modular, and easier to revisit or share.

---

## Additional Entry Types for Product Analytics Work

Here are more examples of entry types that are useful in product analytics projects:

### Visual Documentation

**Uploaded:** retention_heatmap.png  
**Note:** Clear drop-off pattern after day 7. Aligns with end of free trial.

### Pattern Analysis Notes

> Found that users who connect their calendar during onboarding have 2.3x higher 30-day retention.
> Hypothesis: Calendar integration creates immediate value and habit-forming behavior.

### Dashboard Documentation

**Title:** New User Dashboard in Amplitude  
**URL:** amplitude.com/dashboards/123456  
**Note:** Built specifically to track first-week engagement patterns

### AI Assisted Summaries

**Prompt:** Summarize key insights from my retention analysis  
**Response:** Top findings include: 1) Weekend signups retain better, 2) Users who...

### Metric Definition Notes

> Monthly Active Users (MAU) Definition:
> - Users who performed any action in the last 30 days
> - Excludes automated actions and system events
> - Counted as unique by user_id
> Decision: Adding breakdown by acquisition source and plan type to our dashboard.

---

## Common Use Cases for Product Analysts

| When to use reconfigured | Why it helps |
|--------------------------|-------------|
| Building a new metrics framework | Document definitions, calculations, and stakeholder decisions in one place |
| Analyzing user behavior patterns | Track hypotheses, queries, and insights as you discover them |
| Planning and analyzing A/B tests | Maintain test parameters, analysis, and results in a structured way |
| Building product dashboards | Document requirements, metric definitions, and design choices |
| Collaborating across product teams | Keep context separate but searchable across different product initiatives |
| Preparing for stakeholder meetings | Gather data, insights, and recommendations in linked entries |

## Tips from Experienced Product Analysts

- **Use screenshots liberally**: Capture dashboards, charts, and SQL results directly in entries
- **Create daily log entries**: A quick recap of what you analyzed helps maintain context between sessions
- **Link to query repositories**: Reference specific SQL queries when you uncover insights
- **Use structured tags**: Build a consistent tagging system (e.g., #funnel, #retention, #experiment)
- **Create a "Analytics resources" quest**: Collect useful tools, articles, and snippets in a centralized place
- **Document your metric definitions**: Keep clear records of how each metric is calculated and why

## Final Thoughts

Don't overthink structure early on. Start with a single quest. Use objectives to break it down. Let sidequests emerge naturally as your thinking evolves.

The most important habit is consistent capture. Be verbose. Be messy. That's how insights become impact.

Welcome to the journal for the chronically curious.