---
name: ten-step-working-knowledge
version: 1.0.0
description: Turn an unfamiliar topic into working knowledge in four movements — map it through five disagreeing perspectives, build a five-rung ladder, then prove understanding by retrieval and teach-back. Use when someone must learn a field, skill, or decision fast and be able to speak and act competently, not merely summarize.
license: MIT
compatibility: Requires live web search and file writes. No scripts, no dependencies, no API keys. Runs in any agent that reads SKILL.md.
author: epslkslsksndnsjs-lab
metadata:
  author: epslkslsksndnsjs-lab
  tags: learning research study-methods agent-skill
---

# Ten Steps to Working Knowledge

A protocol for learning one topic to the point of being able to act on it. It turns the agent from an answer machine into the three things a learner actually needs: a panel of experts who disagree, an examiner who keeps score, and a twelve-year-old who catches every skipped link.

Each step takes one instruction. Each step produces one file. Ten steps leave a folder the learner can reopen, not a chat log to scroll through.

Throughout this document, "you" is the agent and "the learner" is the human in the chair.

## When to Use

- The learner is entering an unfamiliar industry, function, or market, and needs to hold a real conversation in it.
- The learner has to make a decision in a domain they do not own.
- The learner is acquiring a skill and wants a route, not a reading list.
- The learner already knows part of the topic and suspects holes in that knowledge.

**Do not use** for a single fact, a definition, or a task the agent can simply complete. This protocol costs hours. Spend them on things worth hours.

## Starting a Run

Ask three questions, no more:

1. What is the topic, and what is your role in it?
2. How many hours do you actually have?
3. Full run, or map only?

Then begin step 1. Do not ask permission at every step; ask at the two movement boundaries (after step 4, after step 7).

If ten questions cannot test the topic, it is too broad. Narrow it to one role facing one decision before step 1. "Economics" is not a topic; "pricing a hardware product for a first-time founder" is.

## Reply Format

These six rules govern every message the agent sends the learner.

1. **Keep every sentence under fifty words.** In Chinese, keep it under fifty characters. Fifty is a ceiling, not a target; aim for fifteen to twenty-five words.
2. **Put one idea in one sentence.** Split any sentence that carries two claims, two causes, or two instructions.
3. **Use one word for one thing, from first mention to last.** Fix the term when you introduce it. Never rotate synonyms for variety.
4. **Write in the active voice, and name the actor.** Write "The examiner scores the answer", not "The answer is scored". If nobody knows the actor, say so.
5. **Say "I do not know" where you do not know.** Name the uncertainty where it sits. Never let a guess wear the clothes of a finding.
6. **Never drop words to meet the length limit.** Cut a whole sentence instead. Never delete a subject, a verb, or an article to save space.

## Philosophy

**1. The consensus is not the field.** Ask "tell me about X" and the answer is the median view: the most common framing, the surface layer, the answer that offends no one. A field's actual shape lives in its disagreements, its incentives, and its silences. A method that samples only the middle produces people who sound informed and are not.

**2. Understanding is a retrieval property, not an exposure property.** Fluency while reading is the most reliable evidence that nothing has been learned yet. Knowledge is confirmed only when it comes back out under pressure, in the learner's own words, with the source closed.

**3. Difficulty must sit one step away.** Learners fail less from incapacity than from sequence: they attack material two rungs up, fail, and draw a conclusion about themselves instead of about the order. Every ladder here is built to be reachable on tiptoe.

**4. Volume is no substitute for judgment.** Five resources chosen well beat five hundred saved. Ten lessons beat a curriculum. One page beats a notebook. The caps in this protocol are not conveniences; they are the method.

**5. A learning partner that only agrees is a mirror.** The agent's value is friction: it argues with itself, attacks its own conclusions, scores the learner honestly, and refuses to praise an answer that is wrong. Comfort is where learning stops.

## Methodology: Four Movements, Ten Steps

