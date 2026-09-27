# Project Showcase

## Shukatsu OS

[Open the interactive demo](https://yaenyanyako.github.io/shukatsu-os-showcase/) · [Repository](https://github.com/YAEnyanyako/shukatsu-os-showcase)

### Problem

Recruitment notices can refer to different tracks at the same company. An invitation, a confirmed booking, an application deadline, and a cancellation deadline each require different actions.

### Product decisions

| Problem | Design |
|---|---|
| A company's context is scattered across messages | Use company workspaces as the main entry point |
| Different recruitment tracks get mixed together | Organize company → project → event |
| An invitation can be mistaken for a booking | Keep notification type, confirmation evidence, and next action distinct |
| Dates have different meanings | Separate submission deadlines, event times, and cancellation deadlines |
| Unclear information can lead to wrong actions | Keep unknown items pending and show supporting evidence |

### Explore the demo

The fictional dataset includes 4 companies, 7 projects, and 12 initial message samples. Browse company-grouped messages, project deadlines, ES drafts, research materials, interview preparation, and the Calendar simulation. Re-running classification demonstrates duplicate handling.

![Overview with fictional data](assets/shukatsu-overview.png)
![Company-first inbox with fictional data](assets/shukatsu-inbox.png)

The public demo uses structured sample data. It does not fetch real email, run live AI inference, send messages, make bookings, or connect a real calendar. Calendar actions are simulated.

## Kotobacho

[Repository and installation instructions](https://github.com/YAEnyanyako/kotobacho)

### Problem

An unfamiliar word in a Japanese video is easier to review when its reading, meaning, context, and source scene stay together.

### Product decisions

- Start with a video rather than requiring a built-in placement test.
- Create lessons from inspected Japanese captions, with vocabulary linked to source timestamps.
- Provide Today, To Learn, All Vocabulary, and Video Archive views.
- Support search, usage and status filters, and word-status changes.
- Keep learning records local and separate from public examples.

![Vocabulary library with fictional examples](assets/kotobacho-vocabulary.png)
![Lesson with fictional examples](assets/kotobacho-lesson.png)

These are actual UI screenshots loaded with an authored fictional lesson. The sample is not a real video transcript or a personal learning record. Screenshot counts are demonstration data, not adoption or learning-outcome metrics.

## Implementation and verification

The projects use AI-assisted development. Public repositories document the implementation and available verification results. This showcase makes no claims about external user adoption, time saved, or measured learning outcomes.
