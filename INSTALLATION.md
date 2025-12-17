# GrammarBuddy - Installation Guide

**Prepared by Mistress Parwinder Kaur, English Mistress**

## Prerequisites

Before installing GrammarBuddy, ensure you have the following installed on your system:

- **Node.js** (version 18.x or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**
- A modern web browser (Chrome, Firefox, Safari, or Edge)

## Installation Steps

### 1. Navigate to Project Directory

Open your terminal/command prompt and navigate to the project directory:

```bash
cd c:\xampp\htdocs\GrammarBuddy
```

### 2. Install Dependencies

Run the following command to install all required dependencies:

```bash
npm install
```

This will install:
- Next.js 14 (React framework)
- React 18 (UI library)
- TypeScript (type safety)
- TailwindCSS (styling)
- Lucide React (icons)
- Framer Motion (animations)
- Zustand (state management)
- Recharts (charts and analytics)
- And other supporting libraries

**Note:** The installation may take 2-5 minutes depending on your internet connection.

### 3. Start Development Server

Once installation is complete, start the development server:

```bash
npm run dev
```

The application will start on **http://localhost:3000**

### 4. Access the Application

Open your web browser and navigate to:

```
http://localhost:3000
```

## Default Login Credentials

### Student Account
- **Email:** student@example.com
- **Password:** student123
- **Class:** 8

### Admin Account
- **Email:** admin@grammarbuddy.com
- **Password:** admin123

## Features Overview

### For Students:
1. **Dashboard** - View your progress, points, and streaks
2. **Learn** - Browse and study grammar topics by class level
3. **Practice** - Play interactive grammar games
4. **Profile** - Track achievements and statistics

### For Admin:
1. **Content Management** - Add/edit grammar topics and games
2. **Student Management** - Monitor student progress
3. **Analytics** - View performance reports

## Project Structure

```
GrammarBuddy/
├── src/
│   ├── app/              # Next.js pages and routes
│   │   ├── page.tsx      # Landing page
│   │   ├── login/        # Login page
│   │   ├── signup/       # Signup page
│   │   ├── dashboard/    # Student dashboard
│   │   ├── learn/        # Grammar topics
│   │   ├── practice/     # Games and exercises
│   │   └── profile/      # User profile
│   ├── components/       # Reusable React components
│   │   ├── MobileAppBar.tsx
│   │   ├── MobileNav.tsx
│   │   ├── DesktopNav.tsx
│   │   └── ThemeProvider.tsx
│   ├── lib/             # Utilities and data
│   │   ├── utils.ts     # Helper functions
│   │   └── data.ts      # Grammar topics and games
│   ├── store/           # State management
│   │   ├── authStore.ts
│   │   ├── themeStore.ts
│   │   └── progressStore.ts
│   └── types/           # TypeScript type definitions
├── public/              # Static assets
├── package.json         # Dependencies
├── tailwind.config.ts   # TailwindCSS configuration
└── tsconfig.json        # TypeScript configuration
```

## Building for Production

To create an optimized production build:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## Troubleshooting

### Port Already in Use

If port 3000 is already in use, you can specify a different port:

```bash
npm run dev -- -p 3001
```

### Installation Errors

If you encounter errors during installation:

1. Delete `node_modules` folder and `package-lock.json`
2. Clear npm cache: `npm cache clean --force`
3. Reinstall: `npm install`

### TypeScript Errors

The TypeScript errors shown in the IDE are expected before running `npm install`. They will be resolved once dependencies are installed.

## Browser Compatibility

GrammarBuddy is optimized for:
- ✅ Chrome/Edge (version 90+)
- ✅ Firefox (version 88+)
- ✅ Safari (version 14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Mobile Experience

GrammarBuddy features a native app-like experience on mobile devices:
- Bottom navigation bar
- Touch-friendly interface
- Responsive design that adapts to all screen sizes
- Smooth animations and transitions

## Dark Mode

Toggle between light and dark themes using the moon/sun icon in the navigation bar.

## Support

For issues or questions, please contact:
**Mistress Parwinder Kaur, English Mistress**

---

© 2024 GrammarBuddy. All rights reserved.
