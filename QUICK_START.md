# GrammarBuddy - Quick Start Guide

**Prepared by Mistress Parwinder Kaur, English Mistress**

## 🚀 Getting Started in 3 Steps

### Step 1: Install Node.js

**Node.js is required to run this application.**

1. Download Node.js from: https://nodejs.org/
2. Choose the **LTS (Long Term Support)** version
3. Run the installer and follow the installation wizard
4. Restart your computer after installation

**Verify Installation:**
Open Command Prompt and type:
```bash
node --version
npm --version
```

You should see version numbers displayed.

### Step 2: Install Project Dependencies

Open Command Prompt and navigate to the project folder:

```bash
cd c:\xampp\htdocs\GrammarBuddy
```

Install all dependencies:

```bash
npm install
```

**This will take 2-5 minutes.** Wait for it to complete.

### Step 3: Start the Application

After installation completes, start the development server:

```bash
npm run dev
```

Open your browser and go to:
```
http://localhost:3000
```

## 🎓 Login Credentials

### Student Account
- Email: `student@example.com`
- Password: `student123`

### Admin Account
- Email: `admin@grammarbuddy.com`
- Password: `admin123`

## 📱 Features

### Student Features:
- ✅ Interactive grammar lessons for Classes 6-10
- ✅ Game-based learning with quizzes
- ✅ Progress tracking and analytics
- ✅ Achievement badges and rewards
- ✅ Daily streak tracking
- ✅ Mobile-friendly interface
- ✅ Dark/Light mode

### Admin Features:
- ✅ Content management system
- ✅ Student progress monitoring
- ✅ Performance analytics
- ✅ Game and topic management

## 🎮 How to Use

1. **Sign In** - Use the demo credentials above
2. **Explore Topics** - Click "Learn" to browse grammar topics
3. **Play Games** - Click "Practice" to test your knowledge
4. **Track Progress** - View your stats in the Dashboard
5. **Earn Rewards** - Complete games to unlock achievements

## 📂 Project Files Created

```
✅ package.json - Dependencies configuration
✅ tsconfig.json - TypeScript configuration
✅ tailwind.config.ts - Styling configuration
✅ next.config.js - Next.js configuration

✅ src/app/ - All pages (landing, login, signup, dashboard, learn, practice, profile)
✅ src/components/ - Reusable UI components
✅ src/lib/ - Utilities and data (6 grammar topics, 3 games)
✅ src/store/ - State management (auth, theme, progress)
✅ src/types/ - TypeScript type definitions

✅ README.md - Project documentation
✅ INSTALLATION.md - Detailed installation guide
✅ QUICK_START.md - This file
```

## 🎨 Design Features

- **Mobile-First Design** - Native app-like experience on phones
- **Responsive Layout** - Works on all screen sizes
- **Bottom Navigation** - Easy thumb-friendly mobile navigation
- **Desktop Navbar** - Professional layout for larger screens
- **Glass Effect** - Modern, beautiful UI
- **Smooth Animations** - Engaging user experience
- **Dark Mode** - Eye-friendly theme switching

## 📊 Grammar Content Included

### Topics by Class Level:

**Class 6:**
- Parts of Speech
- Subject-Verb Agreement
- Articles

**Class 7:**
- Tenses

**Class 8:**
- Active and Passive Voice

**Class 9:**
- Direct and Indirect Speech

Each topic includes:
- Detailed explanations
- Multiple examples
- Interactive games
- Practice exercises

## 🎯 Games Included

1. **Parts of Speech Quiz** - Identify parts of speech (Easy)
2. **Tense Master** - Choose correct tenses (Medium)
3. **Agreement Challenge** - Fix grammar errors (Easy)

More games can be easily added through the admin panel!

## 🔧 Troubleshooting

**Problem:** Port 3000 is already in use
**Solution:** Use a different port:
```bash
npm run dev -- -p 3001
```

**Problem:** Installation fails
**Solution:** 
1. Delete `node_modules` folder
2. Run `npm cache clean --force`
3. Run `npm install` again

**Problem:** Page not loading
**Solution:** 
1. Make sure the dev server is running
2. Check if you're using the correct URL (http://localhost:3000)
3. Try refreshing the browser

## 📞 Support

For questions or issues, contact:
**Mistress Parwinder Kaur, English Mistress**

## 🎉 Next Steps

1. ✅ Install Node.js (if not already installed)
2. ✅ Run `npm install` in the project directory
3. ✅ Run `npm run dev` to start the server
4. ✅ Open http://localhost:3000 in your browser
5. ✅ Login with demo credentials
6. ✅ Start learning grammar!

---

**Prepared by Mistress Parwinder Kaur, English Mistress**

© 2024 GrammarBuddy. All rights reserved.
