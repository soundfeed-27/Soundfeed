# SOUNDFEED

Immersion sound engine. A single-page generative instrument that runs in the browser: cathedral choir, space pad, monastic chant, organ drone, sub core, and optional binaural / bell layers, through a 4-way crossover and a safety limiter.

Original sound engine and music © 2026 ALEN DIVULJSKI. All rights reserved.

## Run it

Open `index.html` in a current browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. Press **Start** (browsers require a tap before audio can play). Begin with the master at 30 and raise it slowly.

## Safety

- The meter is digital peak (dBFS), not how loud the room is.
- A compressor-limiter and a hard ceiling keep the output under about −1 dBFS.
- **Emergency Cut** silences immediately and closes the audio session.
- Take a break every 30 minutes. The status line reminds you.
- Phone speakers cannot play the sub band (below 60 Hz). Use headphones or a subwoofer.
- The binaural layer is for headphones only.

## Scenes

| Mood | Character |
| --- | --- |
| Descent | Dark cathedral choir |
| Abyss | Deep industrial drone |
| Space | Slow synth pad |
| Tenebrae | Monastic chant, 285 Hz root |
| The Protectors | Guardian theme, brighter pad |

Slow-down stretches chord motion, chant phrasing, bells, and LFOs together (1× to 8×). Tuning can sit at A = 440 Hz or a 285 Hz root.
