# High Frequency Noise Detector

Real-time high-frequency noise detector that runs entirely in your phone's browser. Use it to hunt down the source of annoying high-pitched sounds (coil whine, squeals, electrical noise, etc.).

## Live App

**Enable GitHub Pages** (takes 30 seconds):
1. Go to repo Settings → Pages
2. Source: Deploy from a branch
3. Branch: main / root → Save
4. Wait ~1 minute, then open: https://esgorotg666.github.io/high-frequency-noise-detector/

## How to Use
1. Open the live URL on your phone (must be HTTPS — GitHub Pages handles this).
2. Tap **Start Listening** and allow microphone access.
3. Walk around while listening. When the full-screen red alert appears + phone vibrates, you're close to the source.
4. Adjust the frequency threshold (default 10 kHz) and sensitivity as needed.

## Tips for Finding the Source
- Start with sensitivity around 40. Lower the number if it's too quiet to trigger.
- High-pitched noise often comes from power supplies, chargers, LED drivers, or failing electronics.
- Phone mics work best for audible high frequencies (roughly 5–18 kHz). True ultrasonic (>20 kHz) usually requires special hardware.

Works offline once loaded. No backend, no accounts, no data leaves your phone.