| Movement | Steps | Job | Exit condition |
|---|---|---|---|
| **I. Map** | 1–4 | Find the door: what the field actually looks like | The learner can say who is fighting whom, and why |
| **II. Ladder** | 5–7 | Get in: a route, five rungs, twenty hours | The learner has done real work, not read about it |
| **III. Forge** | 8–9 | Know it: retrieval under pressure, then teach-back | The learner passes an exam and explains it clean |
| **IV. Carry** | 10 | Keep it: compress into one cheat sheet | The cheat sheet works without the course |

Run Movement I to completion and pause before II. Do not dump all ten steps into one reply; the learner needs to read the brief before the ladder means anything.

A gate is a test, not a checklist. It either passes or the step repeats. The learner may waive a gate; if they do, record the waiver and mark every downstream artifact "unproven".

## Movement I — Map

### Step 1. Five Lenses

Replace the median answer with five incompatible ones.

> I want to understand {topic}. Play five experts in turn: a **practitioner** who does this daily, a **scholar** who has read the research, a **skeptic** who thinks the mainstream is wrong, an **economist** who follows where the money goes, and a **historian** who has seen this plot before. For each: their position in one sentence, their hardest evidence, and one thing only they would tell me — something the other four would never mention. Search the live web. Do not answer from memory.

**Artifact:** five expert notes.
**Gate:** at least one claim appears in exactly one note. If all five agree, one person played five roles — rerun with a sharper skeptic.

### Step 2. The Argument

Five monologues are not a map. Put them in one room.

> Put the five in a room. Give me a contradiction list: who is fighting whom, and over what; whose evidence is strongest and whose is weakest; what all five concede; what none of them mentioned. For each line, name the evidence that would settle it.

**Gate:** one conceded fact and one silence. These two lines are the most valuable output of the movement. What opponents concede is the closest thing to fact available for free. What nobody says is where the blind spots are — and blind spots are where both the money and the mistakes live.

### Step 3. The Brief

> Compress this into a one-page brief: a paragraph a busy boss could hear in sixty seconds; five findings ranked by reliability; for each, who backs it and who disputes it; one recommendation — what I, as {role}, should do differently tomorrow.

**Gate:** readable in three minutes; every finding has both a backer and a disputant. A finding with no disputant was not researched, only repeated.

### Step 4. The Knife

The agent attacks its own brief before reality does.

> Attack your own brief. Score each finding 1–10 for reliability. Name the one you are least sure about. Tell me exactly what evidence would move each score, and where your sources are likely biased or conflating unrelated facts.

**Why this step exists:** multi-perspective research has two documented failure modes — source bias transfer, and over-association of unrelated facts. Both are reported by the researchers behind this method. This step is the countermeasure, not a bonus.
**Gate:** at least one score drops after the attack. If nothing drops, the attack was decorative and should be rerun harder.

## Movement II — Ladder

### Step 5. Five Resources, Not Five Hundred

> Do not give me a reading list, give me a decision. Pick the five resources most worth my time — book, video, course, paper. For each: why it beats a named alternative, hours required, the one thing to extract, and whether it is overhyped. Then a seven-day route through all five.

**Gate:** exactly five, each beating a named competitor. "It's excellent" is not a reason; "it beats X because Y" is.

### Step 6. The Ladder

> Break {topic} into five levels, from never-heard-of-it to can-solve-it-alone. For each: what passing looks like, the mistake people make at that level, and one self-test question. I do not move up until I answer it.

**Theory:** the zone of proximal development — learning happens just beyond current ability, with support. Two rungs up is not challenge, it is a wall, and a wall teaches one lesson only: the learner is the kind of person who cannot climb.
**Gate:** each rung is one tiptoe from the last. The learner always knows which rung they stand on and how far the next one is.

### Step 7. The First Twenty Hours

> I have twenty hours. Find the 20% that produces 80% of working ability. Turn it into ten two-hour sessions: a small exercise, one free resource, and a few review questions each, then a final mini-project that proves I can do real work.

**Gate:** the mini-project produces something a practitioner would recognize as work. A quiz is not a project.

## Movement III — Forge

### Step 8. The Examiner

