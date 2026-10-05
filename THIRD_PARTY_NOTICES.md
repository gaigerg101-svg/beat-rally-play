# THIRD_PARTY_NOTICES.md

Add a row the moment an asset or library enters the repo. Save a copy of each source page (print to PDF) in `assets-src/licenses/`. The in-game Credits screen is generated from this file and `src/game.ts` credits().

## Music

No music files ship with this build. All four songs are procedural and original (synthesized at load time from data in `src/audio/proceduralTracks.ts`):

| Title | Author | License | BPM | Key |
| --- | --- | --- | --- | --- |
| Pulse Garden | Beat Rally (procedural) | Original | 104 | A minor |
| Night Drift | Beat Rally (procedural) | Original | 112 | D minor |
| Sunny Rally | Beat Rally (procedural) | Original | 120 | C major |
| Volt Run | Beat Rally (procedural) | Original | 126 | F minor |

Candidates researched but NOT downloaded or used (no `assets-src/` folder was supplied): Wednesday Night (Funk Fusion) by Zane Little, Funky Disco Beats by Fupi, Funked Up by Joth, Space City by MintoDog (all CC0 on OpenGameArt; verify before any future use).

## Music (wave 2)

Bundled songs in `public/music/` (`<id>.opus`, `<id>.m4a`, `<id>.beatmap.json`), listed in `src/audio/songCatalog.ts`. Each licence was read on the track's own page on the date shown; a copy of the page text, the credit line and the edits is in `assets-src/licenses/<id>.txt`. Show the credit line on the Now Playing card each time the song starts and in the credits. CC BY forbids DRM that restricts the files, so ship the audio as plain files. Lyrics (4 Josh Woodward songs) come from the song pages, which carry the CC BY 4.0 statement; timing is ours (`assets-src/lyrics/`).

| Title | Artist | Source page | License | Credit line | Edits | Date checked |
| --- | --- | --- | --- | --- | --- | --- |
| Crazy Glue | Josh Woodward | https://www.joshwoodward.com/song/CrazyGlue | CC BY 4.0 | Music - "Crazy Glue" by Josh Woodward. Free download: https://www.joshwoodward.com/ Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Already There | Josh Woodward | https://www.joshwoodward.com/song/AlreadyThere | CC BY 4.0 | Music - "Already There" by Josh Woodward. Free download: https://www.joshwoodward.com/ Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Afterglow | Josh Woodward | https://www.joshwoodward.com/song/Afterglow | CC BY 4.0 | Music - "Afterglow" by Josh Woodward. Free download: https://www.joshwoodward.com/ Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Let It In | Josh Woodward | https://www.joshwoodward.com/song/LetItIn | CC BY 4.0 | Music - "Let It In" by Josh Woodward. Free download: https://www.joshwoodward.com/ Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Turning Into Normal (What Once Felt Strange) | SackJo22 | https://ccmixter.org/files/SackJo22/43036 | CC BY 3.0 | Music "Turning Into Normal (What Once Felt Strange)" by SackJo22 featuring Analog by Nature and Haskel (HE31). Available at ccMixter.org https://ccmixter.org/files/SackJo22/43036 Under CC BY license http://creativecommons.org/licenses/by/3.0/. Edited for Beat Rally. | trimmed to 223.7 s (ends on a downbeat near 3:45, original 5:56) with a 6 s fade out; loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Let's Sing | SackJo22 | https://ccmixter.org/files/SackJo22/38362 | CC BY 3.0 | Music "Let's Sing (ft. George Ellinas with Snowflake)" by SackJo22 featuring George Ellinas and Snowflake. Available at ccMixter.org https://ccmixter.org/files/SackJo22/38362 Under CC BY license http://creativecommons.org/licenses/by/3.0/. Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Flyer | Madam Snowflake | https://ccmixter.org/files/snowflake/35396 | CC BY 3.0 | Music "Flyer" by Madam Snowflake featuring Alex Beroza. Available at ccMixter.org https://ccmixter.org/files/snowflake/35396 Under CC BY license http://creativecommons.org/licenses/by/3.0/. Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Pixel Peeker Polka - faster | Kevin MacLeod | https://kevinmacleod.bandcamp.com/track/pixel-peeker-polka-faster (audio from incompetech.com) | CC BY 4.0 | "Pixel Peeker Polka - faster" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 http://creativecommons.org/licenses/by/4.0/ Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| The Stars and Stripes Forever | United States Marine Band (John Philip Sousa) | https://commons.wikimedia.org/wiki/File:USMC_stars_stripes_forever.ogg | Public domain (U.S. federal government work; may differ outside the U.S.) | "The Stars and Stripes Forever" by John Philip Sousa, performed by the United States Marine Band. Public domain (work of the U.S. federal government), via Wikimedia Commons. Use does not imply endorsement. Edited for Beat Rally. | loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Back In The 80s | HoliznaCC0 | https://freemusicarchive.org/music/holiznacc0/power-pop/back-in-the-80s/ | CC0 1.0 | "Back In The 80s" by HoliznaCC0 (freemusicarchive.org), CC0 1.0. Edited for Beat Rally. | trimmed to 216.0 s (ends at the downbeat of bar 108) with a 6 s fade out; loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Everything is love | Komiku | https://freemusicarchive.org/music/Komiku/Helice_Awesome_Dance_Adventure_/everything-is-love/ | CC0 1.0 | "Everything is love" by Komiku (freemusicarchive.org), CC0 1.0. Edited for Beat Rally. | trimmed to 215.7 s (ends at the downbeat of bar 80) with a 6 s fade out; loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Vengeance Electro | Of Far Different Nature | https://opengameart.org/content/vengeance-electro | CC0 1.0 | "Vengeance Electro" by Of Far Different Nature (fardifferent.carrd.co), CC0 1.0, via OpenGameArt. Edited for Beat Rally. | trimmed to 210.0 s (ends at the downbeat of bar 112) with a 6 s fade out; loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| The Entertainer | Scott Joplin | https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=263 | Public domain | "The Entertainer" by Scott Joplin (1902), public domain. Score: The Mutopia Project (public domain). Synthesized for Beat Rally. | our own render of the Mutopia MIDI (tools/songs/synth_rag.py, 84 BPM constant); loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |
| Maple Leaf Rag | Scott Joplin | https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=23 | Public domain | "Maple Leaf Rag" by Scott Joplin (1899), public domain. Score: The Mutopia Project (public domain). Synthesized for Beat Rally. | our own render of the Mutopia MIDI (tools/songs/synth_rag.py, 100 BPM constant); loudness normalized to -16 LUFS; Opus and AAC encode | 2026-10-05 |

