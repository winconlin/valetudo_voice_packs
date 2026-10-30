# Valetudo Voice Packs

Eine Sammlung von Voice Packs für [Valetudo](https://github.com/RobinBruecker/valetudo) mit deutschen Stimmen.

## Enthaltene Packs

| Pack | Sprache | Stil | Dateien |
|------|---------|------|---------|
| **Reich-Ranicki** | Deutsch | Autoritär, literarisch, kritisch – im Stil des bekannten Literaturkritikers | 201 (WAV + OGG) |
| **Sträter** | Deutsch | Erzählerisch, warm, umgangssprachlich – im Stil des bekannten Sprechers | 201 (WAV + OGG) |

## Struktur

```
reich_ranicki/
  wav/    # WAV-Dateien (16 kHz, Mono)
  ogg/    # OGG-Dateien (Opus, 24 kbps)
strater/
  wav/    # WAV-Dateien (16 kHz, Mono)
  ogg/    # OGG-Dateien (Opus, 24 kbps)
sound_list_reich_ranicki.csv  # Texte für den Reich-Ranicki Pack
sound_list_strater.csv        # Texte für den Sträter Pack
```

## Installation

1. Den gewünschten Ordner (z. B. `reich_ranicki/ogg/`) nach `/mnt/user/shared/valetudo/voices/` auf deinem Valetudo-Server kopieren.
2. In Valetudo den Voice Pack auswählen.

## Hinweise

- Alle Audiodateien sind auf -1 dBFS normalisiert.
- Die WAV-Dateien sind für maximale Qualität, die OGG-Dateien für kleineren Speicherplatz.
- Die Texte sind in den zugehörigen CSV-Dateien dokumentiert.
