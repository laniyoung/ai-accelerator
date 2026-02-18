# Day 3 Demo Plan: One-Pager with AI
**Session Lead: Lani Young**
**Time: 10 minutes**
**Date: Wednesday 02.18.26**

---

## Demo Flow Overview

1. **Why This Matters** (1 min)
2. **The 4Ds Framework** (2 min)
3. **Opening Prompt** (1 min)
4. **Live Interaction** (4-5 min)
5. **Toolkit + Send Off** (1-2 min)

---

## Why This Step Matters Most

**This is the most important step in the entire product development process.**

Oftentimes we get into debates about the solutions, the copy, the UX—and actually it's rooted in a disagreement about the problem and the problems we're trying to solve. If we had spent more time really aligning on the problem to solve and agreeing on that problem, then the rest of it would be smooth sailing.

**I can't emphasize enough how important I think this step is.** Spend time in the problem space. Convince yourself and understand what is the root cause of the problem and what is the problem to solve. That will then set you up for a better opportunity to step into the solution space.

**That's why it's so valuable to use AI at this stage.**

---

## Your Goal Today

Show PMs how to work **WITH** Claude (not just use Claude) to create a compelling one-pager that defines the problem and gets buy-in from leadership. This isn't about prompting tricks—it's about teaching them to maximize both their brain AND AI's capabilities.

---

## The Setup (What You're Walking Into)

- **Their task**: Walk out in 1 hour with a really solid one-pager that defines the problem and sets them up for a review with leadership to get buy-in that this is a problem worth solving

- **What they have**:
  - Customer insights brief from Day 2 (sentiments, scale, quotes)
  - Their own brain (the most powerful tool)
  - HCP data sources, competitive research, Jira, Confluence, GitHub
  - One-pager template
  - Claude as their AI assistant who can find/source information, help write, and play different stakeholder roles to help them refine before sharing

- **Your demo problem**: Credits as a payment method

---

## The 4Ds Framework (2 minutes)

**Key Takeaway:**

When you utilize this framework with any AI, it can help you to not only just 'prompt better' but really get the most out of your interactions and produce better work overall. I'll show you how I think about the 4Ds when I engage with Claude.

### The Four Ds:

**DELEGATE** - Decide what tasks to assign to Claude
- Send Claude to find data, research competitors, synthesize information
- YOU decide what needs to be done

**DESCRIBE** - Communicate clearly with Claude
- Set clear guardrails, give context, be specific
- Bad description = bad output

**DISCERN** - Critically evaluate what Claude gives you
- Don't copy/paste wholesale
- Ask: is this right? compelling? what's missing?
- Redirect if needed

**DILIGENCE** - Take responsibility for what you do with AI
- Ensure accuracy and quality
- Consider ethics
- Own the final work product

