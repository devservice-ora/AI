# 💬 Interactive Prompt Guides

The **PARTS** framework (from Google AI Educator training) is a chronological way to shape interactions with large language models and AI agents. It is useful for educators and learners who want more reliable, reusable prompts.

**See also:** [Interactive Prompt Examples](https://github.com/devservice-ora/AI/blob/main/Common%20AI%20prompt%20examples.md)

---

## PARTS

Work through these in order.

1. **Purpose** — State the objective of this interaction so the model knows what success looks like.
2. **Audience** — Name who the output is for and their knowledge level or interests.
3. **Relevance** — Supply the specific context, constraints, and facts the model needs.
4. **Tone** — Say how the response should sound (formal, conversational, concise, supportive, and so on).
5. **Structure** — Describe the format you want (bullets, steps, table, short paragraphs, headings).

### Related framing (persona variant)

1. **Persona** — Who you are in this request.
2. **Aim** — What you want to achieve.
3. **Recipients** — Who will read or use the result.
4. **Theme** — The tone (keep it conversational and engaging unless you need otherwise).
5. **Structure** — A clear, organized format.

Following PARTS in sequence tends to produce outputs that need less repair.

---

## Suggested rules

Use these whenever you write or revise a prompt. They sit underneath PARTS.

### Consistency
Keep terms, constraints, and success criteria the same across the prompt and any follow-ups.
- Reuse the same names for roles, audiences, and deliverables.
- If you set a length, format, or exclusion in Purpose or Structure, do not contradict it later.
- In multi-turn work, restate only what changed; do not silently redefine the task.

### Clarity
Make each instruction unambiguous and checkable.
- Prefer one concrete ask over a stack of vague verbs (“summarize in 5 bullets for grade 8” rather than “make this better”).
- Define audience level and any must-include or must-exclude items under Relevance.
- Replace subjective words (“engaging,” “professional”) with observable cues when Tone alone is not enough.

### Separation
Keep distinct jobs in distinct parts of the prompt so the model does not blend them.
- Purpose states the goal; Relevance holds source facts and constraints; Structure holds format only.
- Do not bury the real task inside background text or examples.
- If you include an example, label it as an example so it is not treated as new instructions.

### Avoid over-engineering
Add only the instructions that change the result. Extra rules, nested conditions, and unused frameworks usually make outputs worse, not better.
- Start with Purpose, Audience, and Structure. Add Relevance and Tone only where they matter.
- Do not stack personas, scoring rubrics, chain-of-thought demands, and format rules unless each one is required.
- If a shorter prompt already gets the draft you need, stop. Complexity is a cost, not a quality signal.
- Drop constraints you will not check.

### Avoid ambiguity
Do not leave the model to guess which reading you meant.
- Replace words with more than one reasonable meaning (“short,” “recent,” “appropriate,” “cover this”) with a bound: length, date, audience, or scope.
- One prompt, one main task. If you need two deliverables, say so and separate them.
- State exclusions explicitly (“do not include citations”) instead of hoping the model infers them.
- If an example could be read as the new task, label it as an example.

### How the rules map to PARTS

| Rule | Where it shows up in PARTS |
| --- | --- |
| Consistency | Same terms in Purpose, Audience, and Structure; stable constraints across turns |
| Clarity | Precise Purpose, explicit Audience, concrete Relevance details |
| Separation | Purpose ≠ context ≠ format; examples labeled and kept apart from instructions |
| Avoid over-engineering | Shortest PARTS set that still specifies the real task; no unused fields |
| Avoid ambiguity | Checkable Purpose and Structure; bounded Relevance; no double meanings |

---

## Human in the loop

Google’s AI Principles call for a **human-in-the-loop** approach: the model supplies a first draft; you use your expertise to accept, edit, or reject it. PARTS plus these rules improve that first draft. They do not replace review.
