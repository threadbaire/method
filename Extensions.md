# Threadbaire — Extensions

When Core + Addendum isn't enough, add one of these.

---

## For development projects

If you're writing code, add two more files:

### Technical Core

Stable technical decisions. Stack choices, architecture, dev environment rules.

**Sections:**
- Stack (what you're using, pinned versions, why you chose it)
- Architecture (how components fit together)
- Project structure (folder layout)
- Dev rules (things to check before writing code, testing requirements)
- Open technical questions

**Update when:** A technical decision becomes permanent.

### Dev Log

Session-by-session coding progress.

**Sections:**
- Current state (what exists, what works, what's broken)
- Targets (this week's goals, stretch goals, not-this-week)
- Dead ends table (what you tried that didn't work — so you don't try it again)
- Session entries (date, what you built, what worked, what's next)

**Entry format (simpler than Addendum):**
```
### [Date]

**Type:** Setup / Feature / Fix / Dead End
**Status:** Done / Partial / Failed

**What happened**
[2-3 sentences]

**Details**
- [Specifics, commands, code notes]

**Next**
- [What follows]
```

**Update when:** After each coding session.

---

## For content projects

If you're making videos, writing, or publishing, add metrics and review checkpoints to your Addendum entries.

### Extended entry format

```
### 1. [Title]

**Type:** [Content Release / SEO Pass / Experiment]
**Status:** [Done]

**What happened**
[Description]

**Details**
- Asset: [Title, ID, link]
- Changes: [What you published or modified]

**Metrics at publish**
- [Relevant numbers: views, CTR, engagement, etc.]

**Review plan**
- 7 days ([date]): Check [what]
- 30 days ([date]): Check [what]

**What's next**
- [Follow-up]

**Receipt:** [Who · Why · Source · Date · Model]
```

**Tip:** Create a simple stats file or spreadsheet alongside your Addendum. Reference it in entries but don't clutter the log with raw data.

---

## For outreach and pipeline work

If you're contacting people, tracking leads, or managing a sales-like process, add a Tracker file.

### Tracker

One entry per target/contact. Update status as things change.

**Entry format:**
```
### [Company/Person Name]

**Status:** [Not contacted / Awaiting response / In conversation / Dead / Converted]
**Last touch:** [Date]

**Context**
- What they do: [One line]
- Why contact them: [Your hook or reason]
- Funding/stage: [If relevant]

**History**
- [Date]: [What you did, what happened]
- [Date]: [Next touch, response, outcome]

**Notes**
[Anything worth remembering — red flags, insights, follow-up timing]
```

Your Addendum becomes the activity log (what you did today). The Tracker becomes your database (status of each target).

---

## General pattern

| Project type | Files |
|--------------|-------|
| Most projects | Core + Addendum |
| Development | Core + Addendum + Technical Core + Dev Log |
| Content | Core + Addendum (with metrics sections) |
| Outreach/Sales | Core + Addendum + Tracker |

Start simple. Add files only when the existing ones get cluttered or you're mixing very different types of work.

---

## Naming convention

Name files for your project:

```
MyProject_Core.md
MyProject_Addendum.md
MyProject_Technical_Core.md
MyProject_Dev_Log.md
MyProject_Tracker.md
```

Or use folders:

```
my-project/
  Core.md
  Addendum.md
  Technical_Core.md
  Dev_Log.md
```

Whatever helps you find things.
