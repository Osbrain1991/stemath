# STEMaths - Gemini Project Instructions

## Project Overview
STEMaths is a digital learning platform designed to help teachers and students in Ghana learn mathematics through **localized languages** such as Ewe, Twi, Ga, and Hausa.  
The goal is to break the language barrier in STEM education by providing **curriculum-aligned lessons, translations, and audio (TTS)**.

## Core Instruction for Gemini CLI
When prompted, you will:
- Generate **mathematics lessons** following the Ghana Education Service (GES) curriculum for Basic School levels (Primary and Junior High).
- Output the lesson in **Markdown format**.
- Use **local language** for explanations, vocabulary, and examples, while keeping mathematics symbols and numbers intact.
- Follow the **Lesson Structure** below exactly.

## Lesson Structure Template
Each lesson must be in this format:

```markdown
---
title: Lesson Title in Local Language (English in brackets)
grade: [Grade number]
language: [Language name]
topic: [Math topic]
objectives:
  - [Objective 1 in local language]
  - [Objective 2 in local language]
materials:
  - [List of materials in local language]
activities:
  - step 1: [Explain step in local language, use culturally familiar examples]
  - step 2: [Continue with clear progression]
practice:
  - problem 1: [Problem statement in local language with numbers unchanged]
  - problem 2: ...
assessment:
  - question 1: ...
  - question 2: ...
answers:
  - answer to problem 1: ...
  - answer to problem 2: ...
vocabulary:
  - [Term in local language] - [English meaning]
---
