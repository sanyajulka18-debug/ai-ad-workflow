# AI Workflow Templates for Video Ads

Reusable, plain-text templates I use to make short-form video ads (Reels, Shorts, Meta ads) with AI tools.
Each template turns one stage of ad production into a fixed set of steps and checks, so every ad goes
through the same process and the same mistakes don't repeat.

No code needed: every template is a Markdown file you fill in or paste into an AI assistant (I use Claude).

## Why I made this

Every ad I made was repeating the same steps: collect brand facts, study a reference ad, write the script,
write prompts for AI video, check the clips, edit, add captions. When those steps lived only in my head,
things slipped: a brand name pronounced wrong, a line said twice in a clip, a claim the brand doesn't allow,
captions out of sync. Writing each stage down as a template fixed that.

## The workflow

```
Brief ──► 1. Brand sheet ──► 2. Reference breakdown ──► 3. Script
                                                          │
   7. Final check ◄── 6. Edit & captions ◄── 5. Clip check ◄── 4. AI video prompts
          │
          └──► Mistakes log (what went wrong + the fix) ──► templates updated
```

| # | Template | What it does |
|---|---|---|
| 1 | [Brand sheet](templates/01-brand-sheet.md) | One page of brand facts: product look, how it's shown, claims to make or avoid, pronunciation |
| 2 | [Reference ad breakdown](templates/02-reference-ad-breakdown.md) | Breaks a competitor or reference ad down shot by shot so the new ad can match its pacing and look |
| 3 | [Ad script](templates/03-ad-script.md) | Hook, body and call-to-action in a fixed format, with 3 hook options to test |
| 4 | [AI video prompt](templates/04-ai-video-prompt.md) | One prompt per clip: scene, people, camera, light, exact dialogue, voice and sound |
| 5 | [Clip check](templates/05-clip-check.md) | Checks every generated clip against the script before editing starts |
| 6 | [Edit & captions](templates/06-edit-and-captions.md) | Edit order, pacing, colour and caption-style choices |
| 7 | [Final check](templates/07-final-check.md) | Last checklist before the ad is delivered |
| – | [Mistakes log](templates/mistakes-log.md) | Records each problem and its fix, so the templates improve over time |

## How to use it

1. Copy the templates folder for a new ad.
2. Fill the **brand sheet** once per brand; reuse it for every ad of that brand.
3. Work through templates 2 → 7 in order. Each one ends with a short checklist: don't move on until it's ticked.
4. When something goes wrong, add a line to the **mistakes log**. If the same problem appears twice,
   add a new check to the template where it should have been caught.

With an AI assistant: paste the template plus your inputs (brief, script, brand sheet) and ask it to
fill the template. The fixed structure keeps the AI's output consistent from ad to ad.

## Example

[example/sample-ad-walkthrough.md](example/sample-ad-walkthrough.md) runs one sample ad through every
template, from a one-line brief to a final checklist. It uses a made-up product (BrewBright cold coffee),
not a real client.

## What changed after using templates

- Every ad follows the same steps, so nothing depends on memory.
- Problems are caught at the clip-check stage, before editing time is spent.
- New ad formats take less time to set up: copy the closest template and change only what's different.

## Tools

Claude (AI assistant), an AI video generator, a video editor (CapCut), GitHub for version history.

---
Made by **Sanya Julka** · [LinkedIn](https://www.linkedin.com/in/sanya-julka-91a7b535a)
