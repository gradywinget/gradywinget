
18, moving to San Francisco in January. I build tools with AI coding agents (Claude Code) and I'm looking to join an early-stage startup full-time, in ops, sales, or wherever I'm most useful.

**What I've built**
- **[property_qa](https://github.com/gradywinget/property_qa)** - a data-quality pipeline. It takes messy CSV/JSON property records from three different sources, standardizes them, quarantines bad rows with a reason for each, and holds the whole batch when a source suddenly changes format. 120 automated tests.
- **Inbox Butler** - an AI-powered email productivity tool I built and ran, then shut down after Google API access restrictions.

**What I learned building property_qa**
- **Never invent data to make a record look clean.** If a timestamp is broken, quarantine it with the raw value. A visibly broken record can be fixed; an invisibly wrong one corrupts everything downstream.
- **The same input can need different fixes.** Excel strips the leading zero from `02134`. Restoring it is right in Massachusetts and wrong in California.
- **A spike in rejected rows usually means the source changed,** not that a lot of individual rows went bad. That needs a human, not a partial load.
- **Working with AI agents is a skill.** The agent writes code fast. My job is to define what "correct" means, push back on shortcuts, and understand every line well enough to defend it.

**Other things I do**
Live fundraising pitches and donor outreach (Level Up LA) · funded-account trading evaluation · 1st place in the investment competition at a London investment-banking summer program

📫 graydenwinget@gmail.com · [LinkedIn](https://www.linkedin.com/in/grady-winget-42a7603a6/)
