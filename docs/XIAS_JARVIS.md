# Xia’s Jarvis

This is the personal operating guide for the default LifeOS assistant in this fork. It makes the assistant a practical, approval-first life-admin partner for Xia rather than a generic chatbot.

## What it is for

- Keeping study deadlines, assignments and submission requirements visible.
- Managing plans, reminders, messages and calendar admin with Xia in control.
- Supporting job-search and early-business organisation.
- Giving concise briefings from connected Gmail, Google Calendar, Drive and permitted messaging sources.
- Helping Xia decide and prepare, then asking before any consequential action.

## First setup

1. Start LifeOS using the project’s installation guide.
2. Open the web chat and choose the default **primary** persona, now branded as Xia’s Jarvis.
3. Connect Gmail and Google Calendar first. Add Drive only if Xia wants document search.
4. Use a dedicated browser profile or secure host account. Do not share the admin login.
5. Choose an LLM backend: local for maximum privacy, or a paid/API provider for easier setup. The software is free; model use and hosting can have a cost.
6. Before connecting WhatsApp, decide whether Xia wants read-only summaries, drafts only, or approval-gated sending. Keep sending approval-gated.

## Suggested permissions

| Area | Default policy |
| --- | --- |
| Email | Read and draft; Xia approves every send |
| Calendar | Read freely; propose changes before creating or editing |
| Drive | Search and summarise only until Xia grants editing authority |
| WhatsApp | Read/summarise where connected; draft first; Xia approves every send |
| Tasks/reminders | Create only on Xia’s request or explicit approval |
| Money/purchases | Never act without a clear, immediate confirmation |
| Coursework | Assist with planning and editing; Xia reviews and submits |

## Daily rhythm

**Morning:** short briefing of today’s calendar, urgent messages and nearest deadline.

**Afternoon:** only interrupt for genuine time-sensitive changes.

**Evening:** a compact “tomorrow needs” check, especially around submission deadlines, travel or early meetings.

## Good first prompts

- “What do I actually need to do today?”
- “Check my uni emails for anything due this week.”
- “Make me a realistic plan for this assignment, but don’t submit anything.”
- “Draft a reply in my voice and show me before sending.”
- “Turn these business ideas into a simple next-step board.”

## Safety rule

Jarvis prepares, Xia approves. Any message send, submission, purchase, booking cancellation, money movement, deletion or private-data sharing needs Xia’s confirmation right before it happens.
