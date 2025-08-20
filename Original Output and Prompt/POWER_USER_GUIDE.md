# POWER\_USER\_GUIDE.md

**Spanish Voice Tutoring Project for ChatGPT Projects and GPT-5**

This guide shows you exactly how to run fast, effective voice sessions using the provided Project instructions, prompt pack, and 4-week plan. It is written in English for setup and control. The live sessions happen in Spanish.

---

## Contents

* [What you need](#what-you-need)
* [Quick start](#quick-start)
* [Session types](#session-types)
* [Live control: micro-commands](#live-control-micro-commands)
* [Immediate correction workflow](#immediate-correction-workflow)
* [Shadowing in 60 seconds](#shadowing-in-60-seconds)
* [Spaced review inside a call](#spaced-review-inside-a-call)
* [Adaptive difficulty](#adaptive-difficulty)
* [Time templates](#time-templates)
* [Using the prompt library](#using-the-prompt-library)
* [Daily and weekly routine](#daily-and-weekly-routine)
* [Customization](#customization)
* [Quality checks and self-tests](#quality-checks-and-self-tests)
* [Troubleshooting](#troubleshooting)
* [Appendix: ready-to-say starters](#appendix-ready-to-say-starters)

---

## What you need

* ChatGPT Projects with the included `PROJECT_INSTRUCTIONS.yaml`.
* The `SESSION_PROMPTS.json` prompt library.
* The `PLAN_4_WEEKS.md` plan.
* Voice mode enabled.

All optimization is for GPT-5 and ChatGPT Projects. Ignore older models.

---

## Quick start

1. **Create a new Project** and paste `PROJECT_INSTRUCTIONS.yaml` into the instruction area. Save.
2. **Attach the prompt library** content somewhere handy for copy or reference. The Project does not require tool calls.
3. **Pick your session length**: 5, 10, 15, or 20 minutes.
4. **Say this to begin**:

   * Learner-led: `Modo alumno. Quiero hablar sobre mi día.`
   * Tutor-led: `Modo tutor. Tema: pretérito vs imperfecto.`
5. Stay in Spanish. Use micro-commands to steer. End with the recap. The tutor will read the session log.

---

## Session types

### A) Learner-led topic

* You choose the topic from your life.
* No new topics introduced by the tutor.
* Corrections are immediate and minimal.
* Goal: fluency and comfort while fixing live errors.

**Starter lines**

```
Modo alumno. Quiero hablar sobre mi rutina de mañana.
Modo alumno. Hoy quiero contar un recuerdo de un viaje.
```

### B) Tutor-led topic

* Tutor selects or you request a focus area.
* Brief teach-through inside conversation.
* Includes 2 to 3 micro-drills.
* Goal: targeted growth in vocab or structure.

**Starter lines**

```
Modo tutor. Practiquemos dar consejos con “deberías” y el imperativo.
Modo tutor. Subjuntivo con opiniones: “no creo que...”.
```

---

## Live control: micro-commands

Say these in Spanish at any time. The tutor must comply immediately.

| Command              | Effect                                          |
| -------------------- | ----------------------------------------------- |
| `otra vez`           | Repeat the last question or instruction.        |
| `más despacio`       | Slow down one step.                             |
| `más rápido`         | Speed up one step.                              |
| `pausa`              | Hold until you say `continuar`.                 |
| `explícame`          | Shorter, clearer explanation in simple Spanish. |
| `ejemplo`            | One or two fresh examples.                      |
| `¿cómo se dice ___?` | Quick translation or phrasing tip.              |
| `repite`             | Exact repetition for listening.                 |
| `dictado`            | One or two sentences for echo or jotting.       |
| `sombras`            | Start a 30 to 45 second shadowing segment.      |
| `sin correcciones`   | Suspend corrections. Resume with `corrígeme`.   |
| `ayuda` o `pista`    | Prompt or key word to unlock your sentence.     |
| `continuar`          | Resume after pause or drill.                    |

Keep commands short. Do not switch to English for control.

---

## Immediate correction workflow

Protocol used in both modes:

1. **Detect** the error.
2. **Interrupt briefly**.
3. **Provide the fix** plus a **very short metalinguistic cue**.
4. **Ask you to repeat** the corrected full sentence.
5. **Confirm** quickly.
6. **Resume** the conversation.

**Example**

* You: `Mi madre es orgullosa de mí.`
* Tutor: `Se dice “está orgullosa” porque es un estado. Repítelo: “Mi madre está orgullosa de mí”.`
* You repeat. Tutor confirms and continues.

Use `sin correcciones` if you need a break. The tutor may batch minor issues until the recap.

---

## Shadowing in 60 seconds

Shadowing builds pronunciation, rhythm, and parsing.

* Trigger with `sombras`.
* The tutor talks for 30 to 45 seconds on a simple topic.
* You speak at the same time, matching sounds and intonation.
* One pass slow, one pass near natural speed.
* Return to conversation. Ask for `repite` if you missed a segment.

Do this 1 to 2 minutes total in longer sessions. Skip in 5 minute sprints.

---

## Spaced review inside a call

Use quick re-queues:

* When a new word appears at minute 2, the tutor resurfaces it around minutes 5 and 8.
* Each time, you must produce it, not only recognize it.
* At the end, the recap lists new items and flags them for tomorrow.

For multi-day spacing follow the Plan: next day, then 3 to 4 days later, then about a week later.

---

## Adaptive difficulty

* If you are cruising, the tutor tightens: richer vocab, more complex prompts, faster speech, light idioms.
* If you struggle, the tutor simplifies: shorter questions, slower pace, more examples, focused correction.
* Request a push: `Dame preguntas más difíciles`.
* Request relief: `Más sencillo, por favor`.

Target a success rate near 70 to 80 percent. That feels a bit hard and is right for growth.

---

## Time templates

Use these splits to avoid drift.

**5 minutes**

* 1 warm-up recall
* 3 core talk or one drill
* 1 recap

**10 minutes**

* 2 warm-up recall
* 6 conversation plus one micro-drill
* 1 short shadowing
* 1 recap

**15 minutes**

* 3 warm-up recall of 2 older items
* 9 conversation plus two micro-drills
* 2 shadowing
* 1 recap

**20 minutes**

* 4 warm-up recall quiz
* 12 conversation plus three micro-drills
* 2 shadowing or role-play
* 2 recap with spaced cues for tomorrow

---

## Using the prompt library

You have 30 plug-and-play sessions in `SESSION_PROMPTS.json`:

* 15 learner-led prompts that stay on your life.
* 15 tutor-led prompts focused on a grammar or lexical theme.

**How to use**

1. Pick a prompt that fits your goal and level.
2. Say the title in Spanish, then the focus.
3. Let the tutor run the three micro-drills that are listed for that prompt.
4. Ensure the 90 second recap runs. It seeds tomorrow’s review.

**Example call**

```
Modo tutor. Use el prompt “Debate: Technology”. Quiero practicar opiniones con subjuntivo.
```

---

## Daily and weekly routine

* Follow `PLAN_4_WEEKS.md`. It mixes new topics with planned review.
* Hit 5 sessions per week.
* Keep most sessions 10 to 15 minutes. Add a 20 minute slot once per week for deeper practice.
* Protect the recap. Never cut it.

---

## Customization

You can adjust the Project without breaking the core behaviors.

1. **Level bias**

   * To bias upward: start the session with `Hoy, habla más rápido y usa vocabulario más avanzado. Corrígeme errores menores también.`
   * To bias downward: `Habla más despacio y haz preguntas más cortas. Corrige solo lo esencial.`

2. **Register**

   * Default is mostly `tú`.
   * For formal practice: `Hoy usemos usted todo el tiempo. Corrija cualquier tuteo.`

3. **Cultural flavor**

   * Keep neutral by default.
   * Add opt-in flavor: `Incluye un dato cultural breve si encaja con el tema.`

If you edit the YAML later, keep the correction protocol intact and leave the guardrails in place.

---

## Quality checks and self-tests

Run these quick tests once per week.

* **Immediate correction**
  Say one intentional error. You should get fast fix, tiny cue, and a required repeat.

* **In-session review**
  Ask for a word at minute 2. It should reappear later in the same session.

* **Interleaving**
  During a new topic, the tutor should slip in a quick use of an older structure.

* **Micro-commands**
  Say `sombras`, `pausa`, `más despacio`. The tutor should pivot instantly.

* **Logging**
  The end log should list minutes practiced, new items, and 2 to 3 corrections.

If any fails, state a runtime reminder:
`Sigue el protocolo de corrección inmediata con repetición obligatoria. Repite mi frase corregida y espera mi eco.`

---

## Troubleshooting

**The tutor slips into English**
Say: `Solo español, por favor.`

**Corrections feel too frequent**
Say: `Solo corrige errores que afecten la comprensión. El resto al final.`

**Not enough challenge**
Say: `Preguntas más complejas y vocabulario menos frecuente, por favor.`

**Shadowing is too hard**
Say: `Primero muy despacio, luego velocidad normal.`
Then use `repite`.

**Time overrun**
Say with 2 minutes left: `Recapitulación ahora. Dame el resumen y los ítems nuevos.`

**JSON prompts look heavy**
You can run a prompt’s drills without the full list. Say:
`Usa las tres micro-prácticas del prompt, pero mantén respuestas breves.`

---

## Appendix: ready-to-say starters

Copy these into voice mode.

**Warm-ups**

```
Repásame dos palabras de ayer.
Pregúntame algo que use el pasado y un conector.
```

**Learner-led**

```
Modo alumno. Quiero hablar sobre [mi semana].
No introduzcas temas nuevos. Corrígeme en el momento.
```

**Tutor-led**

```
Modo tutor. Tema: [subjuntivo con opiniones]. Haz dos micro-prácticas y un minuto de sombras.
```

**Push or ease**

```
Dame preguntas más difíciles y habla más rápido.
Más sencillo y más despacio, por favor.
```

**Correction control**

```
Corrígeme cada error con una pista breve y pídeme repetir la frase completa.
Sin correcciones por ahora. Retoma correcciones en cinco minutos.
```

**Closeout**

```
Haz el resumen con ítems nuevos, errores y minutos practicados.
Mañana recuérdame dos palabras de hoy.
```

---

### Final notes

* Stay in Spanish during the session. Use micro-commands to control flow.
* Protect the recap. It powers spaced retrieval tomorrow.
* Track confidence at the end from 1 to 5. Adjust difficulty next time based on it.

That is all you need to run smooth, high-yield voice sessions with this Project.
