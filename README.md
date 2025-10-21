# Project Broteas

**Discuss, Discover, Disco**

D1SCO is a web app built with SvelteKit that helps to build and empower communities centered around music. Share your favorite artists, albums, and songs, discover what others are listening to, and engage in discussions about music.

## Features

- **Music Discovery**: Search and explore artists, albums, and songs powered by Spotify
- **Social Feed**: Share posts about your favorite music and see what others are listening to
- **Artist & Album Pages**: Dedicated pages for artists and albums with community discussions
- **User Profiles**: Create and customize your profile, follow other users
- **Comments & Discussions**: Engage in threaded conversations on posts
- **Spotify Integration**: Connect your Spotify account for personalized features
- **News Feed**: Stay updated with music news
- **Mobile Responsive**: Fully responsive design with dedicated mobile layouts
- **Golden Ticket Referral System**: Invite friends to join the community

## Tech Stack

- **Frontend**: SvelteKit 1.20.4
- **Styling**: TailwindCSS 3.3.3 + Flowbite 1.8.1
- **Backend**: Firebase 10.4.0 (Authentication, Firestore, Storage)
- **API Integration**: Spotify Web API
- **Language**: TypeScript 5.0.0
- **Build Tool**: Vite 4.4.2
- **Testing**: Playwright (integration) + Vitest (unit)

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn
- Firebase account
- Spotify Developer account

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd broteas-app
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory with your Firebase and Spotify credentials.

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run test` - Run all tests
- `npm run test:unit` - Run unit tests
- `npm run test:integration` - Run integration tests
- `npm run check` - Run Svelte/TypeScript checks
- `npm run lint` - Lint code
- `npm run format` - Format code with Prettier