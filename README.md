

# Pop Music Infilling Plugin for Ableton Live

`infilling.amxd` is a Max for Live plugin designed for pop music infilling within Ableton Live. It requires a backend server to function. You can use the following Colab notebook to set up the server (preferably with GPU support):

👉 [Colab Notebook – Server Setup](https://colab.research.google.com/drive/17dKOKgoCpq5lA6JIPNLu7mnFWJpT1R1W)

You can download this repo or download the plugin directly as a ZIP file:  
📦 [Download ZIP](https://drive.google.com/file/d/1XvmT14jS9N1O6VsqsYMoqAerWmdhJ8jJ/view)

---

## 🎹 Basic Functionality

This plugin supports infilling for up to **3 tracks** in a pop song project. Please follow these setup guidelines:

- MIDI track names in Ableton Live should follow the format: `track_0`, `track_1`, ..., `track_n`.
- Each track should contain **only one MIDI clip**.
- The plugin supports up to **16 bars** per session. To go beyond 16 bars, set the **starting bar** to a number higher than 1.

---

## 🎛️ Control Parameters

You can customize the infilling behavior using the following parameters:

- **Bar-level tonal tension**
- **Track-level texture**
- **Bar-level texture**

Texture is defined by three components:
- **Density** – Number of notes per bar.
- **Occupation** – Total duration of notes within a bar.
- **Polyphony** – Number of notes played simultaneously.

---

## ✨ Infilling Regions

You can specify the infilling region at various granularities:

- A specific **track** (e.g., only melody)
- A specific **bar** (e.g., bar 3)
- A range of **bars**
- An entire **track**

---

## 📽️ Demo

### ▶️ YouTube Video Demo  
Watch how to install, set up, and use the plugin step by step:  
📺 [YouTube – Pop Music Infilling Plugin Demo](https://youtu.be/n7aZmGCoJkI)