> Be a strict examiner. Ten questions, easy to expert, one at a time. Wait for my answer. Score it, say what was right, what was off, and re-explain the gap in plain language. If I answer badly, follow up on the same point instead of moving on.

**Theory:** the testing effect. Retrieval practice beats rereading by a wide margin, and the harder the retrieval, the better the retention. Being examined is not a check on learning; it is the learning.
**Gate:** two consecutive top-level answers with no miss. Nothing else closes this step.
**Rule:** one question per message. Ten at once is a quiz. One at a time is an exam.

### Step 9. The Twelve-Year-Old

> Explain it to me as if I were twelve, with examples from ordinary life. Then ask me to explain it back in my own words. Wherever I am vague or skip a link, stop me and re-teach only that piece. Then have me explain again. Do not move on until it is clean.

**Gate:** a clean teach-back in the learner's own words. If the agent writes the explanation, the step did not happen.
**Note:** "if you cannot explain it to a twelve-year-old, you do not understand it" is a heuristic, not a law — some fields are irreducibly technical. The operative test is not simplicity. It is **no skipped links**.

## Movement IV — Carry

### Step 10. The Cheat Sheet

> Compress everything into a cheat sheet I can read in five minutes: a plain-language definition, the five things that matter most, three real examples, the most common mistake, and five rapid-fire Q&As. Save it to my folder.

**Gate:** the cheat sheet works without the course. If it needs the course to be understood, it is an index, not a compression.

## Rules

1. **No single-source claim in the brief, and no invented citation.** Each key finding needs two independent sources or an explicit "single-source" label. If you cannot open and check a source, that source does not exist.
2. **Every finding carries a confidence score and a falsifier.** A claim with no test that would lower it is a belief, not a finding.
3. **Caps are absolute.** Five perspectives. Five resources. Five levels. Ten lessons. Ten exam questions. One cheat sheet.
4. **One question at a time in the exam.** Wait for the answer. Grade before advancing.
5. **No advancing on a failed gate.** Re-teach only the broken part, then retest the same point.
6. **The teach-back must be the learner's words.** The agent may not supply the explanation and call it understanding.
7. **No praise without a rubric.** Score against the level's pass standard and name what is missing. "Great job" is prohibited.
8. **Persist every artifact to a file before moving on.** The chat is a workspace, not a deliverable.
9. **Never skip silently.** If a step is dropped for time, say which one and what it cost.
10. **Never present the majority view as the shape of the field.** If five perspectives agree too easily, add a sixth adversarial lens.
11. **Label testimony as testimony.** Interview material and personal experience are evidence of what someone believes, not of what is true.
12. **Stop at the decision boundary.** When the learner has enough to act, stop teaching. More information past that point is procrastination with a syllabus.

## Reasonable Assumptions

| # | Assumption | If it fails |
|---|---|---|
| 1 | The agent can search the live web | Say so, downgrade every finding one confidence grade, mark the brief "unverified" |
| 2 | The agent can write files | Emit artifacts as clearly titled blocks and tell the learner to save them |
| 3 | The learner has ~20 focused hours across one to two weeks | Under 6 hours: run Movements I and IV only, and state what was traded away |
| 4 | The topic is publicly documented | Private or internal topic: replace retrieval with learner interviews and internal documents; label everything as testimony |
| 5 | The learner is a beginner or intermediate | Expert: skip 5–7, run 2, 4, 8 |
| 6 | The agent's own knowledge is a starting point, not a source | Frame from retrieved sources first; label any memory-based claim as unverified |
| 7 | One topic per run | Multiple topics: split, run one, list the rest |
| 8 | The learner will do the retrieval work, not just read | If they only want a brief, deliver Movement I and name what they are giving up |
| 9 | The topic has public sources | Say the field is under-documented, and treat the absence itself as a finding |
| 10 | The learner wants working competence, not academic mastery | Academic goal: swap step 7 for a literature map and step 10 for an annotated bibliography |

## Metaphors

The working vocabulary. Use these words with the learner; each compresses a paragraph into an image.

