---
name: ai-automation
description: >-
  Practical AI and automation for marketing and content teams - how to write
  better ChatGPT prompts, build a custom GPT assistant trained on your own
  style, automate repetitive tasks with Make, and use email/video tools to save
  hours. Use when the user wants to write a better prompt, build a custom GPT or
  AI assistant, automate a workflow, connect tools, set up email automations, or
  repurpose long video into clips. Triggers on: prompt structure, ChatGPT
  prompt, custom GPT, AI assistant, automation, Make, Zapier, automate
  repetitive tasks, email automation, lead automation, reporting automation,
  repurpose video, Opus clip, save time with AI.
---

# AI & Automation for Marketing

How teams actually use AI and automation to save hours and raise efficiency. Step by step,
with copy-paste templates.

**Language:** produce output in the brand's language (default Slovak), in a plain, direct,
no-bullshit voice.

## 1. ChatGPT - two fast hacks

### A) Write a perfect prompt (4 sections)
A good prompt is the basis of a good answer. Just typing what you need is not enough. Use this
4-section structure (popularized by OpenAI's president). The more precision and context you
give, the fewer generic answers you get.

- **#1 Goal:** state exactly what you want. e.g. "Write a script like the example below, but
  this time target the insight in the post below..."
- **#2 Output format:** tell the model how to answer. e.g. "Write a script for a short viral
  TikTok video. At the end, mention that [product] launches on [date]." Tell it
  precisely what you want produced (full script? bullet list? a table?).
- **#3 Warnings:** state what to avoid / what you do NOT want. e.g. "No fluff. Start with a
  genuinely viral hook that gets under the skin of this insight and the people who'll see it."
- **#4 Context:** paste in everything the model needs - the example being referenced, plus a
  long dump of all the relevant context from your head. The more, the better.

Copy-paste skeleton (fill only the quotes):
```
Ciel : ""
Format vystupu : ""
Upozornenia : ""
Kontext : ""
```

### B) Train your own AI coworker (Custom GPT)
If you write the same emails, answer the same questions, or do repetitive tasks daily, build a
custom AI assistant to do them. No programming needed. A custom GPT can be: a post-writing
helper, an editor that checks texts before publishing, a marketer that analyzes campaigns and
suggests improvements, a strategy assistant for a client.

How (practically):
1. **Decide what you need it for.** Want it to write posts like you? Put at least ~10 pages of
   your successful posts into its "knowledge" and it learns your style. Want grammar checking?
   Upload the official spelling-rules reference and it becomes a perfect proofreader.
2. **Upload the knowledge.** Example - a reply-bot that answers messages/emails like you:
   - Create one Google Doc (or Word) as your answer database. Save all your "successful
     conversations" from your messages/emails into it. Export it and upload to the GPT's
     knowledge.
   - You can also add other helpful files: old posts, newsletters, a brand manual. The answer
     database alone is enough; the rest is optional and improves style matching.
3. **Write clear instructions (the "Master prompt").** Tell it exactly what to do, in what role,
   with what constraints and tone.
4. **Test and refine.** Give it a task, check the output, adjust the instructions. You can do
   this live in the right-hand pane of the custom-GPT builder.

## 2. Make - kill repetitive manual tasks
Make connects hundreds of tools and automates processes between them, running in the background
while you do more important work. **First, sketch the sequence of steps on paper** - what each
step does and in what order. It makes configuring Make far easier.

Three ways to build an automation:
1. **From a template** - Make has 2000+ scenario templates. Search by the app you need (which
   you defined on paper), pick a fitting scenario, then configure it.
2. **From scratch, solo** - the boldest option. You choose from every connectable app and every
   action it supports. Think it through carefully (this is why you sketch on paper first), since
   each app has dozens of actions and their real-world meaning isn't always obvious.
3. **From scratch with the AI Beta Assistant** - the helper in the bottom-right builds it for
   you. Works like ChatGPT: the better the prompt (lots of detail), the better the result. It
   accepts Slovak prompts (though it replies in English). It prepares a near-finished
   automation; you just set up the app connections. If something's off, tell it what to swap.

**Setting up connections:** mostly via an API key, a webhook, or logging in with a Google
account. In each module (app) you set the needed parameters (number of outputs, which columns,
which metric, etc.). If a connection fails, follow the error message, ask the built-in AI Beta
Assistant, or check the Make help centre (excellent step-by-step docs). To learn from scratch,
Make Academy is free; if already registered, the Make Resource Hub has more.

**Worked example (e-shop -> sheet):** export orders from an e-commerce store (e.g. WooCommerce)
to Google Sheets. On the store module, choose how to sort the data and how many rows to pull
(set a high number so you don't re-check each time). On the Sheets module, set how to find the
target sheet (via Google Drive, or by pasting the spreadsheet ID from the URL), pick the tab,
set "Table contains headers" to "Yes" (otherwise you can't map the data), then choose which
column gets which piece of info. Done.

### Make automation ideas
1. **Lead gen & CRM:** a form submission (Google Forms, Typeform, Facebook Lead Ads) -> save
   contact to Google Sheets + CRM (HubSpot, Pipedrive, Salesforce) -> auto thank-you email ->
   create a task in Trello for sales to call the lead.
2. **Automated email campaigns:** newsletter signup (MailerLite, ActiveCampaign) -> welcome
   email with bonus -> tips email after 3 days -> if opened, tag as "interested" in CRM ->
   special offer after a week.
3. **Reporting & analysis:** every Monday Make pulls data from Meta Ads and Google Ads -> saves
   to Google Sheets or Looker Studio -> emails you the updated results. No manual reports.
4. **Auto-replies to messages & comments:** a Facebook message comes in -> Make detects keywords
   ("price", "shipping", ...) -> sends an automatic reply or routes to the right team member ->
   if a question repeats often, saves it to an internal FAQ database.

## 3. Other time-saving tools

### Email tool (MailerLite / Mailchimp / any CRM)
Email is still one of the strongest channels to acquire and keep customers. If you still send
newsletters by hand, or have no welcome/goodbye automation, you're leaving huge potential on the
table. Set up automated lead-gen email campaigns so you don't send each email manually.

### Opus.clip (opus.pro) - cut editing costs on video repurposing
Turns long-form video into Instagram reels / TikToks / YouTube Shorts, with captions, and even
scores each clip's virality potential - in the free version (it leaves a watermark, removed on
the paid Pro plan). How:
1. Upload your 20+ minute video (it has handled 2-hour videos and cut them into finished reels
   in minutes).
2. The AI picks the most interesting parts (key ideas, funny moments, strong emotions).
3. It auto-adds dynamic captions and highlights keywords.
4. Tweak what you need (e.g. caption color).
5. Export as TikTok, Reels, or YouTube Shorts.

## How to use this skill
1. For prompting: structure every important prompt as Goal / Output format / Warnings / Context,
   and push as much context as possible.
2. For repetitive work: identify the repeated task, sketch the step sequence on paper, then build
   it in Make (template -> AI assistant -> from scratch, in that order of ease).
3. For style-matching output: build a custom GPT with a knowledge base of the user's own best
   work plus a clear Master prompt.
4. For video repurposing and email: point to Opus.clip and an email automation tool.

Related: writing posts in your voice -> tone-of-voice; hooks for the clips -> headlines; content
workflow -> content-planning.
