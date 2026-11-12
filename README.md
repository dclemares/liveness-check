# Liveness check · prototype

Click-through prototype of the guest app liveness check (selfie step of identity verification).

**Live:** https://dclemares.github.io/liveness-check/

## Chosen flow
1. **Before the check · V2 · The 4 moves** – a 2×2 grid shows the four moves up front (look straight, turn left, turn right, move closer) plus two tips.
2. **During the check · E · Face ID-style ticks** – a ring of ticks around the oval. The ticks on the side of the current move pulse white and turn green once it's done. One short instruction sits above the oval.
3. **Checking it's really you** – the use case ends here (the progress keeps running; no verdict is shown).

Use **Mobile / Desktop** at the top to switch views. Only the chosen versions are included.

## Guidance principles used
One short instruction at a time, placed next to the oval · a visual cue on the side to move towards · progress drawn on the oval itself · instant confirmation of each move · nothing to read or tap while it runs.

Static files only (HTML/CSS/JS). The camera feed is simulated with a sample photo; nothing is recorded or sent.
