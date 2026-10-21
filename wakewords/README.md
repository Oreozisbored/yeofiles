# Wake Words Directory

By default, Yeo uses built-in openWakeWord models (such as `"hey_jarvis"` or `"alexa"`).

### Custom Wake Word Models:
If you train a custom wake word model with openWakeWord (e.g. `hey_yeo`):
1. Place the trained `.onnx` file here (e.g. `wakewords/hey_yeo.onnx`).
2. In your `.env` file, set:
   ```env
   WAKE_WORD=wakewords/hey_yeo.onnx
   ```
3. Restart the bot. Yeo will now trigger on your custom wake word!