Researched and not shipped: "Hyper Ultra-Racing" by cynicmusic (CC0, but the file is only 1:20 long); the Kevin MacLeod recording of Maple Leaf Rag (CC BY 4.0, replaced by our own render); ccMixter lyrics (the ccMixter site text is CC BY-NC 4.0, so no ccMixter page text ships).

Build-time tools (not shipped, run from `tools/.venv`): librosa (ISC) for beat maps, stable-ts (MIT) with OpenAI Whisper small.en (MIT code and weights) for lyric timing, numpy and scipy (BSD-3-Clause), soundfile (BSD-3-Clause), mido (MIT), ffmpeg for decoding and encoding.

## Sound effects

No sample files ship. Every sound effect and note instrument is synthesized at startup (`src/audio/synth.ts`, `src/audio/synthVoices.ts`). The michorvath ping pong hit and the Kenney packs were not used.

## Visual assets

None. Table, paddles, ball, net, opponent characters, floors, skies and props are procedural (geometry, shaders, canvas textures). No HDRI, no texture downloads, no models. Environment lighting uses three.js RoomEnvironment (part of the three package, MIT).

## Fonts

No font files are bundled; the UI uses the local system font stack.

## Fonts (wave 2)

Bundled in `public/fonts/` as woff2 with their licence files beside them. Both fonts declare no Reserved Font Name.

| File | Font | Source (commit) | License | Change |
| --- | --- | --- | --- | --- |
| Archivo-Variable.woff2 | Archivo (wdth 62 to 125, wght 100 to 900), Copyright 2020 The Archivo Project Authors | github.com/google/fonts ofl/archivo/Archivo[wdth,wght].ttf (9710da1e), upstream github.com/Omnibus-Type/Archivo | SIL OFL 1.1, `public/fonts/Archivo-OFL.txt` | Subset to Latin, Latin Extended and punctuation, converted to woff2 with fontTools |
| Archivo-Italic-Variable.woff2 | Archivo Italic (same axes and authors) | github.com/google/fonts ofl/archivo/Archivo-Italic[wdth,wght].ttf (9710da1e) | SIL OFL 1.1, `public/fonts/Archivo-OFL.txt` | Subset and converted as above |
| JetBrainsMono-Variable.woff2 | JetBrains Mono (wght 100 to 800), Copyright 2020 The JetBrains Mono Project Authors | github.com/JetBrains/JetBrainsMono fonts/webfonts/JetBrainsMono[wght].woff2 (19371302) | SIL OFL 1.1, `public/fonts/JetBrainsMono-OFL.txt` | None (official woff2, renamed) |

## Libraries (npm, exact versions in package.json)

