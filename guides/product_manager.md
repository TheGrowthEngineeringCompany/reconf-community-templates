# Journaling Product Management Work in reconfigured

Welcome to your guide for using reconfigured to track and organize product management work. Whether you're defining strategy, gathering requirements, coordinating development, or analyzing outcomes, reconfigured helps you create a journal of your thinking — structured around quests.

This document walks through:

- The core concepts of quests, objectives, and entries
- A quick setup to get started
- Real-world examples of how to structure your product management work using reconfigured

## Core Concepts

### Quests

A quest is a loose but defined container for a topic. It's up to you to decide what a quest is, but typically a quest is a question or a desired answer for a question. It could be:

- A feature development project
- A product strategy exploration
- A user research initiative
- A question about user behavior you're trying to answer

Rule of thumb: If you'd want to revisit, share, or reflect on it later — make it a quest.

### Objectives → Sidequests

Each quest can have objectives, which are automatically treated as linked subquests. This allows you to break the work down into smaller chunks without cluttering the main thread.

We recommend a structure like:

```
Main Quest: Develop User Onboarding Flow
├── Objective: Research current drop-offs
│     → Sidequest: Onboarding funnel analysis
├── Objective: Design improved experience
│     → Sidequest: Onboarding wireframes
├── Objective: Test with users
│     → Sidequest: Usability test findings
```

This keeps your project clean, focused, and expandable as you learn more.

### Entries

Entries are your trail of thought. They can be:

- Long-form notes
- User interviews
- Requirements documentation
- Stakeholder feedback
- Analytics insights
- Links and references
- Uploaded files (e.g. wireframes, roadmaps)
- AI chats and summaries

Be verbose. That's the point. Capture the signal before it fades.

