---
name: give-me-the-english
description: Write one ready-to-use Teacher English script (classroom language) for an activity the teacher already has. Use when a teacher asks what to say in English while running an activity, e.g. "give me the English", "teacher talk for this activity", "what should I say in class", "berikan bahasa Inggrisnya", "instruksi dalam bahasa Inggris", "apa yang harus saya katakan di kelas", "buatkan script guru".
---

# Give me the English

First apply the shared principles in the `peyl-core` skill (`peyl-design-partner:peyl-core`).

## Essential rules (apply even if `peyl-core` is not loaded)

- The whole response is in English, always, even when the teacher writes in Indonesian.
- Never invent student target language. If it is not supplied, write `[existing frame]` in student lines.
- Do not redesign the activity; keep the supplied sequence and give one script.
- Keep Teacher English (simple, short, repeatable) separate from Student English.
- Never use the teacher's personal name.

## Rules

- **Write the entire response in English**, including headings and notes, even when the teacher writes in Indonesian. Only translate if the teacher asks separately.
- Provide **one** coherent script for the activity the teacher supplied. Do not give multiple versions unless asked.
- **Preserve the supplied sequence.** Do not redesign the activity or add steps.
- Teacher English is simple, natural, short and repeatable: one instruction per sentence, the same phrase for the same action every time, with gestures noted.
- Keep **Teacher English** separate from **Student English**. Student lines use only the target language the teacher supplied. If it was not supplied, write `[existing frame]` instead of inventing it.
- Do not add new classroom vocabulary or grammar that the activity does not need.

## Output

A short table or list, one row per step of the teacher's activity:

| Step | Teacher says | Teacher does | Learners say or do |
|------|--------------|--------------|--------------------|

End with at most two reusable routine phrases (for example for attention or for pairing up), only if they are used in the script.

## Example (invented for illustration)

Teacher: Aktivitas saya: (1) murid berpasangan, (2) murid A menyembunyikan benda, (3) murid B menggambar apa yang didengar. Kalimat murid: "I have a ___."

| Step | Teacher says | Teacher does | Learners say or do |
|------|--------------|--------------|--------------------|
| 1 | "Find a partner." | Points to pairs, mimes holding hands up | Move and sit with a partner |
| 2 | "A, hide three things." | Hides objects behind a book as a model | A hides three objects |
| 3 | "A, say. B, draw." | Mimes speaking, then drawing | A says "I have a ___."; B draws |

Student English in this example comes from the teacher's supplied frame, not from the script. (The request above was in Indonesian; the response is entirely in English.)
