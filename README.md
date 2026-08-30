# 🐸 Lily Pad Hopper 🪷

A gentle pond-crossing game for kids: hop your frog across the drifting lily pads and
zap bugs with your big stretchy tongue along the way!

**▶️ Play it here: https://jmrogers-it.github.io/lily-pad-hopper/**

## How to play

Hop from lily pad to lily pad all the way to the far bank. Catch as many bugs as you
can on the way — dragonflies and flies buzz around the pond, and your tongue can
reach them from a nearby pad.

There's no way to lose! Hop into the water and the frog just splashes, paddles to the
nearest pad, and climbs back on.

### The four ponds

1. **Sunny Pond** — a gentle warm-up across calmly drifting pads.
2. **Firefly Dusk** — the sun sets and glowing fireflies come out to be caught.
3. **Rushing River** — a current carries the pads sideways, a different direction
   each row, so time your hops as they float by.
4. **Turtle Starlight** — a starry night where some "pads" are friendly turtles.
   They bubble when they're about to dive — hop off in time, or enjoy the swim!

Reach the far bank and you'll see how many of that pond's bugs you caught, then it's
straight on to the next one. Cross all four and the game tallies up every bug you
caught along the way.

### Controls

| Device | Hop | Catch a bug |
|---|---|---|
| iPad / touch | Tap a lily pad | Tap a bug |
| Mouse | Click a lily pad | Click a bug |
| Keyboard | Arrow keys or WASD | Space (zaps the nearest bug) |

Tap the screen or press any key to start — and again to move along between ponds.

Helpful hints built into the game:
- Lily pads you can reach glow with a white ring.
- Bugs your tongue can reach get a soft yellow sparkle.
- The bar on the right shows how far you've hopped: 🐸 is you, 🏁 is the far bank.
- The counter up top tracks bugs caught and which pond you're on.

### Sounds

The frog has a voice — a croaky little *rrr-RIBBIT*, which he'll also let out on his
own if he's left sitting on a pad too long. Hops, landings, the *thwip* of the tongue,
splashes, and a level-clear fanfare are all in there too.

Every sound is synthesized on the fly with the Web Audio API, so there are no audio
files to load, and if a browser won't play sound the game just carries on quietly.

## Made for small hands

Tap-where-you-want-to-go controls, big tap targets, no fail state, and a pad layout
that's mathematically guaranteed to never leave you stranded — there is always a
glowing pad within hop range on the way forward.

## Running it

It's a single `index.html` with no dependencies and no build step. Open it in any
browser, or serve the folder with any static file server:

```
python -m http.server 8000
```

---

Made with ❤️ (and 🪰) using HTML5 canvas. No assets, no libraries — everything is
drawn and synthesized in code.
