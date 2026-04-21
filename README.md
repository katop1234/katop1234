
# 👕 VibeTry - AI Virtual Fashion Studio

A high-end virtual try-on experience powered by **Gemini 2.5 Flash Image**. Upload a photo of yourself, select or upload clothing, and see how it looks in parallel.

## 🚀 One-Click Deployment (Vercel)

1. **Push this code to GitHub** (Use the Cursor Source Control sidebar).
2. Go to [Vercel](https://vercel.com).
3. Click **"Add New" -> "Project"**.
4. Import this repository.
5. **CRITICAL**: In the "Environment Variables" section, add:
   - **Key**: `API_KEY`
   - **Value**: Your Gemini API Key from [Google AI Studio](https://aistudio.google.com/).
6. Click **Deploy**.

## ✨ Features
- **Parallel Synthesis**: Try on multiple outfits at the same time.
- **Local Persistence**: Your model photo and custom closet are saved to your browser's local storage.
- **Auto-Hydration**: System samples are automatically prepared for the AI engine on load.
- **Mobile First**: Designed to feel like a premium native app on iOS/Android browsers.

## 🛠️ Technical Stack
- **AI**: Google Gemini (Nano Banana / 2.5 Flash Image)
- **Frontend**: React 19 + TypeScript
- **Bundler**: Vite
- **Styling**: Tailwind CSS
# katop1234