You can use tags on quests to group work by theme, topic, or status (e.g. #feature, #research, #strategy, #experiment).

## Getting Started in 5 Minutes

Here's a quick way to start using reconfigured for your product management work right now:

1. **Create your first quest**: "Explore Q3 Feature Priorities"
2. **Add a simple objective**: "Research 3 potential solutions to user pain point"
3. **Make your first entry**: Write down what you're currently working on or thinking about
4. **Create a second quest** for a specific feature or research initiative you're focused on
5. **Link useful resources** you've found as entries

Remember that the goal is to build a useful trail of your thinking that you can return to later.

## Quick Setup

One of the most common product management activities is developing a new feature — let's use that as an example.

Here's a starter layout you can copy-paste into a new product management quest:

```markdown
# Quest: Develop Team Collaboration Feature

**Tags:** #feature #collaboration

## Summary
Create a new feature that allows users to collaborate on documents in real-time with their teams. Focus on intuitive sharing, permission management, and activity tracking to strengthen our product's team use case.

## Objectives
- [ ] Research user collaboration needs
- [ ] Analyze competitive solutions
- [ ] Define requirements and scope
- [ ] Create wireframes and user flows
- [ ] Validate with customer feedback
- [ ] Finalize specifications
- [ ] Coordinate development and testing
```

## Example Entries for Your Product Management Journal

Below are examples of entries you might create while working on your product management activities:

### Entry Types for Feature Development Example

#### Daily Log
> Met with engineering to discuss technical feasibility of real-time collaboration. WebSockets would require significant backend changes.
> Exploring alternative approach using short polling that could deliver 80% of the value with 40% of the effort.

#### User Research Notes
> User Interview: Sarah (Marketing Team Lead at Enterprise Co.)
> - Currently uses 3 different tools for collaboration
> - Pain point: Version control becomes "a nightmare" with multiple contributors
> - Quote: "I spend more time figuring out who changed what than actually collaborating"
> - Would strongly prefer integrated solution over current workflow
> Key insight: Detailed change history is as important as the real-time aspect

#### Requirements Documentation
> Collaboration Feature - MVP Requirements:
> - Users can invite team members via email or link
> - Permission levels: View, Comment, Edit, Admin
> - Real-time presence indicators showing who's viewing
> - Basic conflict resolution for simultaneous edits
> - Activity feed showing who changed what
> Non-MVP (future): Chat, comment threads, advanced permissions

#### Link Reference
**Title:** Real-time Collaboration UX Patterns  
**Link:** https://www.nngroup.com/articles/synchronous-collaboration/  
**Note:** Great examples of how Google Docs and Figma handle presence indicators and conflict resolution.

---

## Examples: Product Management Quests You Might Create

### Discovery & Research

| Quest Name                              | Purpose                                        |
| --------------------------------------- | ---------------------------------------------- |
| User research: Mobile usage patterns    | Understand how users interact with mobile app  |
| Competitive analysis: Collaboration tools | Compare features and positioning strategies    |
| Problem exploration: Team workflows     | Map current processes and pain points         |

### Strategy & Planning

| Quest Name                  | Purpose                        |
| --------------------------- | ------------------------------ |
| Q3 Product Roadmap          | Prioritize and sequence initiatives |
| Pricing strategy review     | Analyze pricing models and options |

### Feature Development

| Quest Name                       | Purpose                       |
| -------------------------------- | ----------------------------- |
| Team permissions system          | Design and implement permission model |
| Notification system redesign     | Improve engagement and relevance |

### Experimentation & Validation

| Quest Name                           | Purpose                        |
| ------------------------------------ | ------------------------------ |
| Onboarding A/B test                  | Compare conversion between flows |
| Feature adoption research            | Understand usage patterns and barriers |

### Cross-functional Coordination

| Quest Name                               | Purpose                       |
| ---------------------------------------- | ----------------------------- |
| Marketing launch plan: Team features     | Coordinate messaging and rollout |
| Engineering handoff: Search improvements | Ensure clear technical requirements |

### Metrics & Analytics

| Quest Name                        | Purpose                   |
| --------------------------------- | ------------------------- |
| Engagement metrics framework      | Define KPIs for core features |
| Retention driver analysis         | Identify key behaviors that predict retention |

### Professional Development

| Quest Name               | Purpose                         |
| ------------------------ | ------------------------------- |
| Product management resources | Collect articles, books, and tools |
| Experiment: Jobs-to-be-Done framework | Apply JTBD to feature planning |

---

## Structuring Objectives & Sidequests

Use **objectives** to break your main quest into manageable pieces.
Each objective becomes a linked quest where you can explore deeply without cluttering the main timeline.

### Example Structure

**Main Quest:** Launch subscription model

**Objectives → Sidequests:**

- Research pricing → `Pricing benchmarks and elasticity`
- Define tiers → `Feature packaging by tier`
- Design upgrade experience → `Conversion flow design`
- Plan grandfathering strategy → `Existing user transition plan`
- Coordinate go-to-market → `Cross-functional launch plan`

This makes your work navigable, modular, and easier to revisit or share.

---

## Additional Entry Types for Product Managers

Here are more examples of entry types that are useful in product management:

### Decision Documentation

**Decision:** Prioritize mobile web over native app development  
**Context:** 
> - 78% of current users access via desktop
> - Mobile web can address most use cases with lower investment
> - Analytics shows growing mobile traffic but mostly for viewing, not editing
> - Resource constraints prevent building both simultaneously
> Trade-offs: Less performance and limited offline capabilities, but faster time to market and broader reach.

### Stakeholder Feedback

**Meeting with:** Sales Leadership Team  
**Date:** June 15, 2024  
**Key Requests:**
> - Need better competitive comparison materials
> - Enterprise customers asking for SSO and advanced audit logs
> - Pricing objections around per-seat model vs. flat pricing
> - Current close blockers: security documentation, admin controls
> Insights for roadmap: Security and admin features may have higher revenue impact than planned UI improvements

### Specification Documentation

**Title:** Collaboration Feature - Technical Specification  
**Version:** 2.4  
**Key Components:**
> - Permission Model (RBAC with 4 levels)
> - Real-time Presence (WebSocket API)
> - Conflict Resolution (Last-write wins with notification)
> - Activity Tracking (Event system with read receipts)
> - Notification System (In-app and email digests)
> Implementation dependencies: User graph service, notification service upgrades

### AI Assisted Summaries

**Prompt:** Summarize key themes from our user interviews about collaboration needs  
**Response:** Across your 8 interviews with team leads, three consistent themes emerge: version control confusion...

### Experiment Results

> Feature Adoption Experiment Results:
> - In-app guide: 24% engagement, 8% full activation
> - Email onboarding sequence: 32% open rate, 12% activation
> - Combination approach: 37% activation rate
> Learning: Sequential touchpoints across channels most effective. Timing between touchpoints (3 days) seems optimal balance between urgency and annoyance.

---

## Common Use Cases for Product Managers

| When to use reconfigured | Why it helps |
|--------------------------|-------------|
| Managing feature development | Track requirements, decisions, feedback, and progress in one place |
| Documenting user research | Maintain organized records of interviews, usability tests, and insights |
| Planning product roadmap | Capture options considered, prioritization decisions, and strategic context |
| Running experiments | Document hypotheses, test designs, results, and follow-up actions |
| Coordinating cross-functional work | Keep context, deliverables, and dependencies clear across teams |
| Preparing for stakeholder meetings | Gather data, options, and recommendations in linked entries |

## Tips from Experienced Product Managers

- **Use screenshots liberally**: Capture wireframes, analytics dashboards, and competitor features
- **Create decision logs**: Document not just what was decided, but why and what alternatives were considered
- **Link to related artifacts**: Connect to PRDs, design files, and technical specifications
- **Use structured tags**: Build a consistent tagging system (e.g., #feature, #research, #decision)
- **Create a "Product management resources" quest**: Collect useful frameworks, articles, and tools
- **Document customer verbatims**: Directly quote users to maintain authentic voice of customer

## Final Thoughts

Don't overthink structure early on. Start with a single quest. Use objectives to break it down. Let sidequests emerge naturally as your thinking evolves.

The most important habit is consistent capture. Be verbose. Be messy. That's how requirements become reality.

Welcome to the journal for the chronically curious.