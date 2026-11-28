# The Sri Lankan leopard: delivery pack

**Film:** the-sri-lankan-leopard.mp4 · 1080×1920 · 30 fps · H.264/AAC · 97.0 s · −14.0 LUFS (true peak −1.6 dBFS) · 93.9 MB
**Captions:** burned in, and in the-sri-lankan-leopard.en-GB.srt · **Cover:** the-sri-lankan-leopard-cover.jpg (end card at 1:35.5, no caption)

## Title (51 characters)
No tigers, no lions: meet Sri Lanka's only big cat

## TikTok caption
No tigers, no lions. Just one big cat 🐆 Why the Sri Lankan leopard lives nowhere else, and why most of the danger lies outside its parks.
#srilanka #leopard #wildlife #yala #learnontiktok #explained

## Facebook description
Sri Lanka has no tigers and no lions. Its only big cat is the leopard, a subspecies found nowhere else on Earth (Panthera pardus kotiya). It is one of just two island-living leopards in the world. With no bigger rival, it is the island's top predator, and Yala's Block 1 holds about one leopard for every two square kilometres, among the highest densities known.

It lives right across the island, from dry scrub to rainforest and tea estates, but fewer than 1,000 adults remain and it is listed as Vulnerable. From 2008 to 2024, at least 164 leopards were recorded killed by people. Where the cause was known, more than six in ten were caught in wire snares set for other animals, and nearly 40% of the deaths were in one hill district, Nuwara Eliya.

What helps: forest links so leopards can move between habitats, clearing snares, keeping livestock safe at night, and giving them space on safari.

Sources: IUCN Red List (Kittle & Watson, 2020); Kittle et al., Global Ecology and Conservation (2022); Animals (MDPI) Yala Block 1 study (2022); Weerakkody et al., Wildlife Letters (2026), via Mongabay (Jun 2026); Kittle, Watson & Fernando, Tropical Ecology (2017); Pocock (1939).

## SEO keywords
Sri Lankan leopard · Panthera pardus kotiya · Yala leopards · leopard density Yala Block 1 · island leopard · Sri Lanka big cat · Sri Lanka wildlife explained · leopard snares Sri Lanka · Nuwara Eliya leopard deaths · IUCN vulnerable leopard · wildlife corridors Sri Lanka · human–leopard conflict · leopard conservation · Sri Lanka safari etiquette · apex predator Sri Lanka

## Pinned comment
Sources 🐆 IUCN Red List: Vulnerable, < 1,000 adults (Kittle & Watson 2020) · One of two island leopards (Global Ecology & Conservation 2022) · Yala Block 1: ≥77 leopards, ≈0.55/km² (Animals 2022) · 164 human-caused deaths 2008–2024, 62% of known causes snares, ~40% in Nuwara Eliya (Wildlife Letters 2026; Mongabay, Jun 2026).

## Assumptions made
- **Style:** "Real-time 3D, bleached desert daylight" isn't a library style, so it was built for this film: a game-engine world rendered live in three.js (hard sun shadows, procedural materials, low-poly trees, HUD-style field-guide labels) under a white-hot noon sun. The sky is blown to cream, haze swallows the distance, the grade is desaturated with ivory highlights and lifted warm blacks. The only rich colours are the leopard's ochre coat and a signal red for danger. No reference images or palette were supplied, so the palette comes from Sri Lanka's dry zone at midday (sand, straw, granite, olive scrub).
- **Leopard and deer:** built from code primitives with a procedural rosette/spot shader. They are stylised, not photoreal.
- **Map:** coastline from Natural Earth, with no borders. The parks are drawn as simplified ellipses (labelled "simplified"). The 164 death markers illustrate the share in the Nuwara Eliya area; they are not real locations.
- **Angle:** Why (island, apex, density) → What (subspecies, size, diet, range, status) → turn (most deaths outside parks) → How (corridors, snares and livestock, safari distance). The bookend returns to the opening rock.
- **Cautious wording:** "fewer than 1,000 adults" (IUCN says < 800 mature; WWCT says about 1,000); "at least 164" (recorded deaths only); "about 56 kilos" (historic average of 11 males). The 100 kg claim was dropped.
- **Length: 97.0 s**, over the 60–90 s target but under the 100 s cap. The How section and the 2 s turn silence needed the time at a calm pace.
- **Transitions:** every scene change is a 0.8 s eased cross-dissolve with both scenes rendered under it. There are no blank frames (blackdetect: 0), and no voice line crosses a dissolve.
- **Mastering:** two-pass −14 LUFS master run by hand (ffmpeg 6.1 here). The picture was re-encoded two-pass to fit under 100 MB.

## Voice
**bm_george** (British male, Kokoro), with a speed set for each line. I tested all four British voices with the same offline recogniser (PocketSphinx; Whisper can't be downloaded here): george **78.7%**, fable 74.1%, isabella 66.2%, emma 65.7%. George was the clearest, and his calm, low documentary tone suits a wildlife story.

## Audio review
- **Pace:** 138–156 wpm per line (target 140–155; two lines sit just outside, kept for naturalness). 0.45 s between lines, 0.85 s between scenes, and **2.1 s of near-silence** (wind only) before "And most of the danger lies outside the parks".
- **Pronunciation (set as IPA, not respellings):** Sri /ʃɹiː/ Lanka; Yala /jˈɑːlə/; Panthera /pˈanθəɹə/; kotiya /kˈəʊtɪjɑː/; Nuwara Eliya /nˈʊwəɹə ˈɛlɪjə/. A phoneme-level recogniser heard SH-R-IY L-AY-N-K, Y-AA-L-AH, K-OW-JH-IY, N-UW-W-R-AA … L-IY, which matches the intended sounds.
- **Word-level check:** 78.8% of words recognised overall (the recogniser is a US-English model, so a British voice scores lower). Every line lands inside its scene and caption.
- **Music:** original score made in code at 76 bpm: nylon guitar arpeggios, pizzicato bass, harp, a kalimba "sun" motif and a soft pad in D major for the setup. It drops out for the turn, then a low drone, a frame-drum heartbeat and sparse harp in D minor carry the problem section. The theme returns fuller and resolves on D at the end. The voice sits 9.5 dB above the music, and the low end sits 7 dB under the rest of the mix.
- **Effects:** hot wind and cicadas, grass rustles for paws, soft wooden taps for markers, HUD ticks for labels, a wire twang for the snare. Dissolves get a soft air swell, never a whoosh.
- **Release check:** −14.0 LUFS integrated, true peak −1.6 dBFS, both measured on the final MP4 after AAC encoding. No clipping.

## Worth a listen
- 0:27 "Panthera pardus **kotiya**": the recogniser heard the "-tiya" close to "-chee-ya".
- 1:11 "**Nuwara Eliya**"
- 1:03 "wire snares": the US recogniser misheard it, but the phonemes are correct.

## File size
Rendered at 169.4 MB → two-pass re-encoded to 93.9 MB (7.55 Mbps video, 1080×1920, 30 fps, audio unchanged). Loudness, peak and contact sheet were re-checked on the smaller file.
