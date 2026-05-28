# Interview Prep Library

A prep system for busy engineers who need to remember who they are.

Most interview prep is about what you know: DSA, system design, leetcode. There are a thousand resources for that. This one is about **who you are**: your story, your decisions, your impact. The part that goes stale the fastest when you're heads-down at work.

By the time a recruiter pings, you've forgotten half of it. This repo is the antidote.

## Who this is for

- Mid-career engineers heads-down at work who get pinged out of nowhere
- Anyone who's been saying "I should update my resume" for three weeks running
- People who want a system, not a one-off cram session

## The 4-step workflow

Fork the repo. Fill in the templates with your own content. Maintain them as you work.

| File | Purpose | When to update |
|------|---------|----------------|
| [00-intro.md](templates/00-intro.md) | Your "tell me about yourself" answer | Whenever your role or focus changes |
| [01-career-narrative.md](templates/01-career-narrative.md) | Career arc, themes, differentiators | Every 3-6 months, or after a major project |
| [02-star-stories.md](templates/02-star-stories.md) | Story bank for behavioural questions | Within a week of shipping anything meaningful |
| [03-pre-interview-drill.md](templates/03-pre-interview-drill.md) | 30-min checklist before each interview | Use as-is, run before every interview |

The trick: **capture while it's fresh, drill before you need it.** Memory degrades fast. Five minutes at the time beats two hours of reconstruction six months later.

## The library

### Books

System design, coding, and architecture references. See [index page](https://enkr1.github.io/interview_preparation_materials/) for the full list.

```
books/
├── system-design/    DDIA, ByteByteGo, Grokking, Database Internals
├── coding/           Cracking the Coding Interview
└── architecture/     DDD, Code Simplicity, Beyond Vibe Coding
```

### System design diagrams

17 Excalidraw diagrams covering common system design interview questions (Netflix, WhatsApp, TinyURL, Ticketmaster, Google Maps, etc), rendered as SVG so they preview inline.

**Browse the gallery: [`excalidraw/README.md`](excalidraw/README.md)** (grouped by topic, sources attributed)

To edit a diagram, open the `.excalidraw` file at [excalidraw.com](https://excalidraw.com) or in VS Code with the Excalidraw extension.

### Notes

Reference notes and papers on specific algorithmic concepts.

## How to use this repo

**Browse only:** Visit [the library page](https://enkr1.github.io/interview_preparation_materials/), read what's useful.

**Fork and personalise:** Fork the repo, fill in the templates with your own content. Keep it private if it contains sensitive details, or share with peers.

**Reference during prep:** Clone locally, open the diagrams in Excalidraw, work through the books one chapter at a time.

## Contributing

PRs welcome for:
- New system design diagrams (Excalidraw, with attribution to original source)
- Notes on technical concepts (deep dives, paper summaries)
- Template improvements (clearer prompts, better examples)

Not accepted:
- Direct copies of copyrighted material
- Generic AI-generated content
