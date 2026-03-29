<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/af5deb09-bde1-4858-839e-ebebc0aaea5d

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Features

• Topic-based question generation

• Multiple question formats
  - Fill in the blanks
  - Matching
  - True / False
  - Short answer
  - Long answer

• Difficulty levels
  - Standard
  - Normal
  - JEE level
  - NEET level
  - Olympiad level

• Progress tracking
Students can see their performance using graphs and progress analysis.

• Score evaluation
Final score is calculated after completing the questions.

• Question generation from notes
Students can upload images of handwritten notes and generate questions from them.

• Voice-to-question feature
Students can speak their notes and the system converts speech to text to generate questions.
