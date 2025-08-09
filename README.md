<div align="center">

# TimerMe - Professional Timer Tools

</div>

<div align="center">

**🌐 Website:** [www.timerme.com](https://www.timerme.com)

**⏰ Focus Better, Work Smarter**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built with HonoX](https://img.shields.io/badge/Built%20with-HonoX-orange)](https://github.com/honojs/honox)
[![Deployed on Cloudflare](https://img.shields.io/badge/Deployed%20on-Cloudflare%20Pages-blue)](https://pages.cloudflare.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-3178c6)](https://www.typescriptlang.org/)

---

</div>

A modern web application providing professional timer, stopwatch, and world clock tools for productivity and time management. TimerMe is designed to help users focus better and work smarter with intuitive timing solutions.

This website is built with [HonoX](https://github.com/honojs/honox) and features a clean, responsive design with theme customization capabilities.

## Features

- **Timer**: Professional countdown timers with customizable durations, perfect for Pomodoro technique and focused work sessions
- **Stopwatch**: Precision timing with lap recording for training, sports, and time tracking
- **World Clock**: Track time across multiple timezones simultaneously, ideal for global teams
- **Theme Support**: Dynamic color themes (Orange, Blue, Green) with system-wide consistency
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **PWA Ready**: Progressive Web App capabilities for native-like experience

## Technology Stack

- [HonoX](https://github.com/honojs/honox): HonoX is a simple and fast supersonic meta-framework for creating full-stack websites and web APIs. It is built on top of Hono, Vite, and a UI library.
- [Biome](https://github.com/biomejs/biome): Biome is a performant toolchain for web projects, aimed at providing developer tools to maintain the health of the project.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework packed with classes for rapid UI development.
- [TypeScript](https://www.typescriptlang.org/): Strongly typed programming language for better development experience.
- [Cloudflare Pages](https://pages.cloudflare.com/): Fast and secure hosting platform for modern web applications.

## Getting Started

This section explains how to set up your environment for local development.

### Installing

```bash
npm install
```

Note that this step does not necessarily have to be done with npm; you may use other package managers like bun or pnpm.

## Starting the App

### Local Environment

```bash
npm run dev
open http://localhost:5173/
```

### Production Environment

```bash
npm run build
npm run preview
```

## Project Structure

```
timerme.com/
├── app/
│   ├── components/        # Reusable UI components
│   ├── islands/          # Client-side interactive components
│   ├── routes/           # Page routes and API endpoints
│   └── style.css         # Global styles and theme variables
├── public/
│   ├── favicon*.svg      # Dynamic theme-aware favicons
│   └── sitemap.xml       # SEO sitemap
└── wrangler.toml         # Cloudflare deployment configuration
```

## Key Features

### Timer Module
- Multiple preset durations (1, 2, 3, 5, 10, 15, 20, 25, 30, 45, 60, 90, 120 minutes)
- Custom timer input for any duration
- SEO-optimized URL paths for specific timers (`/timer/5`, `/timer/25`, etc.)
- Audio notifications and visual alerts
- Fullscreen mode for distraction-free timing

### Stopwatch Module
- Precision timing with millisecond accuracy
- Lap time recording and statistics
- Fastest/slowest lap tracking
- Export functionality for recorded times
- Professional sports timing interface

### World Clock Module
- Automatic user timezone detection
- Multiple timezone support with flag indicators
- Time status indicators (morning, afternoon, evening, night)
- Customizable time formats (12/24 hour)
- Real-time updates with configurable intervals

### Theme System
- Three beautiful color themes: Orange (default), Blue, and Green
- System-wide color consistency using CSS custom properties
- Dynamic favicon that changes with theme
- Persistent theme selection across sessions
- FOUC (Flash of Unstyled Content) prevention

## Deployment

The application is configured for deployment on Cloudflare Pages:

```bash
npm run deploy
```

## SEO Optimization

TimerMe is optimized for search engines with:
- Comprehensive sitemap with all timer duration pages
- SEO-friendly URLs for popular timer durations
- Structured data markup for better search visibility
- Optimized meta tags and descriptions
- Responsive design for mobile-first indexing

## Contributing

We welcome contributions to improve TimerMe! Please feel free to submit issues and enhancement requests.

## License

This project is open source and available under the [MIT License](LICENSE).

---

**TimerMe** - Focus Better, Work Smarter ⏰
