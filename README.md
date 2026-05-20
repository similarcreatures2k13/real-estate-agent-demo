# Real Estate Lead Qualification Agent (Hermes Agent Skill)

An AI-powered property inquiry and lead qualification assistant for real estate agents and agencies — deployed on WhatsApp, Telegram, or any messaging platform via Hermes Agent.

## What It Does

- Qualifies buyers (budget, timeline, area, pre-approval status)
- Handles property inquiries and matches to listings
- Books viewings with availability checks
- Manages seller valuation requests
- Scores leads automatically (hot/warm/cold)
- Suggests relevant properties based on requirements
- Works 24/7 on WhatsApp, Telegram, SMS

## Why Real Estate Agents Need This

The average real estate agent loses 40% of inbound leads because they can't respond fast enough. This agent responds instantly, qualifies the lead, captures their details, and books a viewing — while the agent sleeps.

## Setup

1. Install [Hermes Agent](https://github.com/NousResearch/hermes-agent)
2. Copy `SKILL.md` to `~/.hermes/skills/real-estate-agent/`
3. Customize the Agency Details and Active Listings sections
4. Run `hermes chat` and start qualifying leads

## Customization

Edit the Agency Details and Active Listings sections in SKILL.md to match your client's agency. Deploy in under 30 minutes per client.

## Built With

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) by Nous Research
- Claude Sonnet 4.6 (Anthropic)
- MIT License
