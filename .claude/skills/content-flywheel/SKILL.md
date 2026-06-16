---
name: content-flywheel
description: >-
  How to set up an automated content repurposing pipeline where one piece of content
  (video, lecture, article, meeting) auto-generates blog posts, LinkedIn posts, social
  media content, and weekly newsletters using AI agents. Use when the user wants to
  repurpose content across formats, automate their newsletter, run a hands-free content
  calendar, or set up a content pipeline that runs without them. Triggers on: repurpose
  content, content automation, video to blog post, one content many formats, automated
  newsletter, content pipeline, hands-free content, content flywheel, auto-post social
  media, save time on content, content on autopilot.
---

# Content Flywheel - One Input, All Formats, Automatically

One piece of content should become ten. Not manually - automatically. A video you
record becomes a blog post, a LinkedIn post, an Instagram caption, and a newsletter
section, all in your voice, without you doing the work. Most people create one thing
and publish it once. The flywheel creates one thing and publishes it everywhere.

**Language:** default output in Slovak, plain and direct.

## Key capability: AI can watch videos

Gemini (Google AI Studio API or Gemini Advanced) can watch a full video and describe
everything: what is said, what is on screen, moment by moment. Give it an MP4 upload
or a YouTube link. This is the engine behind every video-based workflow below.

Prompt to extract everything from a video:
```
Pozri si toto video. Daj mi: uplny prepis toho, co sa hovori; popis toho, co je
vidiet na obrazovke v kazdom momente; klucove myslenky a citaty; a zoznam
konkretnych, akcionovatelnych bodov, ktore by mohol pouzit citatel.
```

Output: a full structured document of the video's content you can feed into every
subsequent step.

---

## Workflow A: One video → all formats

Use when you record a talk, lecture, webinar, podcast episode, or educational video.

**Step 1 - Extract:**
Give Gemini the video. Ask for: full transcript, on-screen descriptions, key insights,
notable quotes, actionable takeaways.

**Step 2 - Blog post:**
Feed the extraction to Claude with your foundation layer linked. Prompt:
```
Na zaklade tohto prepisu videa napis blogovy clanek v mojom Creator Style.
Obsah ma byt hodnotny, nie prepis. Vyber najsilnejsie myslenky a postav ich
do logickeho celku. Potom mi daj aj prompt na hero obrazok v nasom brandovom style.
```

**Step 3 - LinkedIn post:**
```
Z toho isteho materialu napis LinkedIn prispevok. Zacni silnym jednovetovym hookom,
potom hodnota, potom jedna otazka alebo CTA. Max 8 odstavcov, kratke vety.
```

**Step 4 - Short clip + caption:**
Identify the 30-60 second segment with the sharpest insight (ask Gemini: "Which 30-60
second moment from this video has the highest standalone value?"). Write a caption
for it. Schedule both together.

**Step 5 - Newsletter section:**
```
Zhrn klucovu myslenku tohto videa do 2-3 viet pre tyzdenny newsletter. Vysvetli,
preco je to dolezite pre [tvoja cielova skupina z ICP].
```

**Step 6 - Schedule:**
Drop all outputs into your social media scheduling tool. Stagger them: blog on Monday,
LinkedIn on Tuesday, clip + caption on Thursday, newsletter section the following Sunday.

Result: one recording → 5-7 pieces of content, all in your voice, staggered across 1-2 weeks.

---

## Workflow B: Automated weekly newsletter

A weekly newsletter that runs itself. Set it up once, it runs every week.

**What the agent does:**
1. Wakes up on a set day (Friday evening or Sunday morning works well).
2. Checks a source list you define: RSS feeds, specific websites, LinkedIn creators
   you follow, YouTube channels, newsletters you subscribe to.
3. Picks the most relevant items for your audience (you define the criteria once in
   the agent instructions: topic areas, content types, what counts as relevant).
4. Writes an intro paragraph in your tone of voice (from your foundation layer).
5. Generates a contextual image matching the theme of that week's edition.
6. Assembles the full newsletter: intro + 5-7 items with links and one-line descriptions.
7. Sends via your email tool (MailerLite, Mailchimp, Brevo, or similar).

**What you do:**
Review the draft before it goes out (or skip review and let it run if you trust the
setup). Either way, it goes out every week. Consistency is the point.

**To set up:**
- List your sources (5-10 URLs, RSS feeds, or account handles).
- Write your criteria ("must be relevant to Slovak marketers and founders, no politics,
  no generic motivational content").
- Connect Claude to your email tool via API or Make.
- Set a weekly trigger (Make workflow or Claude scheduled task).

---

## Workflow C: Your brand generates its own weekly content

Your social media accounts never go silent even when you do nothing.

**What the agent does weekly:**
1. Checks your foundation layer for your topic areas and voice.
2. Scans your approved sources for relevant material from the past 7 days.
3. Drafts LinkedIn posts, Instagram captions, reel scripts, TikTok concepts.
4. Each draft includes: hook, body, CTA, and a note on which technique was used
   (so you understand the logic, not just the output).
5. All land in your scheduling tool as drafts awaiting your approval.

**What you do:**
Review once a week. Approve, edit, or delete individual posts. Takes 10-15 minutes.
The rest runs without you.

---

## Workflow D: Meeting / call → action items + summary

Every important meeting or call captured automatically.

**Process:**
1. Record the meeting (Fireflies, Otter, or simply the voice recorder on your phone).
2. Drop the audio or transcript into Claude.
3. Ask: "Vytvor zapis zo stretnutia: co sme sa dohodli, kto ma co urobit do kedy,
   otvorene otazky, a veci, ktore este treba doriešit."
4. For a client meeting: "What information from this call should I add to my
   foundation layer about this client?"

For in-person meetings where you can't use an app: start your phone's voice recorder
before the meeting. Tell the other person you're recording for notes. Transcribe
afterward, drop into Claude.

---

## What you need to run this

| Requirement | Why |
|-------------|-----|
| **Foundation layer** | Without it all output is generic. Non-negotiable prerequisite. |
| **Gemini access** | Video analysis for Workflows A and C. Google AI Studio or Gemini Advanced. |
| **Email tool with API** | For Workflow B newsletter automation. |
| **Social scheduling tool** | Centralizes all drafted content for review and posting. |
| **Make or similar** | Connects the pieces and runs triggers on a schedule. |

---

## How to use this skill

1. Start with Workflow A - highest return, least setup. One video, done today.
2. Add Workflow B once you have a list worth nurturing (100+ subscribers).
3. Add Workflow C when you want consistent presence without weekly effort.
4. Workflow D can start immediately - no setup, just a recorder and Claude.
5. Foundation layer must exist before any workflow produces good output.

Related: building the foundation layer -> foundation-layer; AI prompting and tooling
-> ai-automation; content calendar and planning -> content-planning;
what to post and why -> content-principles.
