# NUTECH Connect

A modern student community and campus engagement platform built with React, Vite, Tailwind CSS, and TypeScript.

NUTECH Connect brings together student communication, academic resources, event updates, internship opportunities, mentorship, AI-powered help, and campus marketplace features in one smart portal.

## Features

- Campus social feed for announcements and student discussions
- Event calendar with RSVP support
- Internship and job opportunities board
- Mentor matching and student support requests
- Marketplace for buying and selling items
- Lost and found section
- Project sharing and collaboration space
- AI assistant with offline fallback support
- Student ID scanning and profile extraction support
- Responsive dashboard for university students

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide React icons
- Tesseract.js for OCR
- Canvas Confetti for UI interactions

## Project Structure

```bash
nutech-connect/
├── src/
│   ├── main.tsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.ts
├── tailwind.config.js
├── postcss.config.js
├── tsconfig.json
├── .env.example
├── README.md
└── metadata.json
```

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run the app locally

```bash
npm run dev
```

The app will start on:

```bash
http://localhost:3000
```

### 3. Build for production

```bash
npm run build
```

This will generate a production build in the `dist` folder.

### 4. Preview production build

```bash
npm run preview
```

## Environment Variables

An example environment file is included as `.env.example`.

If you want to enable live AI features, add your API key in a `.env` file:

```bash
VITE_GEMINI_API_KEY=your_api_key_here
```

If the key is missing, the app will continue to work in offline mode.

## Deployment

This project is a static frontend app and can be deployed to any Vite-compatible hosting platform, including:

- Vercel
- Netlify
- GitHub Pages
- Firebase Hosting

Because the app uses relative paths in the Vite configuration, it is suitable for static hosting.

## Notes

- The app is designed to work offline in its default mode.
- AI features are optional and can be enabled with environment variables.
- The interface is optimized for student engagement and campus workflow management.

## License

This project is open for educational and personal use. Please check with the repository owner before using it for commercial purposes.

## Author

NUTECH Connect

