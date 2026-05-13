# AI-VISION-ACCESIBILITY

An AI-powered accessibility assistant web app for blind and low-vision users. It uses a live camera feed to analyze the environment and provide spoken feedback in real time.

🔗 **Live Website:** [https://id-preview--fe8f18c3-8bb2-492f-bb6c-c96e86965b10.lovable.app](https://id-preview--fe8f18c3-8bb2-492f-bb6c-c96e86965b10.lovable.app)

## Features

- 📖 **OCR text reading** — books, signs, screens, and documents
- 👁️ **Scene description** using computer vision
- ⚠️ **Hazard detection** for obstacles and unsafe surroundings
- 🔊 **Text-to-speech** voice output
- 🔄 **Camera switching** between front and rear cameras
- ♿ **Minimal high-contrast** accessibility-focused interface

## Tech Stack

- React + Vite (TypeScript)
- Tailwind CSS (high-contrast theme)
- Lovable Cloud (Supabase) edge functions
- Lovable AI Gateway — Google Gemini 2.5 Flash (vision)
- Browser SpeechSynthesis API for voice feedback

## How It Works

1. User points the camera at their surroundings
2. App captures a frame
3. Image is sent to the backend edge function
4. Gemini vision model analyzes the image
5. Result is returned as text
6. App speaks the response aloud

## Run Locally

```bash
npm install
npm run dev
```

Open the app on a mobile browser for the best camera and microphone experience.
