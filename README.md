# LiveKeys sounds

SoundFont (SF2) banks downloadable from the LiveKeys iPad app, converted from their original SFZ / SF2 / WAV
releases and redistributed **non-commercially**, with credit to their authors.

| Bank | Author | License | Source | Changes made for LiveKeys |
|---|---|---|---|---|
| Upright Piano KW (full) | FreePats project (Gonzalo & Roberto) | CC0 1.0 | https://freepats.zenvoid.org/Piano/acoustic-grand-piano.html | None (original SF2) |
| Upright Yamaha (VCSL) | Versilian Studios — Versilian Community Sample Library | CC0 1.0 | https://github.com/sgossner/VCSL | Mapped to SF2 from the raw WAV samples (round-robin 1 only), soft velocity layers levelled up, tails cut at 12 s with a 1 s fade |
| Upright Knight (VCSL) | Versilian Studios — VCSL, sampled by Simon Dalzell (Ivy Audio) | CC0 1.0 | https://github.com/sgossner/VCSL | Mapped to SF2 from the raw WAV samples, tails cut at 12 s with a 1 s fade |
| Splendid Grand Piano | AKAI (public domain), SFZ mapping by kinwie | Public domain | https://github.com/sfzinstruments/SplendidGrandPiano | Converted from SFZ |
| Salamander Grand Piano | Alexander Holm | CC BY 3.0 | https://github.com/sfzinstruments/SalamanderGrandPiano | 5 of the 16 velocity layers (2, 5, 8, 12, 16), no release / resonance samples, tails cut at 12 s with a 1 s fade, 16-bit |
| Grand Kawai (VCSL) | Versilian Studios — VCSL | CC0 1.0 | https://github.com/sgossner/VCSL | Mapped to SF2 from the raw WAV samples, soft velocity layers levelled up, +8 dB overall, tails cut at 12 s with a 1 s fade |
| YDP Grand Piano | Zenph Studios (OLPC sample library), SF2 by FreePats | CC BY 3.0 | https://freepats.zenvoid.org/Piano/acoustic-grand-piano.html | Preset renamed only |
| jRhodes Mark I (light, looped) — jRhodes3c | Jeff Learman | CC BY-NC-SA 4.0 | https://github.com/sfzinstruments/jlearman.jRhodes3c | Converted from SFZ |
| jRhodes Mark I (full) — jRhodes3d | Jeff Learman | CC BY-NC 4.0 | https://github.com/sfzinstruments/jlearman.jRhodes3d | Converted from SFZ |
| Yamaha CP80 | Greg Sullivan, SFZ by kinwie | CC BY 3.0 | https://github.com/sfzinstruments/GregSullivan.E-Pianos | Converted from SFZ |
| Hohner Pianet T | Greg Sullivan, SFZ by kinwie | CC BY 3.0 | https://github.com/sfzinstruments/GregSullivan.E-Pianos | Converted from SFZ |

The Wurlitzer EP200 from the same Greg Sullivan collection (CC BY 3.0) and a « bright » Upright Piano KW (FreePats,
CC0) are bundled in the app itself rather than downloaded.

The jRhodes samples may not be used commercially; contact their author for a commercial license.
Original license and readme files are in [`licenses/`](licenses). Conversions were made with the scripts of the
LiveKeys app (`scripts/samples2sfz.py`, `scripts/sfz2sf2.py`).

Files are attached to the [v1 release](../../releases/tag/v1); `catalog.json` lists them with size and SHA-256.
