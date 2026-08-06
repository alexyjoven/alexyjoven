> **→ start here: [alexy.modjo.me](https://alexy.modjo.me)** · this readme is the extension.

### hi, i'm alexy.

**head of growth · marketing engineer.**
b2b + prosumer · formerly founder @ [modjo](https://www.modjo.me/) · nyc + brussels.
fr/en/es/nl · belgian + spanish · b. brussels 1995 · Solvay Business School · Bachelor's in Economics · Master's in Finance.

spent the last decade building growth systems for b2b and prosumer companies. from zero to millions in revenue and fundraise. my own companies. my clients'.

---

### prior work

| company           | year      | what happened                                                                             |
| :---------------- | :-------- | :---------------------------------------------------------------------------------------- |
| Reveel Pay(ID)    | 2025      | $26M deposits, $200M transaction volume, in 60 days                                       |
| xy.ai             | 2026      | ai-native healthcare RCM · ~$1.6M ARR · built in 4 weeks · ~1,500 accounts mapped with the full buying team · 12,500+ in the CRM · 1,559 decision-makers at 95% · 3,050 emails/week at <2% bounce · ~4,000 intent signals · a different message per committee role, not a merge field · retargeting audiences off the same engagement data |
| Elixir Games      | 2024      | $14M revenue, 250% over target, marketing spend cut 65%                                   |
| Jeux d'Hiver      | 2022      | 60,000+ paying customers in 6 months, brussels' most prestigious venue                    |
| Green-In          | 2019–2021 | 4,000-person festival, $1M+ ARR, built from a garden at 22                                |
| Modjo             | 2023–2026 | 70+ clients across entertainment, ai, fintech, blockchain · teams of 20+ · $2M+ bootstrapped |
| bl0x              | 2022–2023 | growth marketing, paris. 50+ clients: binance, ledger, animoca, pmu, lacoste. growth (influence, content, pr, collabs) + community & social media. |

---

### the difference

**growth systems built as code.** one queryable substrate underneath. every event is a fact. every axiom runs as a rule. the engines compound because they talk to each other over the ontology. every reply lands as a fact, so next month starts with more than this month did.

---

### the technical turn · since 2024

the last two years i went deeper on the technical and engineering side.

i run my own company as queryable code. an ontology of every customer, machine-enforced rules, agents that source, score and route, governance that blocks bad data at commit time. same discipline applied to the growth stack itself: attribution, martech ops, data model, funnel eng.

```
registered spec nodes   ~530
systems                   23
spec files              ~670
python & shell modules    91
git commits             ~990
```

*regenerable count · re-run 2026-08-06 · v4 pre-commit + ci · one home per matter · mcp query layer.*

**built one for [xy.ai](https://xy.ai)**, AI-native healthcare RCM company at ~$1.6M ARR. in 4 weeks: ~1,500 target companies mapped with the full buying team at each (12,500+ people in the CRM, all xy.ai-relevant), 1,559 decision-makers at 95% hit rate, 8 committee-role campaigns (CFO / CEO / CIO / COO / Champion / DRC / Office Manager / Admin Manager) staged, 8 dedicated sending domains, 16 warmed inboxes, 3,050 emails/week at <2% bounce rate. **a different message per committee role, not a different merge field**, routed off their role and org size, what they open and click, which competitors they engage, and the stack they run (detected via amplemarket). retargeting audiences are built per committee role off that same engagement data. AI reply classifier (n8n + claude) auto-tags every reply hot/warm/cold/ooo, logs to hubspot, pings slack. daily safety net cross-checks hubspot + twenty + amplemarket, blocks matches before any smartlead send fires. ~4,000 buying-intent signals via 5 listening searches. hipaa + soc 2 posture, structurally phi-free.

---

### how the engines actually talk

three engines. growth, content, design. one queryable ontology in the middle. AI runs inside each of the three, not as a fourth box.

the **growth engine** knows where every lead sits, what pain they hold, and how they've engaged per channel. it reads the ontology before every routing decision. it writes back to the ontology on every event: opened, clicked, replied, muted, unsubscribed.

the **content engine** takes a routing decision from growth and produces the narrative variants. one lead, one account: cold email to the CFO (roi-anchored, references the specific signal she showed), LinkedIn ad for the ops staff at her org (compliance-forward), InMail to her VP of RCM (clinical framing, different value prop), retargeting sequence for anyone at her org who touches the site next. same account, different narratives per person, based on what the ontology says will land.

the **design engine** ships the four assets in their proper format: email HTML, LinkedIn image ad, InMail body, banner set for the retargeting exchange. four assets, four formats, same velocity.

every reply, click, and open lands back in the ontology as a new fact. next lead the funnel sees, the whole system already knows more.

---

### one lead, one flow · a real example

a CFO at a 200-provider healthcare org lands in the funnel. reacted to a legacy RCM incumbent's LinkedIn post 3 weeks ago (competitor engagement flag from the listening layer). viewed the prior-auth automation page on our site. has been sitting in HubSpot as a stalled deal for 4 months.

the growth engine already knows every one of those facts because every event landed as a fact when it happened. it knows this CFO is on the Champion committee campaign, and that her org has a live buying-signal flag.

and it knows this from observed engagement in the ontology: this CFO has zero ad clicks across 4 months of retargeting. her VP of RCM has clicked twice. ops staff at her org open at a higher rate than the C-suite generally does. so the growth engine doesn't guess. it routes her personally to an InMail plus a cold email tuned to the specific signal she showed, and it targets the LinkedIn ad at her VP and the ops staff. same account, different levers per person, based on what actually got a response. not on a rule about "CFOs."

the content engine writes the four narratives in parallel. the design engine ships the four assets in parallel. every reply the AI reply classifier sees goes back into the ontology hot/warm/cold/ooo. next lead the funnel sees, the whole system already knows more.

---

### what that fraction doesn't count

comparable volume to a 3-person SDR team over the same window, for a fraction of the retainer plus comp cost.

that fraction doesn't count the engine itself. the ontology, the reply-classifier, the suppression net, the signal listener. those are one-time builds that carry across every future sub-funnel. each new sub-funnel is easier to implement than the last, because the substrate is already there and the ontology is already grounded in the client's reality.

next month's campaigns start with more data than this month's: which channels got responses per persona, which openers converted by ICP, which orgs didn't respond and why. the system doesn't get smarter on its own. it collects observations, surfaces them, and lets a human decide what to change. the gain is that the operator isn't rebuilding the memory from scratch every quarter.

still needs a human in the loop for the judgment calls the machine shouldn't be making alone. the engine does the work between those calls.

---

---

### outside signal · march 2026

**30 Global Founders to Watch.** by aspire, in collaboration with lightspeed venture partners and deel. the cohort recognises founders who crossed borders to build in the us and are now redefining what's possible.

**mentor** at techstars · berkeley skydeck · nucleate · outlier ventures · onepiece labs.

---

### recent build · 2026

**modjo content engine.** a brand-locked, multi-tenant, multi-format video factory. one-line prompt → ready-to-post clip in ~2 hours.

**stack (8):** remotion (react video framework, every frame is JSX) · elevenlabs (voice, music, SFX) · v0.app (react+tailwind UIs) · figma + MCP (live brand pull) · screen studio (capture) · whisper (captions) · R3F (3D inside remotion). orchestrated through claude code.

**cost: ~$82/mo full stack**, a few dollars per output. self-serve for the whole team via one shared claude code seat + shared 1password vault of API keys.

**built with georgi selivjorstov**, production lead. i trained him to be ai-native. two hours per video, no designer-hours or animator-hours in the loop.

**shape**: engine replaces the shop. built once (multi-tenant, brand-locked via one tokens.ts swap per client), then every future video runs at marginal cost. same operating pattern that runs the b2b engine, applied to creative production.

→ one output plays on [alexy.modjo.me](https://alexy.modjo.me) under this section (xy.ai brand-locked).

---

### writing

**[CMOs Can't Execute](https://www.linkedin.com/feed/update/urn:li:activity:7409608835339939841/)** · jan 2026 · **18,701 followers** · 1,032 reactions on this post · 180 comments. the thesis on why head-of-growth seats are opening in the shape they are, and why early-stage companies will skip cmo hires in the 24-month horizon.

---

### now

open to head-of-growth / marketing-engineer conversations at b2b + prosumer companies.

---

### reach

- linkedin · [alexy-joven-405075107](https://www.linkedin.com/in/alexy-joven-405075107/)
- x (technical dives) · [@alexyjoven](https://x.com/alexyjoven)
- email · alexy@modjo.me
- phone · (510) 221-6181
- web · [modjo.me](https://www.modjo.me/)

---

*start here → [alexy.modjo.me](https://alexy.modjo.me) · this readme is the extension.*
