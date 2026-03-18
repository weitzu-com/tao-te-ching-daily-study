---
name: tao-te-ching-daily-study
description: guide daily study of the tao te ching with one chapter at a time, chinese text, faithful classical english translation, concise chinese interpretation, and practical reflection. use when a user asks to start today's tao te ching study, study a specific chapter, continue from the previous lesson, review a chapter, or receive tao te ching learning content in chinese and english.
---

# Tao Te Ching Daily Study

## Overview

Guide one chapter of the *Tao Te Ching* at a time. Default to a calm, concise, practice-oriented lesson that combines the original chinese text, a faithful classical english translation, a clear chinese explanation, and one concrete daily practice.

Do not rely on connectors for normal use. Work directly in the conversation unless the user explicitly asks for source comparison, scholarly notes, or external references.

## Lesson Workflow

### 1. Determine the chapter

Choose the chapter in this order:

1. If the user specifies a chapter number, use that chapter.
2. If the user says "continue" or "继续", continue from the most recently studied chapter visible in the current conversation.
3. If the user says "start today's study" or similar and no prior chapter is visible in the current conversation, begin with chapter 1.
4. If the prior visible chapter is 81 and the user asks to continue, say the cycle is complete and restart from chapter 1 unless the user asks to review a specific chapter.

When progress is not visible, state the assumption briefly and continue without a long clarification.

### 2. Deliver the lesson in the default order

Use the section order below unless the user asks for a different format:

1. 本章原文
2. 中文今译
3. faithful english translation
4. 核心义理
5. 当日践行
6. 反思一问

### 3. Keep the tone aligned

Write with these defaults:

- keep the explanation concise and calm
- favor direct meaning over academic display
- explain the chapter first, then apply it to daily life
- interpret through returning to the root, reducing grasping, softening force, and aligning action with the natural course
- keep each daily practice small, observable, and doable within one day

## Section Rules

### 本章原文

Present the chapter in chinese first.

Use a standard received wording. If there are well-known wording variants that materially change interpretation, keep the main text stable and mention the variant briefly inside the explanation section, not as a long textual note.

### 中文今译

Render the text into natural modern chinese.

- preserve the original logic and paradox
- do not flatten difficult passages into slogans
- prefer short sentences
- clarify implied subjects only when needed for readability

### faithful english translation

Translate into english that is faithful to the classical tone.

- stay close to the structure and meaning of the original
- preserve paradox, compression, and parallelism where possible
- prefer dignified, readable english over casual modern phrasing
- avoid slang, motivational language, and over-explaining inside the translation
- do not turn the translation into commentary

### 核心义理

Explain the chapter in chinese.

Use 2 to 4 short paragraphs or a few tight bullets when that is clearer. Cover:

- what the chapter is pointing to
- what tension, illusion, or habit it is correcting
- how the idea applies to ordinary life, relationships, work, or self-cultivation

Keep the explanation practical. Avoid excessive historical debate unless the user asks for it.

### 当日践行

Give one small practice for the day.

The practice must be:

- concrete
- observable
- low-friction
- tied directly to the chapter's meaning

Examples of appropriate practice:

- pause before responding in one difficult conversation
- remove one unnecessary act of forcing today
- complete one task with less display and more steadiness
- notice one desire to control and let it soften

### 反思一问

End with one open reflection question.

The question should invite self-observation, not a test of memory. Keep it short and pointed.

## Default Output Template

Follow this structure unless the user requests a different one:

### 第[章号]章

**本章原文**
[chapter text]

**中文今译**
[modern chinese rendering]

**Faithful English Translation**
[faithful classical english translation]

**核心义理**
[concise explanation]

**当日践行**
[action for today]

**反思一问**
[one reflection question]

## Response Quality Bar

Before finishing, verify that the lesson:

- includes both chinese and english
- keeps the english faithful rather than overly modernized
- makes the chinese explanation understandable without becoming shallow
- gives one practical action, not a vague moral slogan
- ends with exactly one reflection question unless the user asks for more

## Adaptation Rules

Adapt when explicitly requested:

- if the user asks for deeper philosophy, expand the explanation and compare interpretations
- if the user asks for practice focus, expand the daily application and keep theory short
- if the user asks for management, family, or self-cultivation framing, keep the same chapter but tilt the explanation toward that context
- if the user asks for only chinese or only english, still preserve the lesson logic while reducing the unused parts

## Example Triggers

Use this skill for requests like:

- 开始今天的《道德经》学习
- 学习第 17 章
- 继续上一篇
- 给我一章《道德经》中英对照解读
- 用忠实经典的英文翻译讲解《道德经》第 8 章
