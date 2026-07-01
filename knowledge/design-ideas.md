# Design Preferences & App Ideas
*Extracted from Apple Notes — last updated: 2026-07-01*

## Design Preferences

### Interface & Interaction Philosophy

- **Human-first, not machine-first.** Design should adapt to how humans naturally think, not force humans to learn machine conventions. "Rather the user learn coding to communicate with computer, we remove one step — user types in human language and system understands." [Note 5]
- **Friction removal is the core battle.** The bottleneck is energy spent organizing stuff. The app should absorb that so the user can focus purely on thinking and creating. [Note 5]
- **Interfaces at every step of a process.** Unsure if overkill, but believes there should be an interface layer mediating between each step of a workflow — the question is which steps genuinely need one. [Note 5]
- **Parallel reasoning as a collaborative design pattern.** Interested in interfaces that let multiple people reason together simultaneously, pivoting ideas collaboratively rather than the standard linear turn-taking. [Note 12]
- **The "Alive" concept.** An app that brings your notes/thoughts to life when you need them — e.g. walking into a meeting, the app surfaces relevant context automatically. Presence-aware, context-aware. [Note 5]

### Visual & Information Design

- **Mindmaps as the primary output format.** Believes visual mindmaps are the best way for humans to understand information at a glance. The goal is scannability — user should grasp the map with ease. [Note 10]
- **Scannable over comprehensive.** Prefers smaller, focused mindmaps split by category rather than one large overwhelming diagram. Values human readability over exhaustiveness. [Memory]
- **Category-based content grouping.** When entering a meeting context, surface only relevant topics (e.g. school work → school mindmap; psychology discussion → psychology notes + personal experience). Context-sensitive filtering. [Note 10]
- **Writing style: linear narrative with analogies.** When explaining concepts, use a linear narrative flow with real-world analogies. No yapping. Every word must tell. Active voice. [Note 141]

### System & Workflow Design

- **Dota 2 five-man team as mental model for agent systems.** Positions 1-5 with distinct roles: Pos 5 covers Pos 1's shortcomings, Pos 1 is the executor. Three-phase game stages (drafting → laning → late game) as design pattern for multi-agent workflows. [Note 5, Note 140]
- **Gemini → Codex pipeline architecture.** Gemini (large context window) does the heavy synthesis from raw diary entries. Codex (smaller window) takes Gemini's output and creates visual mindmaps suited for human understanding. Each tool does what it's best at. [Note 10]
- **Subagent-per-topic pattern.** Rather than one agent processing everything, spawn one subagent per knowledge topic. Each subagent compares new diary entries against its domain, finds connections, then appends. Like topic specialists reviewing incoming material. [Note 10]
- **Separate human and machine layers in personal branding.** LinkedIn profile split into: (1) human part — vlog, personal experience, YouTube channel; (2) machine part — GitHub built by AI, showcasing technical output. Two distinct audiences, two distinct presentations. [Note 12]
- **Project memory file → skill.** Concept of taking project-level memory/context and converting it into reusable skills that can be applied across projects. [Note 7]
- **S/L/3/10/P/T shorthand for prompt control.** Single-letter prefixes to control response format: S (one sentence), L (long/detailed with headers), 3 (3 options), 10 (10 options), P (paraphrase), T (table format). Efficient prompt engineering UX. [Note 141]

### Accessibility & Inclusivity

- **Dynamic UI/UX for colorblind and elderly users.** Interface that adapts to the user's visual needs rather than forcing one-size-fits-all design. [Note 5]
- **Design for the lowest common denominator of tech literacy.** Apps that guide users through unfriendly interfaces — especially senior citizens. [Note 5]

---

## App Ideas

### healmyUX
*An app that guides senior citizens through unfriendly user interfaces.*
Tell an AI extension what you want to do, and it navigates the interface for you or guides you step-by-step. Potential add-on: auto-filling forms with stored user information.
[Note 5]

### CRM Auto-Logging System
*Auto-logging CRM cases from meeting speech.*
Transcribes meeting conversations directly into CRM case fields. Configurable AI to provide insights in your preferred style. Could extend to Teams meeting integration with configurable input field mapping.
[Note 5]

### Inventory Management for Gifts
*Track gifts against friends' birthdays.*
A basket/friends system: track what gifts you've bought or plan to buy, matched to birthdays and occasions. Relationship-aware inventory.
[Note 5]

### Finding the Moment When Inspiration Strikes
*Path-finding through campus without filming videos.*
When finding specific routes through campus, instead of needing to record walkthrough videos, the system captures and shares navigation moments contextually.
[Note 5]

