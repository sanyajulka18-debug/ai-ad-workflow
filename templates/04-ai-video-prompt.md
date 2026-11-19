# 4. AI video prompt

One prompt per clip. AI video tools make short clips (often 5–15 seconds), so the script is split
into clips first, then each clip gets a prompt in this exact shape.

## Clip plan
| Clip | Script lines | Length | Location | People |
|---|---|---|---|---|
| H1 | Hook 1 | | | |
| B1 | Body lines 1–2 | | | |
| CTA | CTA | | | |

## Prompt template

```
CLIP: [clip id] · [length] seconds · vertical 9:16

SCENE: [place, time of day, what's around]
PEOPLE: [who is in frame: age, look, clothes — same words every clip]
PRODUCT: [only if in frame — copied from the brand sheet]

CAMERA: [shot size + movement, e.g. "handheld medium shot, slow push-in"]
LIGHT & COLOUR: [e.g. "soft afternoon daylight, warm natural colour"]

ACTION: [what happens, in order]

DIALOGUE (exact words, nothing added):
[SPEAKER] ([voice: age, accent, energy]): "line"

SOUND: [background sound only from what's in the scene; no music unless the script asks]

AVOID: [things that went wrong before: extra words, text on screen, logo changes]
```

## Rules
- Dialogue is copied from the script word for word. Never let the prompt "improve" a line.
- People and product are described with the **same words in every clip**, so they look the same.
- One clear action per clip. Two big actions in one clip usually breaks.
- Add anything from the mistakes log to the AVOID line.

## Checklist
- [ ] Every script line is in exactly one clip
- [ ] Each clip's dialogue fits its length when read aloud
- [ ] People and product descriptions match across clips
