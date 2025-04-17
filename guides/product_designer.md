# Journaling Product Design Work in reconfigured

Welcome to your guide for using reconfigured to track and organize product design work. Whether you're conducting research, creating wireframes, designing interfaces, or testing usability, reconfigured helps you create a journal of your thinking — structured around quests.

This document walks through:

- The core concepts of quests, objectives, and entries
- A quick setup to get started
- Real-world examples of how to structure your design work using reconfigured

## Core Concepts

### Quests

A quest is a loose but defined container for a topic. It's up to you to decide what a quest is, but typically a quest is a question or a desired answer for a question. It could be:

- A UI/UX design project
- A design system component
- A user research initiative
- A question about user behavior you're trying to answer

Rule of thumb: If you'd want to revisit, share, or reflect on it later — make it a quest.

### Objectives → Sidequests

Each quest can have objectives, which are automatically treated as linked subquests. This allows you to break the work down into smaller chunks without cluttering the main thread.

We recommend a structure like:

```
Main Quest: Redesign Onboarding Experience
├── Objective: Analyze current user flows
│     → Sidequest: User journey mapping
├── Objective: Explore design concepts
│     → Sidequest: Onboarding wireframes
├── Objective: Test with users
│     → Sidequest: Usability test findings
```

This keeps your project clean, focused, and expandable as you learn more.

### Entries

Entries are your trail of thought. They can be:

- Long-form notes
- User research insights
- Sketches and wireframes
- Visual design explorations
- Usability test results
- Links and references
- Uploaded files (e.g. mockups, recordings)
- AI chats and summaries

Be verbose. That's the point. Capture the signal before it fades.

