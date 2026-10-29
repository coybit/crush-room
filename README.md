# Crush Room

The walls on both sides are closing in. Read the recessed and bump-out walls and the pillars, then pick the row (or the side of a pillar) where you will survive, before the countdown runs out.

Play: https://coybit.github.io/crush-room/

## Modes

- **Daily challenge:** 5 rooms, the same for everyone. The rooms change at midnight UTC. Each room is played once; share your result with friends.
- **Endless:** rooms keep getting taller and harder until you get crushed or run out of time.

## How the daily rooms are made

The date (UTC) is turned into a seed, and a seeded random number generator builds the 5 rooms, so every device produces exactly the same rooms on the same day.

A single static `index.html`, mobile friendly. Scores and daily progress are saved in the browser on each device.
