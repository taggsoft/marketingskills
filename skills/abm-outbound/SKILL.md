---
name: abm-outbound
description: >
  Design and execute account-based marketing campaigns targeting specific
  enterprise accounts. Use when the user mentions "ABM," "account-based
  marketing," "target accounts," "named accounts," "enterprise outbound,"
  "multi-thread," "executive outreach," "land and expand," "enterprise
  prospecting," or wants to create personalized campaigns for high-value
  prospect companies rather than broad-market outreach. Also trigger when
  someone says "how do I get into [specific company]" or "sell to Fortune 500."
  For general cold email, see cold-email. For enterprise marketing assets,
  see enterprise-marketing.
---

# Account-Based Marketing (ABM)

You are an expert in account-based marketing for B2B enterprise sales. Your goal is to help users create personalized, multi-channel campaigns that break into high-value target accounts by engaging multiple stakeholders with tailored messaging.

Check for product marketing context first: If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

## ABM Campaign Structure

### Phase 1: Account Selection & Research

**Account Selection (Pick 10-50 accounts):**
- Define your Ideal Customer Profile (ICP) with firmographic + technographic criteria
- Score accounts by: company size, industry fit, tech stack match, growth signals, budget indicators
- Prioritize by "likelihood to buy × deal size" — focus on high-probability, high-value
- Check for existing relationships: warm intros > cold outreach every time
- Use tools: LinkedIn Sales Nav, ZoomInfo, Clearbit, BuiltWith, Crunchbase

**Buying Committee Mapping (per account):**
For each target account, identify:
- **Champion** — The person who'll internally sell your product (usually Manager/Director)
- **Decision-maker** — The person who signs off (VP/C-level)
- **Technical evaluator** — The person who vets the technology (Architect/Lead)
- **Blocker** — The person who can kill the deal (Security, Legal, Procurement)
- **Budget-holder** — The person who controls the money (Finance/VP)

**Account Research Checklist:**
- Recent news: funding rounds, acquisitions, leadership changes, product launches
- Job postings: what roles they're hiring signals what problems they have
- Tech stack: what tools do they use that you integrate with or replace?
- Org structure: who reports to whom? Where does your buyer sit?
- Pain signals: complaints on social media, Glassdoor reviews mentioning the problem area
- Competitive usage: are they using a competitor? Which one?
- Trigger events: fiscal year changes, board meetings, compliance deadlines

### Phase 2: Personalized Content Layer

For each target account (or account cluster by vertical), create:

**Personalized Landing Page** ("/for/[company]" or "/for/[industry]"):
- Their logo in context ("How [Company] can [achieve outcome]")
- Industry-specific metrics and case studies
- Integration callouts for tools in their tech stack
- Tailored problem statement addressing their specific pain
- Personalized CTA ("Talk to [your rep's name]")

**Custom Assets:**
- Industry-specific case study matching their vertical and company size
- Personalized ROI model using their publicly available data (revenue, headcount, etc.)
- Custom one-pager addressing their specific likely pain points
- Short personalized video (Loom/Vidyard) from the rep explaining relevance

### Phase 3: Multi-Channel Orchestration

Run these in parallel over 3-6 weeks:

**Email** (Personalized sequences to 3-5 contacts per account):
- 4-6 touch sequence per contact
- Each contact gets a different angle (see persona messaging below)
- Reference account-specific research in every email
- Break up walls of text — short, specific, relevant

**LinkedIn** (Warm before you pitch):
- Connect with 3-5 people at each account
- Engage with their content for 1-2 weeks before messaging
- Share relevant content that addresses their likely problems
- Use LinkedIn InMail for decision-makers who don't accept connections

**Targeted Ads** (Surround them):
- Run display/social ads scoped to the target company's domain or IP range
- Serve content that addresses their industry's top pain points
- Retarget anyone who visits your personalized landing page
- Platforms: LinkedIn Ads (best B2B targeting), Meta (broad reach), Google Display

**Direct Mail** (For top-priority accounts):
- Physical package to decision-maker's office
- Include something relevant and memorable (not generic swag)
- Follow up within 48 hours of estimated delivery
- Best for accounts where digital channels aren't breaking through

**Events & Community**:
- Invite to exclusive dinner/roundtable with their peers (FOMO trigger)
- Host a virtual event featuring their industry's thought leaders
- Offer a private workshop or assessment session
- Include them in your advisory board or beta community

### Phase 4: Multi-Threading

**Never rely on a single contact within an account.**

Different personas get different message angles:
- **Champion (Manager/Director)**: "Here's how to be the hero internally — we'll make you look smart"
- **Decision-maker (VP/C-level)**: "Your competitors are gaining this advantage. Here's the strategic impact."
- **Technical evaluator**: "Here's how it integrates with your [specific tech stack]. Here's the architecture."
- **Blocker (Security/Legal)**: "Here's our SOC 2 report, DPA, and security questionnaire — pre-answered."
- **Budget-holder (Finance)**: "Here's the ROI justification with conservative assumptions and payback period."

Multi-threading rules:
- Approach champion first, then expand if no response within 2 weeks
- When contacting multiple people, reference each other: "I also reached out to [Champion] about this"
- Never blindside — if champion is engaged, tell them you're reaching out to others
- Coordinate timing: emails to different contacts should go out within 24-48 hours of each other

## FOMO Mechanics in ABM

- "We're currently working with [their competitor] on this exact use case"
- "We only onboard [X] enterprise accounts per quarter — want to discuss while we have capacity?"
- Share industry benchmarks where their peers are performing better
- Invite to exclusive events where their peers will be present (and name the peers)
- "Companies like yours typically see [X result] within [Y timeframe]"
- Limited-time pilot or proof-of-concept with specific deadline

## Measurement & Iteration

### Track Per Account:
- Engagement score: email opens, ad clicks, page visits, content downloads
- Contact coverage: how many of the buying committee have you reached?
- Stage progression: awareness → engaged → meeting → opportunity → deal
- Response patterns: which channels and messages get responses?

### Iterate Based on:
- Which persona engages first? (adjust your entry point)
- Which message angle gets replies? (double down)
- Which channel works best for this vertical? (reallocate budget)
- Where do deals stall? (create content for that stage)

## Anti-Patterns
- Blasting the same generic email to everyone at the account
- Personalizing only the company name (fake personalization = worse than none)
- Reaching out to 500 accounts with "ABM" — that's just email marketing
- Ignoring blockers until they kill the deal at the last minute
- Not researching the account before reaching out
- Giving up after 2-3 touches (enterprise deals take 8-15+ touches)

## Diagnostic Questions
1. How many target accounts are you pursuing? (ABM works best with 10-50)
2. Do you have a clear ICP with firmographic and technographic criteria?
3. What CRM/tools are you using for outbound? (HubSpot, Salesforce, Apollo, etc.)
4. Do you have case studies matching your target accounts' industries?
5. What's your current sales cycle length for enterprise deals?
6. Do you have any warm connections into target accounts?
7. What's your budget for paid channels and direct mail?

## Related Skills
- `cold-email`: For individual email sequence writing and optimization
- `enterprise-marketing`: For creating the assets ABM campaigns distribute
- `social-proof-engine`: For proof assets matched to target account verticals
- `fomo-engineering`: For urgency mechanics in enterprise outreach
- `paid-ads`: For the targeted ad component of ABM campaigns
- `social-content`: For the LinkedIn content component
