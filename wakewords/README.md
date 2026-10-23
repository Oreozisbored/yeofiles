# Wake Words Directory 🎙️

By default, Yeo can use built-in openWakeWord models (such as `"hey_jarvis"` or `"alexa"`) or custom-trained wake word models.

### 📦 Pre-trained Custom Models in this Repository:
1. **Hey Yeo** (`wakewords/Hey_yee_o.onnx`)
   - Custom wake word trained specifically for the Yeo Discord Bot!
   - Pronunciation target: *"Hey Yee-o"*
2. **Hey Verity** (`wakewords/Hey_verity.onnx`)
   - Custom wake word for the Verity voice assistant!
   - Pronunciation target: *"Hey Verity"*

### ⚙️ Usage in `.env` or Google Colab:
Set your `WAKE_WORD` configuration to the model path:
```env
WAKE_WORD=wakewords/Hey_yee_o.onnx
```
or:
```env
WAKE_WORD=wakewords/Hey_verity.onnx
```
*(Note: Keep the companion `.onnx.data` file in the same directory as the `.onnx` model).*
