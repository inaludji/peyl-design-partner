# My PEYL Design Partner

A skills-only plugin that helps Indonesian primary English teachers (Grades 3–6) design, improve, simplify, scaffold, extend, run and check English-learning activities using PEYL principles.

It does not connect to any app, server or external service, and it does not store or send data.

## What it does

| Skill | Use it when you want to... | Example requests |
|-------|----------------------------|------------------|
| `design-activity` | Create a new activity from your purpose and context | "Buatkan aktivitas speaking untuk kelas 3" |
| `improve-activity` | Get the smallest useful improvement to your activity | "Tolong review aktivitas saya" |
| `make-easier` | Reduce load when an activity is too hard, without lowering the goal | "Terlalu sulit, tolong permudah" |
| `add-scaffolding` | Add temporary, removable support, with a fade plan | "Beri dukungan bertahap untuk tugas ini" |
| `extend-activity` | Extend for fast finishers or link to another skill | "Pengayaan untuk murid yang cepat selesai" |
| `give-me-the-english` | Get one Teacher English script for your activity | "Apa yang harus saya katakan di kelas?" |
| `check-learning` | Get a light check that matches your objective | "Bagaimana mengecek apakah murid sudah bisa?" |
| `peyl-core` | Shared principles used by all the skills above | (loaded automatically) |

## Core idea

**NEED → ACTION → EVIDENCE.** Language needs a reason to matter. For every activity: what do learners need the English for, what does every learner do, and what can the teacher see or hear that shows learning?

## How it treats textbooks

This plugin contains **no textbook content**. It works from what you tell it: the unit, the activity, the target language you paste or describe. It labels ideas as Textbook-based, Textbook-adapted, Textbook-extended or Project-based, and it never invents textbook content or target language. If you say the existing language must stay unchanged and do not supply it, it uses a placeholder such as `[existing frame]` instead of guessing.

## Language

- **Chat:** it replies in the language you choose or write in, English or Bahasa Indonesia (Bahasa Indonesia if unclear).
- **Activities:** titles are bilingual (English / Indonesian); everything inside the activity is in English.
- **Give me the English:** always entirely in English.
- Student target language is English.

## Three examples to try

1. **Design.** "Buatkan aktivitas speaking untuk kelas 3. Murid sudah belajar 'I have a ___.' Waktu 15 menit." You get one activity with a bilingual title, English content, minimum support and a short check of learning.
2. **Improve.** "Improve this activity: learners stand one by one and say their favourite food while the class listens." You get what already works, the main weakness, and the smallest useful fix, written in English.
3. **Give me the English.** "Berikan bahasa Inggrisnya: (1) pair up, (2) A hides objects, (3) B draws." You get one Teacher English script in English, in the sequence you gave.

These are example requests only. The plugin contains no textbook content.

## Install

Install it from the Claude directory once it is listed, or from a marketplace or folder your trainer shares with you.

## Privacy

The plugin is instructed not to use a teacher's personal name in its answers. Please do not paste learners' names or personal details into your requests.

## Maintaining the plugin

Each mode skill repeats a short "Essential rules" block from `peyl-core`, so the rules still apply if the shared skill is not loaded. If you change a principle in `skills/peyl-core/SKILL.md`, update those blocks in the other seven skills too, and raise `version` in `.claude-plugin/plugin.json` before each release.

## Licence and terms

Copyright 2026 PEYL Design Partner. This plugin is licensed under the Creative Commons Attribution-NonCommercial 4.0 International licence (CC BY-NC 4.0); the full text is in the `LICENSE` file. You may share and adapt it for non-commercial purposes if you give credit to "PEYL Design Partner" and indicate any changes you made. Commercial use is not permitted without the author's permission.

## Contact

Questions or feedback: https://sites.google.com/view/peyl-design-partner/
