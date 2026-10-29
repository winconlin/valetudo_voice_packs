# Valetudo Voice Packs

Dreame Robot Vacuum voice packs for [Valetudo](https://github.com/Valetudo/).

## Packs

| Pack | Voice | Style | Files |
|------|-------|-------|-------|
| [reich_ranicki](reich_ranicki/) | Marcel Reich-Ranicki | Literarisch, autoritär, tief | 201 |
| [strater](strater/) | Torsten Sträter | Freundlich, warm, Geschichtenerzähler | 201 |
| _(bayerisch – original)_ | — | Bairisch (Hochdeutsch-Stimme) | 155 |

## Structure

Each pack contains:
- `wav/` — 22 kHz mono WAV files (IDs 0–200), loudness-normalized (I=-14 LUFS, TP=-1 dBFS)
- `ogg/` — Opus 32 kbps OGG files (same IDs)

## Installation

1. Copy the pack folder to your Valetudo robot:
   ```bash
   scp -r reich_ranicki/ pi@<robot-ip>:/opt/voicepacks/reich_ranicki/
   ```
2. In Valetudo Settings → Voice, select the pack by name.

## Texts

The Hochdeutsch text list is in `sound_list_hochdeutsch.csv`. The original Bavarian list is in `sound_list_bayrisch.csv`.

## Generation

Packs were generated with [VoiceStudio](https://github.com/) TTS (profiles: `f937ec11` for Reich-Ranicki, `558b4913` for Sträter), normalized with ffmpeg `loudnorm=I=-14:TP=-1:LRA=11`.
