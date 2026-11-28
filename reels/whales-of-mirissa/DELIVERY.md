# Whales of Mirissa · delivery pack

**Film:** whales-of-mirissa.mp4 · smooth-shaded 3D graded as a silent-era orthochromatic print, in the sea palette · 1080×1920 · 30 fps · H.264 two-pass 7.3 Mb/s / AAC 192k · 98.9 s · 92.6 MB · −14.0 LUFS (true peak −1.6 dBFS)
**Captions:** burned in (one line, y≈1600, light text with a navy halo) and in whales-of-mirissa.en-GB.srt · **Cover:** whales-of-mirissa-cover.jpg (end card with the diving fluke, 1:34.5)

## Title (43 characters)
Why the world's biggest animal swims here

## TikTok caption
Blue whales feed a short boat ride off Mirissa 🐋 Why they're here, why some stay all year, and how moving one shipping lane could save them.
#bluewhale #mirissa #srilanka #whalewatching #learnontiktok #explained

## Facebook description
Off Mirissa, on Sri Lanka's south coast, the seabed drops away fast: the edge of the continental shelf lies only about 7–8 km out. Along that steep slope, deep water wells up and carries nutrients to the surface, feeding plankton and the tiny shrimp-like animals that the largest animal ever to have lived comes here to eat.

These are northern Indian Ocean blue whales. Unlike most blue whales, they don't migrate to cold polar seas, and some stay around Sri Lanka all year. From November to April, when the sea is calm, boats leave Mirissa harbour to see them, along with sperm whales and dolphins.

But one of the world's busiest shipping lanes runs through the same waters, and ship strikes are the biggest threat these whales face. Scientists estimate that moving the lane 15 nautical miles south could cut the risk by about 95%; in 2022 the shipping line MSC moved its route. Watching them well matters too: by law, boats keep at least 100 m away, and swimming with whales needs a special permit.

Sources: de Vos et al., J. Cetacean Res. Manage. (IWC); de Vos et al., J. Marine Biology (2016); IFAW ship-strike surveys 2014–15 and press release (8 Sep 2022); Mongabay (Oct 2022); Sri Lanka Sea Mammals Regulations No. 1 of 2012 (amended 2019).

## SEO keywords
Mirissa whale watching · blue whales Sri Lanka · Mirissa blue whale · northern Indian Ocean blue whale · Sri Lanka whale season · whale watching season Mirissa November to April · continental shelf Sri Lanka · upwelling Sri Lanka · blue whale ship strikes · Sri Lanka shipping lane whales · MSC reroute blue whales · whale watching rules Sri Lanka · 100 metre rule whales · sperm whales Sri Lanka · largest animal ever

## Pinned comment
Sources 🐋 Shelf edge ~7–8 km south of Mirissa (de Vos et al., IWC J. Cetacean Res. Manage.) · Non-migratory, some resident all year; ship strike the top threat (de Vos et al., J. Marine Biology 2016) · 15 nmi lane shift ≈95% lower risk (IFAW surveys 2014–15) · MSC rerouted 2022 (IFAW, 8 Sep 2022) · 100 m distance, no swimming without permit (Sea Mammals Regulations No. 1 of 2012, amended 2019).

## Assumptions made
- **Style:** "Smooth-shaded 3D graded as a silent-era orthochromatic print" isn't a library style, so it was built for this film: smooth-shaded three.js models (whale, dolphins, boat, ship, seabed cutaway, chart) through a print pass with orthochromatic response (blue water prints pale, dark backs print dark), flicker, gate weave, halation, grain, dust and soft vignette. No 4:3 gate or curtains: the frame is full-bleed as the project requires.
- **Palette (changed mid-production at your request):** first graded in the Bastet photo's crimson, black and gold; regraded in your sea palette — #00669A, #0799BE, #21A6B1, #8EC2B9, sand #DFDDD7 — with a deep navy ink for the darkest tones. Titles and labels are sand-white with a navy shadow; captions light with a navy halo.
- **Whale colour (your note):** lightened to a mottled blue-grey with a pale belly, so it reads against the dark ship hull and the deep water.
- **Transitions:** every scene change is a 0.8 s eased cross-dissolve; both scenes are rendered under it, so no blank frames (blackdetect: 0). Dissolves get a soft swell, never a whoosh.
- **Length: 98.9 s**, over the 60–90 s target but under the 100 s maximum: the Why (shelf, upwelling), What (who, when) and How (the shipping-lane fix, the 100 m rule) needed it at a calm pace.
- **Chart:** the coastline and lanes are schematic, drawn in code (not survey data); no borders. The shelf cutaway is marked "not to scale".
- **Cautious wording:** "some stay all year" (not all); "about 95%" labelled a scientists' estimate; the reported decline in sightings left out as contested (see FACTS.md).
- **File size:** the master render was 823 MB (CRF 14, picture only), so the picture was re-encoded two-pass to 92.6 MB at 1080×1920, 30 fps; loudness and peak measured on that final file.
- **Mastering:** two-pass −14 LUFS master run by hand (ffmpeg 6.1 here).

## Voice
bm_george (British male, Kokoro), speed set per line. Same offline recogniser (PocketSphinx; Whisper's model host is blocked here) on the same script:

| Voice | Word accuracy |
|---|---|
| **bm_george** | **0.816** (chosen; 0.834 after pacing) |
| bm_fable | 0.751 |
| bf_emma | 0.623 |
| bf_isabella | 0.598 |

George was clearest, and his warm, unhurried documentary tone suits the topic.

## Audio review
- **Pace:** 141–155 wpm per line (target 140–155).
- **Turning point:** 2.4 s of near-silence between "…sperm whales and dolphins." and "But the same waters…", with the light dimming.
- **Pronunciation (exact phonemes, not respellings):** Sri Lanka /ʃɹiː lˈaŋkə/ (shree LANG-kuh); Sri Lankan /ʃɹiː lˈaŋkən/; Mirissa /mˈɪɹɪsə/; MSC /ˈɛm ˈɛs sˈiː/ (letters); fifteen /fˌɪftˈiːn/ (stress on -teen, so it isn't heard as "fifty"). Phoneme-level recognition heard SH-R-IY L-AY-NG-K and M-IH-R-S-AH as intended. Every line reviewed for "a" read as "ay", -ed endings and run-together words; no intrusive "r" in "Sri Lanka all year".
- **Sync:** every line starts ≥0.3 s after its scene's dissolve and ends ≥0.45 s before the next; captions follow the voice in one-line chunks without flicker between chunks.
- **Mix:** voice 9.5 dB above music and ambience; music high-passed at 75 Hz; 20–120 Hz sits 7.6 dB under 120 Hz–8 kHz.
- **Release check:** −14.0 LUFS integrated, true peak −1.6 dBFS, LRA 3.8 LU, all on the final MP4 after AAC; no clipping.

## Worth a listen
- 0:00 "Off one **Sri Lankan** beach"
- 0:10 "Off **Mirissa**" — set with first-syllable stress (MI-ri-ssa); tell me if you'd rather mi-RIS-sa.
- 1:05 "**fifteen** nautical miles" — the US-English checker hears "fifty"; the phonemes say -teen.
- 1:16 "the shipping line **M S C**"