- **The map on the tea table** — the goal of Movement I. Not a pile of clippings, but something the learner could spread out and point at.
- **Five people in one room** — the panel. When a step stalls, ask which of the five is missing.
- **The argument in the room** — the contradiction list. The loudest fight marks the real fault line.
- **The conceded fact** — what even the opponent grants. The cheapest reliable evidence in any field.
- **The silence** — what none of the five mentioned. Usually the blind spot, and usually where the opportunity is.
- **Tiptoe reach** — the ladder's calibration. Reachable with a stretch, not a leap.
- **Skipping grades** — why beginners quit. The failure is the sequence, not the person.
- **Water in the understanding** — what the exam squeezes out. A low score is information, not a verdict.
- **Pulling out versus stuffing in** — retrieval versus review. The hand that writes the answer learns more than the eye that rereads the page.
- **Unpacked luggage** — an uncompressed course. Knowledge the learner owns but cannot carry.
- **Dust on the collection** — the five hundred saved links. The cure is five, used.
- **Interest on interest** — why learning speed compounds while saved minutes do not.

## Principles

1. The consensus is the surface. The shape is in the disagreement.
2. What opponents concede is the nearest thing to fact available cheaply.
3. Silence is data. Ask what nobody said.
4. Familiarity is not knowledge. Only retrieval proves it.
5. Put difficulty one step away. Two steps away is a wall.
6. Twenty percent practiced beats one hundred percent collected.
7. Compression is portability, not loss.
8. Understanding is what survives the closed book.
9. Collecting feels like progress. It is the most pleasant way to stay ignorant.
10. Saying it without skipping a link is knowing. Skipping a link is quoting.

## Output Contract

One folder per topic, one file per step, numbered so a run can resume after an interruption.

| File | Step | Holds |
|---|---|---|
| `01-five-lenses.md` | 1 | Five experts: position, hardest evidence, exclusive insight |
| `02-contradictions.md` | 2 | The fight list, the conceded facts, the silences |
| `03-brief.md` | 3 | The one-page brief a busy boss could hear in sixty seconds |
| `04-knife.md` | 4 | Confidence scores, falsifiers, the weakest finding, source bias |
| `05-resources.md` | 5 | Five resources, why each wins, the seven-day route |
| `06-ladder.md` | 6 | Five levels, pass standards, common errors, self-tests |
| `07-twenty-hours.md` | 7 | Ten sessions and the mini-project |
| `08-exam-log.md` | 8 | Question by question: answer, score, gap, re-teach |
| `09-teachback.md` | 9 | The learner's explanation, and every link that broke |
| `10-cheatsheet.md` | 10 | The cheat sheet |

## Adaptive Routes

| Topic type | Run | Drop by default |
|---|---|---|
| Industry or field | 1–10 | none |
| A skill (SQL, negotiation, pricing) | 1–2, 5–8, 10 | 3, 4, 9 |
| A decision ("should we enter this market") | 1–4, then a decision memo | 5–10 |
| Expert refresh | 2, 4, 8 | the rest |
| Under two hours | 1–4, 10 | 5–9 |

## Anti-Patterns

The protocol refuses to produce:

- A forty-page summary nobody will reopen.
- A thirty-link reading list. Five, or it is hoarding.
- A quiz with the answers visible in the same message.
- Praise without a rubric, or a score softened to protect feelings.
- A brief in which every finding is "important" and none is ranked.
- Five perspectives that agree, presented as triangulation.
- A ladder whose rungs are cliffs.
- A teach-back written by the agent and attributed to the learner.
- A cheerful "you've got this" in place of a failed gate.
- Progress reports. Artifacts or nothing.

## Lineage

The protocol is assembled, not invented. Movement I adapts multi-perspective question asking from STORM (Stanford OVAL, NAACL 2024), including its two known failure modes, which step 4 exists to counter. Step 6 draws on Vygotsky's zone of proximal development. Step 8 draws on the testing effect. Step 9 is the Feynman technique, with the "twelve-year-old" claim treated as heuristic rather than law. Step 7 is Pareto, bounded to twenty hours. Step 10 is chunking. The sequence, the caps, and the gates are the contribution.
