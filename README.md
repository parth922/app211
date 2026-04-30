# 🌟 Lumos - Smart Home Control App

A premium Flutter smart home control app inspired by Control4, built for your living room.

## Features

### Lighting Control
- **Ceiling Light** — Toggle + brightness slider
- **Hanging Pendant Lights** — Toggle + brightness
- **Floor Lamp** — On/Off toggle
- **Accent Lights** — Toggle + 6 color options (warm, red, teal, purple, white, blue)

### Climate Control
- **AC** — On/Off + temperature (16°C – 30°C) with +/- controls
- **Ceiling Fan** — On/Off + 3 speed settings (LOW / MED / HIGH)

### Entertainment
- **TV** — On/Off + volume slider (0–100)
- **Input selector** — HDMI 1, HDMI 2, YouTube, Netflix, Amazon
- **Remote controls** — Back, Home, Rewind, Play, Fast Forward

### Room Preview
- Live mini-map of the room showing active lights, TV glow, fan status, accent colors
- Real-time ambient background glow reacts to active devices

## Setup

```bash
flutter pub get
flutter run
```

## Tech
- Flutter 3.x / Dart 3
- Material 3, dark theme
- Custom painter for room visualization
- StatefulWidget with haptic feedback
- AnimatedContainer for smooth toggles

## Structure
```
lib/
  main.dart        — App entry, theme setup
  home_screen.dart — All UI + device state management
```
