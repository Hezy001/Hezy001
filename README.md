<div align="center">

# Hezekiah Fashae

**Frontend Developer | Building for the Web**

I build fast, responsive, and intuitive web applications. Currently deepening my frontend expertise with React,Next.js and Tailwind CSS .
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hezykiah)
[![X](https://img.shields.io/badge/X-black.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/hezykiah001)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fashaehezekiah@outlook.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/hezykiah001)

</div>

---

## About Me

I build clean and responsive user interfaces with React, Next.js, and Tailwind.
Big on good design, smooth user experience, and making things actually work.
Currently leveling up my JavaScript by building real projects.
---

## Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-%2306B6D4.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## Featured Projects

### QuoteForge — AI-Powered Quote Generator                   https://quote-forge-smoky.vercel.app/

A full-featured quote discovery app with real-time API integration, user authentication, and an interactive UI. Pulls quotes dynamically from an external API, lets users save favorites, share to social media, and browse by category.

**Key Features:**
- User authentication (sign up, sign in, password reset, Google OAuth simulation)
- Real-time quote fetching from DummyJSON Quotes API with category filtering
- Next.js API route as a proxy layer with graceful fallback handling
- Save to favorites (localStorage persistence)
- Share to X (Twitter) and LinkedIn
- Copy to clipboard
- Dark / Light theme toggle
- Focus mode for distraction-free reading
- Keyboard shortcuts (Space, S, C, F, H, Esc)
- Quote history sidebar
- Activity stats tracking

**Tech:** Next.js, React, TypeScript, Tailwind CSS, DummyJSON API, Next.js App Router, API Routes

![QuoteForge Screenshot 1](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(1).png)
![QuoteForge Screenshot 2](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(2).png)
![QuoteForge Screenshot 3](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(3).png)
![QuoteForge Screenshot 4](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(4).png)
![QuoteForge Screenshot 5](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(5).png)
![QuoteForge Screenshot 6](https://raw.githubusercontent.com/Hezy001/quoteForge/main/sc%20(6).png)

---

### Four in a Row — Real-time Connect Four with AI Opponent                   https://four-in-a-row-eight.vercel.app/
A polished Connect Four game built from scratch with three distinct modes: local pass-and-play, vs computer with three AI difficulty levels, and real-time online multiplayer with shareable room codes. Hand-crafted UI, custom minimax AI, server-authoritative networking — no UI kits, no shortcuts.

**Key Features:**
- Three game modes — Local, Vs Computer, and Online multiplayer
- AI opponent with three difficulties — Easy (random), Medium (depth-4 minimax), Hard (depth-7 alpha-beta pruning)
- Real-time online multiplayer over Socket.io with 4-character room codes
- Server-authoritative move validation — clients can't cheat
- Graceful disconnect handling with rematch flow (both players must accept)
- Score tracking across rounds (wins per player, ties)
- Hand-crafted UI with CSS Modules — no Tailwind, no UI kit
- Smooth physical disc-drop animations, pulsing winning cells, hover previews
- Mobile-first responsive layout with 44px+ tap targets
- `useReducer` game state — no external state library
- Centralized Socket.io logic in a single React hook
- Copy-to-clipboard room codes, animated waiting screen, slide-up status banners

**Tech:** React 18, Vite, Socket.io (client + server), Node.js, Express, CSS Modules, JavaScript (ES2020+)

![Four in a Row Screenshot 1](https://raw.githubusercontent.com/Hezy001/four-in-a-row/main/Screenshot%20(5).png)
![Four in a Row Screenshot 2](https://raw.githubusercontent.com/Hezy001/four-in-a-row/main/Screenshot%20(6).png)
![Four in a Row Screenshot 3](https://raw.githubusercontent.com/Hezy001/four-in-a-row/main/Screenshot%20(8).png)
![Four in a Row Screenshot 4](https://raw.githubusercontent.com/Hezy001/four-in-a-row/main/Screenshot%20(9).png)

---

### Meeting Notes Taker — Live Meeting Capture with Smart Categorization           https://meeting-tracker-rho.vercel.app/

A modern meeting notes app that captures timestamped notes in real time and auto-generates a structured recap, separating action items from general notes. Distinctive dark UI with neon-lime accent, animated ambient blobs, and a phase-based flow — splash → setup → live → recap.

**Key Features:**
- Animated splash screen with keyboard shortcuts (Enter / Space to advance)
- Pre-meeting setup — name the meeting and add attendees as chips
- Live elapsed-time counter (HH:MM:SS), updated every second
- Quick-tag chips — TODO, Action, Decision, Question, Follow up — one click prefixes the input
- Real-time timestamped notes with auto-scroll to the latest entry
- Edit / delete notes during the meeting on hover
- Smart categorization — notes containing `todo`, `action`, `follow up`, `assign`, or `deadline` are extracted as Action Items; the rest go into Summary
- Editable meeting title in the recap view
- Recap stats — start, end, duration, total words
- Copy summary to clipboard, or download as `.md` / `.txt`
- Distinctive dark UI with neon-lime accent, animated ambient blobs, subtle grid overlay, custom scrollbar
- Fully local — no backend, no tracking, no accounts

**Tech:** React 19, TypeScript, Vite, Tailwind CSS v4

![Meeting Tracker Screenshot 1](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(10).png)
![Meeting Tracker Screenshot 2](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(11).png)
![Meeting Tracker Screenshot 3](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(12).png)
![Meeting Tracker Screenshot 4](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(13).png)
![Meeting Tracker Screenshot 5](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(14).png)
![Meeting Tracker Screenshot 6](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(15).png)
![Meeting Tracker Screenshot 7](https://raw.githubusercontent.com/Hezy001/meeting-tracker/main/Screenshot%20(16).png)

---



<div align="center">

![](https://github-readme-stats.vercel.app/api?username=Hezy001&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=Hezy001&theme=tokyonight&hide_border=true&layout=compact&count_private=true)

</div>

---

<div align="center">

*Currently open to collaborations and opportunities.*

</div>
