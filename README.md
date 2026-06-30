# richworks-skills

[🇬🇧 **English**](README.md) | [🇸🇰 Slovenčina](README.sk.md)

A library of 18 marketing skills built from real practice at **RichWorks** - a results-driven
marketing agency focused on social media, content strategy, and AI-powered growth.

These are not generic tips scraped from the internet. They are the actual frameworks, workflows,
and playbooks used with clients, packaged as plain-Markdown skill files that work with **any AI
assistant** - Claude, ChatGPT, Gemini, Copilot, Cursor, or any tool that lets you add context or
custom instructions.

Each file is self-contained. Load the one that matches your task and the AI writes with the right
framework instead of generic advice.

---

## Who built this

**Adam Hodoši** - Social Media Lead at RichWorks, AI and marketing specialist. Building brand
presence, content systems, and social media strategies for clients across various industries.
These skills reflect what actually moves the needle: follower growth, content systems that scale,
video that performs, copy that converts.

---

## What's inside

18 niche skills covering the full social media and marketing workflow.

| Skill | What it covers |
|-------|---------------|
| `profile-optimization` | Instagram profile setup - bio formula, highlights, handle, name field |
| `profile-growth` | Diagnosing and fixing follower growth - traffic vs. conversion funnel |
| `tone-of-voice` | Brand voice exercises - values, personality, brand codes |
| `reels-video` | Short-form video strategy - hooks, structure, VTR, audio |
| `sales-posts` | Selling on social without killing reach - copy techniques, formats |
| `landing-page-copy` | Web copy that converts - USP, objections, proof, simplicity |
| `headlines` | 100 fill-in-the-blank headline templates |
| `seasonal-campaigns` | Black Friday / Q4 strategy - warming contacts, remarketing, FOMO |
| `content-planning` | Full content workflow - idea bank, calendar, captions, posting routine |
| `content-principles` | Content strategy fundamentals - what to post and why |
| `ai-automation` | AI prompting, custom GPTs, Make automations, email flows |
| `linkedin-templates` | 5 proven LinkedIn post structures for authority building |
| `viral-script-formula` | The psychology behind viral video - 3 concept frameworks |
| `hashtag-strategy` | 2026 hashtag rules, the 5-tag limit, banned hashtag list |
| `reel-diagnosis` | 7-step AI post-mortem for underperforming videos |
| `foundation-layer` | Teaching AI your brand voice, audience, and positioning |
| `content-flywheel` | One recording - all formats, automated |
| `creative-techniques` | Advertising creative frameworks and the 4C strategy model |

Every skill lives at `skills/<name>/SKILL.md`. The file starts with a short metadata block
(name, description, trigger words) followed by the framework in plain Markdown. The metadata helps
tools that auto-load skills; everything below it is readable by any human or AI.

---

## How to use these (pick your tool)

The content is the same everywhere. Only the way you load it differs.

### Claude Code (auto-loading plugin)

In Claude Code, skills activate automatically based on the conversation - you never pick one.

```bash
# 1. Add the marketplace
claude plugin marketplace add hodoshia/richworks-skills

# 2. Install the skills you want (or all of them)
claude plugin install headlines@richworks-skills
claude plugin install reels-video@richworks-skills
claude plugin install content-planning@richworks-skills
# ...one line per skill, see the table above for names
```

Start a conversation about hashtags and `hashtag-strategy` loads. Ask about a flopped reel and
`reel-diagnosis` kicks in. No commands to remember.

### ChatGPT (Custom GPT or Project)

1. **Custom GPT:** create a new GPT, then under **Knowledge** upload the `SKILL.md` files you want
   it to know. In the GPT's instructions add: "When a task matches one of the uploaded skills, follow
   that skill's framework."
2. **Projects:** create a Project, open **Instructions**, and paste the contents of a single skill
   (or a few related ones). Everything in that project then uses the framework.
3. **One-off:** paste a skill straight into the chat before your request.

### Google Gemini (Gem)

1. Open **Gems** and create a new Gem.
2. Paste the skill content into the Gem's instructions.
3. Optionally attach related skill files via Google Drive so the Gem can reference them.

Gemini is also handy for the video-analysis steps inside `content-flywheel` and `reel-diagnosis`.

### Cursor, Copilot, and other coding/agent tools

Drop the `SKILL.md` content into the tool's rules / custom-instructions file
(for example a `.cursorrules` file, a Copilot instructions file, or a system prompt). The tool then
applies the framework whenever it is relevant.

### Any AI chat (copy-paste)

No setup at all: open the skill in this repo, copy it, paste it into your AI of choice, then ask
your question. Works with any model.

### Obsidian, Notion, or a plain knowledge base

Clone or download the repo and open the `skills/` folder as a vault or import it into your notes.
Each skill is a normal Markdown file, so it doubles as a reference library you can read directly.

```bash
git clone https://github.com/hodoshia/richworks-skills.git
```

---

## How it works

Each skill carries:
- The core framework or methodology
- Verbatim prompts and templates (in Slovak where the original is Slovak)
- Cross-references to related skills
- Concrete examples from real campaigns

The skills are deliberately split one-niche-per-file so you only load what's relevant - no bloat,
no contradictory advice from unrelated playbooks.

---

## Language note

Most skills default to **Slovak output** - they were built for a Slovak-speaking audience. The
frameworks and methodologies are universal; switch to any language by saying so in your prompt.

---

## Updates

Skills are added and updated as the practice evolves. Watch the repo or re-pull to get the latest
version. Contributions and adaptations for other tools are welcome.
