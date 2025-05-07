# Unreal MIDI Visualizer 🎹🥁

This Unreal Engine project allows you to **visualize MIDI input** and see which notes are actively playing in real time. The project supports basic instruments such as **piano (simple & grand)** and **drums**, all rendered using blueprints and MetaSounds.

![GrandPianoMap](https://github.com/user-attachments/assets/7aa4f82d-997c-4d86-a540-767e3821cec2)
![DrumsMIDI](https://github.com/user-attachments/assets/f9172414-9bb3-4687-b169-4f61dcf5c65d)

## 📂 How to Use

### 🎵 Input Your Own MIDI
1. Navigate to: Content/midi
2. Open the `MetaSoundSource_Midi` asset.
3. Assign your MIDI file to the **MIDI Player**.

### 🎹 Visual Instruments
You can find the following instruments under: Content/Blueprints
- `BP_SimplePiano`
- `BP_GrandPiano`
- `BP_Drums`

Open the corresponding Blueprint to view or modify the MIDI note mappings.

### 🥁 Drum Sounds Setup
To hear drum sounds:
1. Go to: Content/midi/MetaSoundSource_Midi
2. Create or assign a **Synthesizer Patch** using **Fusion Sampler**.

---

## 💡 Customization

- You can **edit the note-to-key mappings** by modifying the logic inside each instrument’s Blueprint.
- The MIDI player is built with **MetaSounds**, allowing flexible audio manipulation and visualization.

---
