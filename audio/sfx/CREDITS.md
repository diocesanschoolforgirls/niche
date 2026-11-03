# Niche fun-test slice: battle sound effects, credits and licences

Prepared by Raj, 2026-10-29. START-HERE ruling 10: sound must be cleared for any use with no attribution needed. Every source page below was opened and its "License(s)" field read: **CC0 1.0 (public domain dedication) only**, no second licence listed. Licence deed: https://creativecommons.org/publicdomain/zero/1.0/ . Credit is not required; recorded so we know where each came from. Originals are kept in `%USERPROFILE%\aardvark-renders\niche-sfx-raw\` (outside OneDrive). Finals are trimmed, sometimes pitch-shifted or filtered, normalised, mono MP3.

**Stand-ins:** no CC0 recordings exist (that I could find) of NZ species, seal, orca or a shell/claw. Files marked STAND-IN are the nearest real animal or object, altered in pitch. None has been auditioned by ear by me; open `preview.html` in this folder to hear all of them and judge.

| File | What it is | Source (OpenGameArt page) | Author | Licence |
|---|---|---|---|---|
| gull-cry.mp3 | gull, long cry | https://opengameart.org/content/solo-seagull-sound-effects ("Seagull Ambient 1") | Rango Mango | CC0 |
| gull-cry-2.mp3, gull-cry-3.mp3 | gull cries, shorter | same ("Ambient 2", "Ambient 5") | Rango Mango | CC0 |
| gull-hit.mp3 | gull startled / hit | same ("Seaguall Hit 1") | Rango Mango | CC0 |
| gull-hurt.mp3 | gull, longer pained cry | same ("Seagull Death 4") | Rango Mango | CC0 |
| korora-call.mp3 | little penguin, two short calls. STAND-IN (generic penguin) | https://opengameart.org/content/penguin-sounds | AntumDeluge | CC0 |
| shag-croak.mp3 | kāruhiruhi/shag. STAND-IN: crow caw slowed and low-passed | https://opengameart.org/content/crow-caw | zeroisnotnull | CC0 |
| torea-pipe.mp3 | tōrea/oystercatcher. STAND-IN: two shrill bird peeps | https://opengameart.org/content/bird-chirping-sounds | syncopika | CC0 |
| kotare-rattle.mp3 | kōtare/kingfisher. STAND-IN: one chirp repeated as a rattle | same | syncopika | CC0 |
| kahu-screech.mp3 | kāhu/harrier. STAND-IN: raptor-style screech | https://opengameart.org/content/vulture-imitation | AntumDeluge | CC0 |
| heron-squawk.mp3 | heron. STAND-IN: peacock scream lowered and low-passed | https://opengameart.org/content/peacock-scream | popthebubbles4 | CC0 |
| splash-small.mp3, splash-medium.mp3 | splashes | https://opengameart.org/content/6-short-water-splashes | ezwa | CC0 |
| splash-big.mp3 | big water splash | https://opengameart.org/content/ocean-splash | Thimras | CC0 |
| water-churn.mp3 | bubbling churn, 4 s | https://opengameart.org/content/bubble-sound-effects ("bubbles-loop1") | BMacZero | CC0 |
| bubbles.mp3, bubble-pop.mp3 | bubbles, single pop | same ("bubbles-loop2", "bubbles-single3") | BMacZero | CC0 |
| seal-bark.mp3, seal-bark-2.mp3 | kekeno bark. STAND-IN: dog bark pitched down and low-passed | https://opengameart.org/content/dog-sounds | pauliuw | CC0 |
| seal-growl.mp3 | kekeno growl. STAND-IN: bear growl | https://opengameart.org/content/bear-growls | AntumDeluge | CC0 |
| shell-clack.mp3, shell-clack-2.mp3 | hard click for shell on shell. STAND-IN: UI-style clicks | https://opengameart.org/content/87-clickety-clips | OwlishMedia | CC0 |
| claw-snap.mp3, claw-snap-2.mp3 | sharp snap. STAND-IN: short whip/thwack | https://opengameart.org/content/thwack-sounds | AntumDeluge (Jordan Irwin) | CC0 |
| shell-crunch.mp3 | crunch / break | https://opengameart.org/content/5-break-crunch-impacts | Independent.nu (uploaded by qubodup) | CC0 |
| shell-crack.mp3, thud-heavy.mp3 | low crack; heavy thud | https://opengameart.org/content/deep-bone-crackbreak-sfx | Zane Little Music | CC0 |
| crunch-bite.mp3 | quick crunchy bite | https://opengameart.org/content/crunchy-bite | fvcalderan | CC0 |
| thud.mp3 | body thud / impact | https://opengameart.org/content/37-hitspunches | Independent.nu (uploaded by qubodup) | CC0 |
| sand-scuffle.mp3 | scuff on sand/ground | https://opengameart.org/content/fantozzis-footsteps-grasssand-stone | Fantozzi (uploaded by qubodup) | CC0 |
| wing-flap.mp3 | two wing flaps | https://opengameart.org/content/large-wings-flap | AntumDeluge | CC0 |
| rain-loop.mp3 | 8.5 s seamless rain loop (1 s crossfade) | https://opengameart.org/content/amb-rain-loop-1 | Kresiek The Furry | CC0 |
| thunder.mp3 | 4 s thunder, with rain underneath | https://opengameart.org/content/rain-long-thunder | WuxiaScrub | CC0 |

## Not found: use the browser to synthesise

- **orca blow (Maki)**: no CC0 recording found. Stand-in: a 0.6 s burst of band-passed white noise (centre about 1.2 kHz) with a fast attack and long fall, then a quick low-passed puff. Web Audio `AudioBufferSource` of noise into a `BiquadFilter`.
- **orca call (Maki)**: no CC0 recording found. Stand-in: two sine glides with a light amplitude wobble, e.g. 1.8 kHz down to 900 Hz in 0.5 s, then 1.1 kHz up to 2.2 kHz, through a short reverb.
- **real kororā, kāruhiruhi, tōrea, kāhu, kōtare, heron, kekeno recordings**: the genuine species are only on Xeno-canto and NZ Birds Online under CC-BY / CC-BY-NC, which ruling 10 excludes. The stand-ins above are what is available.

## Considered and left out

- https://opengameart.org/content/water-splash-and-sand-footsteps (CC0, but the author asks games to reference their itch.io page).
- https://opengameart.org/content/40-cc0-water-splash-slime-sfx (CC0; only the combined preview was fetched and I could not tell splash from slime without listening).