_Source: Anthropic AI Fluency Framework. Dakan, R., & Feller, J. (2024). AI Fluency: Frameworks and Foundations. Available at: [anthropic.com/ai-fluency](https://www.anthropic.com/ai-fluency)_

---

## Live Demo: The Workflow (5-6 minutes)

### Opening Prompt

**[Show this prompt on screen]:**

```
Hey Claude, I'm writing a one-pager today and I need it to be really great and really solid.

For me, a one-pager is a clear and tight articulation of the problem we're solving—establishing not only that it's a real problem, but that it's a problem worth solving because there's real customer pain. Customer pain at scale. And there's customer and business value if we can solve it.

Today I'm writing a one-pager about using credits as a payment method, and I want you to partner with me to write it together.

I also want you to push me—poke holes, challenge me, help me make it better.

Before we dig in, let me orient you to what I have:

Resources:

- Insights brief:
  ~/dev/ai-accelerator/credits/insights_brief.md

- Credits research brief:
  https://laniyoung.github.io/credits-research-brief/research-brief.html

- One-pager template:
  https://housecall.atlassian.net/wiki/spaces/PM/pages/1738703352/Template+Project+Title+1+Pager
  (use the Atlassian MCP to access this)

- Plus:
  Access to Snowflake, competitive research, and other internal tools if we need them

Start by familiarizing yourself with all of this. Once you've digested everything and you're ready, come back to me and we can get started.
```

**What to say:**

Notice what I'm doing here:
- Setting up a **partnership**, not just asking Claude to write something
- Defining what "great" looks like for me—problem worth solving, customer pain at scale, business value
- Explicitly asking Claude to **push me and challenge me**
- Giving Claude access to all my resources—insights, template, data
- Giving Claude **agency**: "come back when you're ready"

**This demonstrates DELEGATE and DESCRIBE from the 4Ds.**

---

### Follow-Up Prompt 1: Invite Questions

```
Before we get started, what are some of the initial questions you have for me or things that you would want to know before we kick off this working session?
```

**What to say:**

I'm inviting Claude to ask **me** questions. This shows partnership—Claude has agency, not just taking orders. This also helps me understand what Claude thinks is missing.

**This demonstrates DELEGATE (delegating the question-asking) and sets up better DESCRIBE.**

---

### Follow-Up Prompt 2: Collaborative Gap Analysis

```
Now given what we have already and looking at the one-pager template, what are the pieces that you really think we need to dive into to really articulate this problem more fully and demonstrate that it is a true problem to solve and it's a problem worth tackling?

Off the top of my head I already have a sense that we're missing some things around:
  - data
  - value
  - scale of the problem
  - business value to Housecall
  - things like that

There are some pieces that I just haven't really worked through and thought through yet, so I don't feel ready to write this one-pager.

But I'm curious from your perspective: what are the pieces that we really need to work through and the elements that we're just missing?
```

**What to say:**

See what I'm doing? I'm being **vulnerable**—'I don't feel ready.' I'm giving Claude some of my thinking but asking for more. We're thinking **together**.

**This demonstrates all three Ds: DELEGATE (gap analysis), DESCRIBE (being clear about uncertainty), and DISCERN (inviting Claude to help me see what's missing).**

**From here, I'll respond authentically to what Claude says. I'm not scripting this—I want to show you how I actually work.**

---

## Toolkit: Ways Claude Can Help

**Key Takeaway:**

After the live demo, send them off with these tools so they understand the full range of ways Claude can support their work.

### The Tools:

**Data & Snowflake MCP**
- There's a Snowflake MCP—some of you have already connected it
- Claude can help you write and run queries to quantify the problem

**Screenshots & Visual Evidence**
- Claude in Chrome can take screenshots, navigate your product, and show current state to make your case visual

**Competitive Research**
- Claude can research how others have tackled this problem or the scope of similar problems

**Role-Playing Reviewers**
- Have Claude read your one-pager as an engineer, your boss, a designer, an executive—and push back from their perspective

**Context-Aware Role-Playing**
- I've even had Claude read my Slack history with Ethan to understand how he asks questions, then pretend to be Ethan and review my doc

**Confluence & Jira Access**
- Use Atlassian MCP to read templates, pull in context, understand existing work

---

## Your Closing Message

"You have one hour. Remember:

1. **Your brain is the most powerful tool** — Claude can't do your strategic thinking

2. **Use the 4Ds** — Delegate, Describe, Discern, Diligence

3. **Claude can help at every step** — data, screenshots, competitive research, role-playing

4. **This is the most important step** — align on the problem, and the rest gets easier

You've got this. Go make a solid one-pager."

---

## Key Reminders for You (Lani)

### What Matters Most:
- **Emphasize the partnership model** - this is not "Claude writes it for you"
- **Emphasize their brain is most important** - AI can't replace strategic thinking
- **Show the pattern, not the whole process** - you can't do everything in 10 min, so show HOW to approach it
- **The 4Ds are the framework** - come back to this throughout
- **Do it LIVE and REAL** - no scripting, show authentic interaction

### What NOT to Do:
- Don't try to complete a whole one-pager in 10 minutes
- Don't just show them typing prompts - explain the THINKING behind each one
- Don't script or fake the demo - let it be real

### Tools to Mention:
- **Atlassian MCP** - for reading Confluence
- **Claude in Chrome** - browser extension or MCP for screenshots/navigation
- **Snowflake MCP** - for data queries

---

## Breakout Room Challenge (For Reference)

After your demo, they'll work on their own one-pagers for 40 minutes.

**The role-player technique:** Have Claude take on roles (EM, PMM, designer, manager, exec) and review the one-pager from each perspective. This helps them pressure-test before presenting to real people.

Just mention quickly: _"After you finish your one-pager, have Claude review it as your EM, your manager, Ethan—and push back. That's one of the most powerful uses of AI for product thinking."_

---

## Final Thought

This session is where they go from raw insights to a clear problem statement that gets alignment. If the one-pager is weak, the rest of the week suffers. Your job is to show them how to maximize BOTH their brain AND Claude's capabilities to make something great.

You've got this.