You can use tags on quests to group work by theme, topic, or status (e.g. #research, #wireframe, #ui, #usability).

## Getting Started in 5 Minutes

Here's a quick way to start using reconfigured for your design work right now:

1. **Create your first quest**: "Explore Mobile Navigation Patterns"
2. **Add a simple objective**: "Research 3 alternative navigation approaches"
3. **Make your first entry**: Write down what you're currently working on or thinking about
4. **Create a second quest** for a specific design project you're focused on
5. **Link useful resources** you've found as entries

Remember that the goal is to build a useful trail of your thinking that you can return to later.

## Quick Setup

One of the most common design activities is redesigning a key user flow — let's use that as an example.

Here's a starter layout you can copy-paste into a new design quest:

```markdown
# Quest: Redesign Checkout Experience

**Tags:** #ux #conversion

## Summary
Reimagine the checkout flow to reduce abandonment and improve conversion rates. Focus on simplifying the process, reducing friction points, and creating a more intuitive experience that builds user confidence.

## Objectives
- [ ] Analyze current user behavior
- [ ] Research best practices
- [ ] Map current and ideal user flows
- [ ] Create wireframes and prototypes
- [ ] Conduct usability testing
- [ ] Refine based on feedback
- [ ] Prepare final designs for handoff
```

## Example Entries for Your Design Journal

Below are examples of entries you might create while working on your design projects:

### Entry Types for Checkout Redesign Example

#### Daily Log
> Spent the morning analyzing session recordings of users abandoning checkout. Clear pattern at the payment method step — users hesitate when seeing limited payment options.
> Created three different approaches to displaying payment methods earlier in the flow.

#### User Research Notes
> Usability session with User #4 (Sarah, 32)
> - Began confidently but stalled at shipping options
> - Expected to see delivery date estimates before selecting
> - Quote: "I don't want to choose overnight if it's still going to take 3 days"
> - Abandoned when uncertain about actual delivery timeline
> Key insight: Timing expectations are as important as shipping method names

#### Design Exploration
> Exploring different approaches to the shipping selection UI:
> 1. Radio buttons with delivery date prominently displayed
> 2. Cards with visual timeline indicators
> 3. Simplified 2-option approach (Standard/Express) with guaranteed dates
> Going with option 2 for first prototype — provides most clarity while maintaining visual hierarchy.

#### Link Reference
**Title:** Baymard Institute Checkout Usability Research  
**Link:** https://baymard.com/blog/checkout-flow-design  
**Note:** Great data on ideal form field sequence and error handling approaches that reduce abandonment.

---

## Examples: Product Design Quests You Might Create

### Research & Discovery

| Quest Name                              | Purpose                                        |
| --------------------------------------- | ---------------------------------------------- |
| User interviews: Power users            | Understand advanced user workflows             |
| Competitive analysis: Dashboard designs | Compare approaches and identify opportunities  |
| Heuristic evaluation of current app     | Identify UX issues with existing product       |

### UI Exploration & Design

| Quest Name                  | Purpose                        |
| --------------------------- | ------------------------------ |
| Data visualization redesign | Explore chart types and layouts |
| Mobile navigation patterns  | Test different navigation models |

### Design System Work

| Quest Name                       | Purpose                       |
| -------------------------------- | ----------------------------- |
| Button component system          | Create comprehensive button library |
| Form field guidelines            | Standardize input patterns    |

### User Flows & Interactions

| Quest Name                           | Purpose                        |
| ------------------------------------ | ------------------------------ |
| Onboarding flow redesign             | Map and improve first-use experience |
| Multi-step form interaction patterns | Explore progressive disclosure approaches |

### Testing & Validation

| Quest Name                               | Purpose                       |
| ---------------------------------------- | ----------------------------- |
| Usability testing: New search interface  | Test search UI with real users |
| A/B test proposal: CTA variations        | Design variants for experimentation |

### Visual Design

| Quest Name                        | Purpose                   |
| --------------------------------- | ------------------------- |
| Brand refresh explorations        | Update visual language    |
| Dark mode implementation          | Adapt interface for dark theme |

### Learning & Inspiration

| Quest Name               | Purpose                         |
| ------------------------ | ------------------------------- |
| Animation principles     | Explore motion design techniques |
| Design pattern collection | Archive useful UI patterns for reference |

---

## Structuring Objectives & Sidequests

Use **objectives** to break your main quest into manageable pieces.
Each objective becomes a linked quest where you can explore deeply without cluttering the main timeline.

### Example Structure

**Main Quest:** Redesign dashboard experience

**Objectives → Sidequests:**

- Research needs → `Dashboard user interviews`
- Information architecture → `Dashboard information hierarchy`
- Wireframe layouts → `Dashboard wireframe explorations`
- Component design → `Data visualization components`
- Interaction patterns → `Dashboard interaction model`

This makes your work navigable, modular, and easier to revisit or share.

---

## Additional Entry Types for Product Designers

Here are more examples of entry types that are useful in design work:

### Visual Documentation

**Uploaded:** checkout_wireframes_v2.png  
**Note:** Simplified to 3 steps instead of 5. Combined shipping and payment to reduce perceived complexity.

### Design Critique Notes

> Design review feedback:
> - Navigation icons lack sufficient contrast in dark mode
> - Card components need more distinct hover states
> - Typography hierarchy needs refinement - H2s too similar to H1s
> - Animation timing feels too slow on transitions
> Action items: Update component library with revised specs for all interaction states

### Design Decision Documentation

**Decision:** Using progressive disclosure for advanced settings  
**Rationale:**
> - Usability tests showed 82% of users never change default settings
> - Settings page had lowest comprehension score (4.2/10)
> - Advanced settings created anxiety even for users who didn't need them
> Implementation: Moving advanced options behind "Advanced" toggle with sensible defaults exposed

### AI Assisted Summaries

**Prompt:** Summarize common patterns from our user testing sessions  
**Response:** Across your 6 usability tests, users consistently struggled with three areas: finding the filter controls...

### Accessibility Documentation

> Color contrast audit:
> - Primary text: 7.1:1 (Passes WCAG AAA)
> - Secondary text: 4.8:1 (Passes WCAG AA) 
> - Button text: 3.2:1 (Fails WCAG AA)
> - Error states: 3.5:1 (Passes WCAG AA)
> Action needed: Revise button color to achieve at least 4.5:1 contrast ratio while maintaining brand guidelines

---

## Common Use Cases for Product Designers

| When to use reconfigured | Why it helps |
|--------------------------|-------------|
| Managing design projects | Track research, explorations, decisions, and feedback in one place |
| Documenting user research | Maintain organized records of interviews, observations, and insights |
| Exploring design alternatives | Document different approaches, rationales, and iteration history |
| Conducting usability testing | Capture testing plans, observations, and resulting design changes |
| Building design systems | Document component specifications, usage guidelines, and examples |
| Preparing for design reviews | Gather context, options, and rationales in linked entries |

## Tips from Experienced Designers

- **Use screenshots liberally**: Capture design explorations, inspiration, and interface states
- **Create design documentation entries**: Record the "why" behind design decisions, not just the final output
- **Link to Figma files**: Reference specific frames and versions to track evolution
- **Use structured tags**: Build a consistent tagging system (e.g., #research, #wireframe, #visual)
- **Create a "Design resources" quest**: Collect useful references, patterns, and inspiration
- **Document user feedback verbatim**: Preserve exact quotes to maintain authentic user perspectives

## Final Thoughts

Don't overthink structure early on. Start with a single quest. Use objectives to break it down. Let sidequests emerge naturally as your thinking evolves.

The most important habit is consistent capture. Be verbose. Be messy. That's how explorations become elegant solutions.

Welcome to the journal for the chronically curious.