### What to Cook With What's In Your Fridge
*Ingredient-based recipe discovery connected to Instagram/Facebook.*
Input what's in your fridge, get recipe suggestions. Con: high user friction to manually type in all ingredients.
[Note 5]

### NFC Networking
*Connect with someone by tapping your phone.*
Use NFC tags to share contact details. Configurable for different contexts: professional mode (LinkedIn only) vs social mode (private Instagram). Receiver gets a notification without needing the app installed — gentle nudge to download.
[Note 5]

### Book Grab/Gojek via Telegram & WhatsApp
*Ride-hailing through messaging apps.*
Book rides without leaving your chat app. Potential extensions: GrabFood ordering, calendar integration, other shortcut integrations.
[Note 5]

### Restaurant Finder from Social Media
*Find restaurants from untagged Instagram posts.*
Friend posts a dish with no location tag. You don't know the dish name. The app identifies it and finds nearby places serving it.
[Note 5]

### Family Law & Estate Management Platform
*Smart asset-probate orchestration for lawyers and grieving families.*
Families upload chaotic bundles of legal/financial documents. IDP (Intelligent Document Processing) extracts assets, debts, relationships and maps them into official court filing fields. Includes emotional check-in tracker for families and auto-transcription of client-lawyer calls into case notes.
[Note 5]

### Migrant Worker Onboarding & Welfare Platform
*Multilingual worker lifecycle management.*
Voice-driven interface in workers' native languages. Complete onboarding checklists, upload identity papers (auto-populate compliance forms), report adjustment/mental health. Employer dashboard tracks paperwork bottlenecks. Family/NGO portal for employment status verification, safety logs, remittance records.
[Note 5]

### CoachLink Baseball
*Digital marketplace connecting SEA baseball players with coaches in Japan and Taiwan.*
Rule-based matching protocol surfaces relevant regional coaches with explicit explanations of why the match makes sense. Players compare coaching philosophies and video-analysis styles side-by-side. Upload a swing/pitching video to instantly link with a mentor. Vision: hybrid ecosystem where digital trust matures into real-world clinics and camps. [Note 15, Note 16]

### Grey App / Second Brain
*Free-form journal → structured action items and meeting context.*
Core insight: the most natural way for humans to write thoughts is free-form, no structure, no guided questions — just write when the spark hits. The AI absorbs the organization burden. Key features:
- Extract action items from fragmented diary entries
- Surface relevant context when entering a meeting (context-aware mindmaps)
- Categories that emerge naturally from content, not pre-defined buckets
- "Alive" mode: your notes come to life when you need them
[Note 5, Note 9, Note 10]

### Community Podcast Platform
*Building belonging through audio conversations.*
A podcast channel that's more than content — it's a platform that sparks dialogue, builds community, and gives people the feeling of belonging. Targets adults 25-30+ who've lost natural socialization opportunities after school. Call to action: get people to reach out and interact more. [Note 85]

### Music Platform with Advanced API
*Profile page with personalized login. Extra exercise features. Advanced API to connect to external databases for song playback.*
[Note 46]

### 90-Day Challenge Tracker
*Structured challenge system with phases.*
90-day challenges split into parts. Phase 2: 80% writing focus. Career switch into tech companies. Daily vlogs as part of routine. Progress tracking with error logging and course-correction. [Note 142]

### Quest System
*Personal task/quest management inspired by game mechanics.*
Organize life tasks as quests with categories: Active health checkups, Daily admin time, Daily vlogs, Skills exploration, 90-day challenges. Talks to a "stakeholder" persona for accountability. Tracks errors and fix plans. [Note 142]

---

## Raw Source Notes

- **Note 5**: Primary source — Idea Bank (healmyUX, CRM, inventory, dynamic UI, NFC, Grab booking, restaurant finder, law platform, migrant worker platform), Grey App design philosophy, interface layer thinking, Dota 2 agent formations
- **Note 7**: Project memory → skill concept
- **Note 9**: Second Brain design philosophy, human vs machine layers, Apple-like friction removal, natural input method
- **Note 10**: Gemini → Codex pipeline, subagent architecture, mindmap generation, meeting context surfacing
- **Note 12**: Personal branding split (human/machine LinkedIn), parallel reasoning, workflow iteration philosophy
- **Note 15, 16**: CoachLink Baseball pitch and design
- **Note 46**: Profile page, music API, exercise features
- **Note 85**: Community podcast platform concept
- **Note 140**: Dota 2 conceptual framework (positions, formations, gameplay phases)
- **Note 141**: Writing/prompt design philosophy (S/L/3/10/P/T shorthand, linear narrative, no yapping)
- **Note 142**: Quest system, 90-day challenge tracker, daily vlog routine