| Package | Version | License | Use |
| --- | --- | --- | --- |
| three | 0.186.1 | MIT | WebGL renderer; examples/jsm Reflector, RoundedBoxGeometry, RoomEnvironment imported from the package |
| postprocessing | 6.39.5 | Zlib | Bloom, tone mapping, chromatic aberration, vignette, SMAA |
| vite | 8.3.2 | MIT | Dev server and build (dev only) |
| typescript | 5.9.3 | Apache-2.0 | Type checking (dev only) |
| vitest | 5.0.3 | MIT | Unit tests (dev only) |
| @playwright/test | 1.63.0 | Apache-2.0 | End to end tests (dev only) |
| node-web-audio-api | 2.2.0 | BSD-3-Clause | Offline audio renders in unit tests (dev only) |

## Reference repos (algorithm references; no files copied)

Every item below was re-implemented in our own TypeScript or GLSL. No source file was copied. Pinned SHAs and licenses are in docs/REFERENCE-REPOS.md.

| Repo | SHA | License | File(s) read | Copied or algorithm only | Used for |
| --- | --- | --- | --- | --- | --- |
| hec-ovi/hypersurf | 0f4a623f | MIT | src/audio/clock.js, tempo.js | Algorithm only | SongClock from getOutputTimestamp with smoothing and snap (src/audio/clock.ts); BPM guess by onset autocorrelation (src/game.ts guessBpm) |
| tanuu5/bunbetsu-beat | 67cbea24 | MIT | js/audio/conductor.js, js/input.js | Algorithm only | Event timestamp to song time, pause with suspend and rewind, lookahead scheduling (src/audio/clock.ts, scheduler.ts, src/game.ts) |
| cwilso/metronome | 28a6e49d | MIT | js/metronome.js, metronomeworker.js | Algorithm only | Worker timer lookahead scheduler (src/audio/scheduler.ts) |
| cwtickle/danoniplus | 500f7942 | MIT | js/lib/dataLoader.js | Algorithm only | AudioContext warm-up (src/audio/engine.ts unlock) |
| pmndrs/maath | 56e1c4d3 | MIT | src/time spring files | Algorithm only | Critically damped springs (src/render/opponent.ts) |
| mrdoob/three.js | 3d3a92e4 | MIT | examples/jsm/objects/Reflector.js | Imported from the npm package, custom shader ours | Table planar reflection (src/render/table.ts) |
| pmndrs/drei | bf6f4add | MIT | src/materials/MeshReflectorMaterial.tsx, src/core/Sparkles.tsx | Algorithm only | Reflection blur and Fresnel mix (src/render/table.ts); particle drift (src/render/backdrops) |
| DontBullyMeIllCode/react-three-vaporwave | cbbe36a1 | MIT | src/shaders/track.ts, sun.ts, mountains.ts, sky.ts, water.ts | Algorithm only | Grid lines, banded sun, ridged mountains, sky glow, summed-wave water (src/render/backdrops) |
| VictorZakharov/beautiful-water | 830c7f3e | MIT | src/core/adaptive-quality.js | Algorithm only | Resolution governor (src/render/renderer.ts) |
| CBossman/blockyard | 73a88f63 | MIT | src/platform/ui/padnav.ts, keys | Algorithm only | Spatial D-pad menu navigation and rebinding with swaps (src/ui/padnav.ts, settings screen) |
| majidmanzarpour/threejs-game-skills | 8286774b | MIT | playwright.config.ts | Structure followed | Playwright config (playwright.config.ts) |
| David Hoskins, Hash without Sine (shadertoy 4djSRW) | n/a | MIT | hash12, hash13 | Algorithm only | GLSL hashes (src/render/backdrops/glsl.ts) |

READ ONLY repos (ideas only, nothing copied): iwolski99/ThreeJS-Game-Template (no license file), DuDoo97/online-pingpang, oplosy/table-tennis.

## Do not use

- JJDG "Table tennis sounds" (CC BY-NC 3.0).
- Essentia.js and keyandbpm (AGPL-3.0).
- Any repo code without a permissive license (DuDoo97/online-pingpang, ibra-kdbra/PingPong-3D, blinky1994/spin-table-tennis, dryanguasr/TableTennis).

## AI-generated content log (for Steam disclosure)

| Item | Tool | Plan or license | Date | Shipped to players |
| --- | --- | --- | --- | --- |
| All source code (TypeScript, GLSL, CSS, HTML) | Claude (Anthropic) via Claude Code | User's subscription | 2026-10-04 | Yes |
| Procedural music data (chords, patterns, melodies) and synth voice design | Claude (Anthropic) via Claude Code | User's subscription | 2026-10-04 | Yes (rendered at runtime) |
| Sound effect synthesis recipes | Claude (Anthropic) via Claude Code | User's subscription | 2026-10-04 | Yes (rendered at runtime) |
| UI copy, opponent names and personality lines | Claude (Anthropic) via Claude Code | User's subscription | 2026-10-04 | Yes |
| No AI-generated images, audio files or 3D models | n/a | n/a | n/a | n/a |
