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

<div align="center">
  <a href="https://www.producthunt.com/products/timerme?embed=true&utm_source=badge-featured&utm_medium=badge&utm_source=badge-timerme" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1004035&theme=light&t=1754915641022" alt="TimerMe - Simple&#0032;productivity&#0032;timer&#0032;that&#0032;focuses&#0032;on&#0032;doing&#0032;things&#0032;well&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</div>

A modern web application providing professional **timer**, **stopwatch**, and **world clock** tools for productivity and time management. TimerMe is designed to help users focus better and work smarter with intuitive timing solutions.

This website is built with [HonoX](https://github.com/honojs/honox) and features a clean, responsive design with theme customization capabilities.

## 🚀 Quick Access - Timer Tools

### ⏱️ Popular Timer Durations

| Duration | Link | Description |
|----------|------|-------------|
| **1 Minute Timer** | [1 minute timer](https://www.timerme.com/timer/1) | Quick 1 minute countdown for short tasks |
| **2 Minute Timer** | [2 minute timer](https://www.timerme.com/timer/2) | 2 minute timer for brief activities |
| **3 Minute Timer** | [3 minute timer](https://www.timerme.com/timer/3) | 3 minute countdown timer |
| **5 Minute Timer** | [5 minute timer](https://www.timerme.com/timer/5) | 5 minute timer for short breaks |
| **10 Minute Timer** | [10 minute timer](https://www.timerme.com/timer/10) | 10 minute countdown timer |
| **15 Minute Timer** | [15 minute timer](https://www.timerme.com/timer/15) | 15 minute timer for quick sessions |
| **20 Minute Timer** | [20 minute timer](https://www.timerme.com/timer/20) | 20 minute countdown timer |
| **25 Minute Timer** | [25 minute timer](https://www.timerme.com/timer/25) | 25 minute timer - Perfect for Pomodoro technique |
| **30 Minute Timer** | [30 minute timer](https://www.timerme.com/timer/30) | 30 minute countdown timer |
| **45 Minute Timer** | [45 minute timer](https://www.timerme.com/timer/45) | 45 minute timer for extended sessions |
| **60 Minute Timer** | [60 minute timer](https://www.timerme.com/timer/60) | 1 hour timer for focused work |
| **90 Minute Timer** | [90 minute timer](https://www.timerme.com/timer/90) | 90 minute timer for long sessions |
| **120 Minute Timer** | [120 minute timer](https://www.timerme.com/timer/120) | 2 hour timer for extended work periods |

### 🎯 Core Tools

- **[Timer App](https://www.timerme.com/timer)** - Professional countdown timers with customizable durations
- **[Stopwatch App](https://www.timerme.com/stopwatch)** - Precision timing with lap recording
- **[World Clock App](https://www.timerme.com/world-clock)** - Track time across multiple timezones
- **[Custom Timer](https://www.timerme.com/timer)** - Set any duration you need

### 📱 Mobile Optimized

All timer tools are fully responsive and work perfectly on:
- 📱 Mobile phones
- 📱 Tablets  
- 💻 Desktop computers
- 🌐 Any web browser

## ✨ Features

- **⏰ Professional Timer**: Countdown timers with customizable durations, perfect for Pomodoro technique and focused work sessions
- **⏱️ Precision Stopwatch**: High-accuracy timing with lap recording for training, sports, and time tracking
- **🌍 Smart World Clock**: Track time across multiple timezones simultaneously, ideal for global teams
- **🎨 Dynamic Themes**: Three beautiful color themes (Orange, Blue, Green) with system-wide consistency
- **📱 Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **🔔 Audio Notifications**: Clear alerts when timers complete
- **💾 Persistent Settings**: Your preferences are saved across sessions

## 🛠️ Technology Stack

- **[HonoX](https://github.com/honojs/honox)**: Supersonic meta-framework for full-stack websites
- **[Biome](https://github.com/biomejs/biome)**: Fast toolchain for web project health
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework for rapid UI development
- **[TypeScript](https://www.typescriptlang.org/)**: Strongly typed programming language
- **[Cloudflare Pages](https://pages.cloudflare.com/)**: Fast and secure hosting platform

## 🚀 Getting Started

### Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Open in browser
open http://localhost:5173/
```

### Production Build

```bash
# Build for production
npm run build

# Preview production build
npm run preview

# Deploy to Cloudflare Pages
npm run deploy
```

## 📁 Project Structure

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

## 🔑 Key Features Explained

### ⏰ Timer Module
- **Multiple preset durations**: 1, 2, 3, 5, 10, 15, 20, 25, 30, 45, 60, 90, 120 minutes
- **Custom timer input**: Set any duration you need
- **SEO-optimized URLs**: Each timer duration has its own path (`/timer/5`, `/timer/25`, etc.)
- **Audio notifications**: Clear alerts when timers complete
- **Fullscreen mode**: Distraction-free timing experience

### ⏱️ Stopwatch Module
- **Precision timing**: Millisecond accuracy for professional use
- **Lap recording**: Track multiple time segments
- **Statistics**: Fastest/slowest lap tracking
- **Export functionality**: Save your recorded times
- **Professional interface**: Clean design for serious timing needs

### 🌍 World Clock Module
- **Auto-detection**: Automatically detects your timezone
- **Multiple timezones**: Track time across the globe
- **Flag indicators**: Visual country identification
- **Time status**: Morning, afternoon, evening, night indicators
- **Real-time updates**: Live time synchronization

### 🎨 Theme System
- **Three beautiful themes**: Orange (default), Blue, and Green
- **System-wide consistency**: CSS custom properties for seamless theming
- **Dynamic favicon**: Favicon changes with theme selection
- **Persistent selection**: Your theme choice is remembered
- **FOUC prevention**: No flash of unstyled content

## 🌐 SEO Optimization

TimerMe is fully optimized for search engines:

- **Comprehensive sitemap**: All timer duration pages included
- **SEO-friendly URLs**: Descriptive paths for popular timers
- **Structured data**: Rich snippets for better search visibility
- **Optimized meta tags**: Clear descriptions for each page
- **Mobile-first indexing**: Responsive design for search ranking

## 📊 Use Cases

### 🎯 Productivity & Focus
- **Pomodoro Technique**: Use 25 minute timer for focused work sessions
- **Time Blocking**: Set specific durations for different tasks
- **Break Management**: 5-15 minute timers for short breaks
- **Meeting Timers**: Keep meetings on schedule

### 🏃‍♂️ Sports & Training
- **Workout Timing**: Track exercise intervals
- **Sports Practice**: Time drills and practice sessions
- **Competition Prep**: Simulate competition timing
- **Recovery Tracking**: Monitor rest periods

### 🌍 Global Business
- **Meeting Coordination**: Schedule across timezones
- **Client Communication**: Know when clients are available
- **Project Deadlines**: Track time across regions
- **Travel Planning**: Plan around destination times

## 🤝 Contributing

We welcome contributions to improve TimerMe! Please feel free to:
- Submit issues and enhancement requests
- Suggest new timer features
- Report bugs or usability problems
- Share feedback on the user experience

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🔗 Quick Navigation

**Main Tools:**
- [Timer](https://www.timerme.com/timer) | [Stopwatch](https://www.timerme.com/stopwatch) | [World Clock](https://www.timerme.com/world-clock)

**Popular Timers:**
- [5 minute timer](https://www.timerme.com/timer/5) | [25 minute timer](https://www.timerme.com/timer/25) | [60 minute timer](https://www.timerme.com/timer/60)

**TimerMe** - Focus Better, Work Smarter ⏰

*Visit [www.timerme.com](https://www.timerme.com) for the best timer experience!*
