**Independent developer | AI-assisted engineering | Market intelligence | Wearable technology**

I'm an independent developer based in British Columbia, Canada, building practical tools to make complex information easier to understand and AI-assisted software development more dependable.

Much of my work starts with a problem I've encountered myself: too much information scattered across different places, repetitive tasks that should be automated, or promising AI tools that still require considerable human supervision.

I'm interested in finding practical ways to solve these problems without adding unnecessary complexity. My projects emphasize reliable data, transparent evidence, sensible automation, and keeping people in control. Well, at least I try to. This is mostly exploratory; a really intriguing hobby; and I hope it helps someone. 

## Featured projects

### 1. [Asher Bridge](https://github.com/dwats250/asher-bridge)

*Local-first AI development orchestration | Rust · SQLite · Early-stage prototype*

Asher Bridge grew out of the challenges I've experienced building software with AI coding assistants.

These tools are remarkably capable, but coordinating longer engineering tasks can become difficult. Sessions get interrupted, context is lost, work spans multiple tools, and determining what was actually completed can require substantial manual investigation. No matter how disciplined I try to manage my workspaces I always seem to find new headwinds.

I also wanted a better way to preserve continuity between sessions, track decisions, and confidently resume work without accidentally repeating consequential actions. After experimenting with different solutions on the fly, I created this project to put direct focus on the problems. No half-measures.

Built around Rust and SQLite, the project explores task coordination, bounded work permissions, independently verified evidence, human approval checkpoints, and recovery after interruptions.

The goal isn't to remove human involvement or build an elaborate autonomous system. It's to create a lightweight, understandable foundation that makes AI-assisted engineering more reliable for an individual developer.

The project has reached an engineering-tested prototype stage using synthetic tasks and a simulated agent. Integration with real AI coding agents remains future work.

I'm particularly interested in whether a small, carefully designed system can provide much of the reliability associated with more complicated development infrastructure.

### 2. [Market Brief](https://github.com/dwats250/market-brief)

*Evidence-based market intelligence | Python · Automation · AI-assisted analysis*

This project is a little more mature and I use it daily. Market Brief is a personal market intelligence system designed to provide a clearer picture of financial markets without constantly jumping between charts, news feeds, and applications.

It combines deterministic market data with selective AI-assisted interpretation, producing structured briefings and updates throughout the trading day. I just needed something I could glance at. It sets me up for the day and gives me enough context to be informed so I can start watching the markets manually.

A central design principle is that **observed facts and model interpretations should remain distinguishable**.

Accepted analysis is preserved during routine intraday updates, while market prices, data freshness, source coverage, and supporting evidence remain visible. Missing or unreliable information should be disclosed rather than quietly presented as trustworthy.

I built Market Brief because I enjoy following financial markets but wanted something more organized, transparent, and useful than constantly refreshing my phone. Also, I keep getting tempted to check market movements while I'm at work. Whoops.

## Where I'm headed

### Astra Watch Lab — Bringing information to my wrist

I'm also experimenting with Garmin Connect IQ through a project called Astra Watch Lab.

My longer-term ambition is to bring selected Market Brief information, useful notifications, and eventually development-workspace status directly to my Garmin watch.

Rather than recreating a phone interface on a tiny screen, I'm interested in how a wearable could communicate just enough information to be useful at a glance. My goal is to eliminate the annoying headwinds and complexity that AI assisted coding can encounter. More time building, less time screwing around and trying to find my footing.

I also have the typical dashboards, agentic scheduled flows to monitor markets and search for dislocations, patterns, regime changes, etc etc. They're not as interesting but I want to clean up their workspaces and share them in case anyone else is interested.
