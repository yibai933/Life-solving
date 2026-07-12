---
name: yuhua-writing-sop
description: Analyze Yu Hua's collected works and use them as a reusable Chinese essay-writing SOP. Use when the user asks to write, plan, or polish articles inspired by Yu Hua, especially tasks involving topic selection, titles, persona, core themes, emotional arc, material framework, aphorisms, endings, or a complete article based on Yu Hua's novels, short stories, essays, or writing theory.
---

# Yu Hua Writing SOP

## Overview

Use this skill to turn Yu Hua's works into a repeatable article creation pipeline. The output should feel like a sharp, readable Chinese essay: concrete, humane, lightly humorous when appropriate, and built from story pressure rather than abstract preaching.

Load `references/yuhua-creation-model.md` when the task requires deep analysis, topic generation, title design, emotional curve, material selection, or full article writing.

## Workflow

Run the process in stages unless the user explicitly asks to skip ahead.

1. Diagnose the input theme.
   - Identify the human conflict behind the theme: survival, dignity, family debt, bodily cost, memory, absurd reality, social acceleration, or ordinary endurance.
   - Name the target reader and the desired aftertaste: pierced, comforted, amused, ashamed, sobered, or moved.

2. Generate 3-5 topic options.
   - Each option must include a topic angle, suitable Yu Hua source material, audience pain point, and why it can carry an article.
   - Prefer angles that connect Yu Hua to a present-day experience without forcing trendy language.

3. Generate 5-8 titles for the chosen topic.
   - Mix direct, metaphorical, counterintuitive, and emotional titles.
   - Avoid generic titles such as "读余华有感" unless the user requests a plain style.

4. Design the article engine.
   - State the central thesis in one sentence.
   - Provide 3-4 sub-arguments.
   - Design an emotional curve with 4-6 beats: hook, recognition, descent, turn, clarity, lift.
   - Define the narrative persona: witness, late-night friend, cold-eyed commentator, self-mocking survivor, or public-topic essayist.

5. Build the material framework.
   - Use Yu Hua material as evidence, not decoration.
   - Pair literary scenes with modern-life equivalents.
   - Include a "do not overuse" note for any material that is too famous, too sentimental, or too easily clichéd.

6. Draft golden lines.
   - Produce 8-12 reusable lines before drafting.
   - Lines should sound earned by the argument, not pasted in for decoration.
   - Favor plain language with a sudden knife edge.

7. Write the full article.
   - Default length: within 2000 Chinese characters unless the user asks otherwise.
   - Use few headings or none; prefer natural essay flow.
   - Keep the tone vivid, incisive, and grounded. Avoid report-like enumeration in the final article.

8. Revise once.
   - Remove empty praise, over-explained morals, and generic transitions.
   - Strengthen the opening, one middle turn, and the ending sentence.

## Output Pattern

When the user asks for the full staged process, output in this order:

- Task map
- 3-5 topic options
- 5-8 title options after a topic is chosen or provisionally selected
- Theme, thesis, emotional curve, persona, framework, material plan, golden lines, ending lift
- Full article

If the user says "continue" or "下一步", move to the next stage decisively using the prior choice or the strongest option.

## Style Guardrails

- Do not imitate Yu Hua sentence by sentence.
- Do not quote long passages from copyrighted works.
- Do not turn suffering into cheap motivational copy.
- Do not over-label everything with "苦难"; identify the precise mechanism: loss, debt, shame, hunger, absurdity, endurance, bodily exchange, or memory.
- Keep the final prose more like an essay a person would share than a school-style literary report.
