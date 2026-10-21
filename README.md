# YeoFiles 📦🎧

Public CDN & Asset distribution repository for the **Yeo Discord Voice Bot**.

This repository hosts non-private assets (soundboard audio, persona acknowledgement chimes, custom wake word models, and TTS resources) so that environments like Google Colab, servers, and Docker containers can easily fetch them via public URLs without authentication.

## 📂 Repository Contents

### 1. `sounds/`
- `wake_chime.wav` - Universal wake word confirmation chime.
- `airhorn.wav` - Classic soundboard airhorn effect.
- `quack.wav` - Duck quack soundboard effect.
- `drumroll.wav` - Snaredrum roll effect.
- `tada.wav` - Fanfare chord soundboard effect.

### 2. `sounds/acknowledgements/`
Pre-rendered static audio acknowledgements per persona:
- `ack_default.wav` - Clean friendly double chime (Default persona)
- `ack_rude.wav` - Annoyed low scoff (Rude persona)
- `ack_uwu.wav` - Cute sparkle chime (UwU persona)
- `ack_pirate.wav` - Resonant ship bell (Pirate persona)
- `ack_gangster.wav` - Deep 808 sub bass drop (Gangster persona)
- `ack_shakespeare.wav` - Heraldic fanfare (Shakespeare persona)
- `ack_nerd.wav` - 8-bit retro computer beep (Nerd persona)

### 3. `wakewords/`
- Directory for custom openWakeWord `.onnx` models (e.g. `hey_yeo.onnx`).

### 4. `voices/`
- Documentation and storage for Piper TTS `.onnx` models.

---

## 🌐 Raw CDN Usage
Any file in this repository can be fetched directly via raw GitHub URLs:
```bash
https://raw.githubusercontent.com/Oreozisbored/yeofiles/main/sounds/wake_chime.wav
https://raw.githubusercontent.com/Oreozisbored/yeofiles/main/sounds/acknowledgements/ack_default.wav
```
