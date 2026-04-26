# Pre-installation Information

## AI Features (Optional)

Suivi Ruches includes AI-powered features:
- **Dr. Abeille**: Beekeeping AI assistant for advice
- **Flora & Fauna**: Identify plants and insects from descriptions or photos

These features require an **Anthropic API key**. You can:

1. **Get a free API key** at [console.anthropic.com](https://console.anthropic.com/)
2. **Skip AI features** by leaving the API key field empty during installation

The API key will be stored securely in the app's `.env` file (only readable by the app user).

## Storage

The app uses **browser localStorage** for data persistence:
- Hive data, interventions, and photos are stored locally in your browser
- Data is **per-device**: switching browsers or devices will require re-entering data
- This is by design to maximize privacy (no server-side data storage)

If you need cross-device sync, consider using a browser sync feature or exporting/importing your data.

## Browser Compatibility

For the best experience (especially voice dictation):
- ✅ Chrome / Chromium (recommended)
- ✅ Microsoft Edge
- ✅ Safari 14.1+
- ⚠️ Firefox (limited speech-to-text support)

## Microphone Permission

The voice dictation feature requires microphone access. Your browser will ask for permission the first time you use the dictation button (🎤).
