# Velvet App

A beautifully designed wellness platform for booking personal conversation sessions, in-person meetups, and support services.

## Features

- **Voice Calls** - 30-minute to 1-hour sessions
- **In-Person Meetups** - From 1 to 3-hour sessions
- **Late Night Support** - Async voice note support
- **Anonymous Mode** - Private conversations
- **Gift Sessions** - Share the experience with others
- **Premium Add-ons** - Priority queue, private notes, and more

## Tech Stack

- **React 18** - UI framework
- **Styled Components** - CSS-in-JS styling
- **Vercel** - Deployment platform

## Local Development

### Prerequisites
- Node.js 14+ and npm

### Setup

1. Clone the repository:
```bash
git clone https://github.com/velvetappme-blip/Velvetapp.git
cd Velvetapp
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The app will open at `http://localhost:3000`

## Building for Production

```bash
npm run build
```

The build output will be in the `build/` directory.

## Deployment to Vercel

### Option 1: GitHub Integration (Recommended)

1. Push your code to GitHub (already done)
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Select `velvetappme-blip/Velvetapp`
5. Vercel will auto-detect React settings
6. Click "Deploy"

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel login
vercel
```

## Environment Variables

Create a `.env.local` file for local development:

```
REACT_APP_API_URL=http://localhost:3001
```

For Vercel, set environment variables in the Vercel dashboard under Project Settings > Environment Variables.

## Project Structure

```
Velvetapp/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.js              # Main app component
│   └── index.js            # React entry point
├── package.json            # Dependencies and scripts
├── vercel.json             # Vercel configuration
├── .gitignore              # Git ignore rules
└── README.md               # This file
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm test` - Run tests

## Design System

- **Primary Color:** Gold (#C9A84C)
- **Secondary Color:** Light Gold (#E8C97A)
- **Background:** Dark (#08070A)
- **Typography:** Playfair Display (headings), DM Sans (body)

## Contributing

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Commit changes: `git commit -m 'Add your feature'`
3. Push to branch: `git push origin feature/your-feature`
4. Open a Pull Request

## License

All rights reserved © 2026 Velvet

## Support

For issues or questions, open a GitHub issue or contact the team.
