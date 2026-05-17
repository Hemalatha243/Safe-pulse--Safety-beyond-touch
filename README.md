# SafePulse – Safety Beyond Touch 🛡️

AI-powered smart emergency alert system prototype.

## Quick Start in VS Code

```bash
# 1. Open this folder in VS Code
# 2. Open Terminal (Ctrl + `)

# 3. Install dependencies
npm install

# 4. Start the app
npm start
```

The app opens at **http://localhost:3000**

## Screen Routes

| Route | Screen |
|-------|--------|
| `/` | Splash Screen |
| `/onboarding` | Onboarding (5 slides) |
| `/login` | Login / OTP |
| `/home` | Home Dashboard |
| `/lock` | Lock Screen Alert |
| `/sos` | Emergency Activated |
| `/family` | Family Tracking |
| `/detection` | AI Detection |
| `/future` | Future Scope |
| `/settings` | Settings |

## Project Structure

```
safety-pulse/
├── public/
│   └── index.html
├── src/
│   ├── App.js              # Router
│   ├── index.js            # Entry point
│   ├── index.css           # Global theme & animations
│   ├── components/
│   │   ├── PhoneFrame.js   # Phone wrapper UI
│   │   └── BottomNav.js    # Navigation bar
│   └── pages/
│       ├── SplashScreen.js
│       ├── OnboardingScreen.js
│       ├── LoginScreen.js
│       ├── HomeScreen.js
│       ├── LockScreen.js
│       ├── SOSScreen.js
│       ├── FamilyScreen.js
│       ├── DetectionScreen.js
│       ├── FutureScreen.js
│       └── SettingsScreen.js
└── package.json
```

## Design System

- **Dark theme** with neon red + blue glow
- **Glassmorphism** cards throughout
- **Fonts**: Orbitron (display) · Rajdhani (headings) · Inter (body)
- **Colors**: Red `#ef4444` · Blue `#3b82f6` · Green `#22c55e`
