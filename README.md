# ResumeLens AI

ResumeLens AI is an AI-powered resume analysis web app that compares a candidate’s resume against a target job description and provides ATS-focused feedback, skill gap analysis, and improvement suggestions.

Live Demo: https://resumelens-ai.vercel.app/

## Features

- Upload and parse PDF resumes
- Compare resume content with a job description
- Generate AI-based compatibility score
- ATS formatting and keyword analysis
- Identify matched skills, missing skills, and extra strengths
- Interactive resume improvement suggestions
- Built-in AI career assistant for resume and cover letter guidance
- Modern responsive UI built with React and Tailwind CSS

## Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Lucide React
- PDF.js
- Gemini API
- Vercel

Getting Started
1. Clone the repository
git clone https://github.com/RashneemaAmeen/resumelensAI.git
cd resumelensAI
2. Install dependencies
npm install
3. Add environment variables

Create a .env file in the root folder:

GEMINI_API_KEY=your_gemini_api_key_here

Do not commit this file to GitHub.

4. Run locally

For normal Vite frontend development:

npm run dev

For testing the Vercel API route locally:

vercel dev
5. Build for production
npm run build
Deployment

This project is deployed on Vercel.

Required environment variable in Vercel:

GEMINI_API_KEY=your_gemini_api_key_here

Vercel settings:

Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
Screenshots

Add screenshots here after deployment.

![ResumeLens AI Screenshot](./public/screenshots)
Future Improvements
Add user authentication
Save analysis history
Support DOCX resume uploads
Improve mobile responsiveness
Add downloadable PDF reports
Add more detailed ATS keyword scoring
Add cover letter generation templates
