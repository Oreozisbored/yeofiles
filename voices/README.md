# Piper Voices Directory

Place Piper TTS `.onnx` and `.onnx.json` model files in this directory.

The bot automatically downloads `en_US-lessac-medium` on first run if this directory is empty.

### Adding New Piper Voices:
Download pre-trained Piper voices from the [Piper Voices repository](https://huggingface.co/rhasspy/piper-voices/tree/v1.0.0):
1. Download the `.onnx` model (e.g. `en_US-ryan-medium.onnx`).
2. Download the `.onnx.json` config (e.g. `en_US-ryan-medium.onnx.json`).
3. Place both files in this `voices/` directory.
4. In Discord, use `/voice en_US-ryan-medium` to select it!
