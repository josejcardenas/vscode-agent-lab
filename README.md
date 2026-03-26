# 🎉 Soc Ops — Social Bingo

> **Break the ice. Meet your people. Get five in a row.**

Soc Ops is a fast, fun social bingo game built for in-person mixers, team events, and networking gatherings. Each player gets a unique bingo card filled with fun facts. Find real humans who match each square, mark them off, and shout **BINGO!**

[![Deploy to GitHub Pages](https://github.com/josejcardenas/vscode-agent-lab/actions/workflows/deploy.yml/badge.svg)](https://github.com/josejcardenas/vscode-agent-lab/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## ✨ Features

- 🃏 **Randomized Bingo Cards** — Every player gets a unique 5×5 card so no two games are the same
- 🙋 **People-first Questions** — Prompts like *"speaks more than 2 languages"* or *"has been skydiving"* spark real conversations
- 📱 **Mobile-ready** — Designed for your pocket; works on any phone browser, no install required
- 🚀 **Zero friction** — Open the link, tap Start, and you're playing in seconds
- 🎯 **Free Space included** — Classic center free square for a head start
- 🥳 **Win celebration** — A satisfying BINGO moment when five in a row are found

---

## 🕹️ How to Play

1. **Share the link** — Send your event's game URL to all participants
2. **Each player taps "Start Game"** on their own device to get a unique card
3. **Mingle!** — Walk around and find people who match the squares on your card
4. **Tap a square** to mark it when you've found a match
5. **First to get 5 in a row** — horizontally, vertically, or diagonally — wins!

---

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to play locally.

### Build for production

```bash
npm run build
```

Deploys automatically to **GitHub Pages** on every push to `main`.

---

## 🛠️ Customization

Make the game your own by editing the questions in [`src/data/questions.ts`](src/data/questions.ts):

```ts
export const questions: string[] = [
  "bikes to work",
  "has lived in another country",
  // Add your own prompts here!
];
```

Theme ideas to inspire your next card:
| Theme | Example prompts |
|---|---|
| 🧑‍💻 Tech Life | *"has a mechanical keyboard"*, *"uses vim"* |
| 🌍 Travel | *"has visited 5+ countries"*, *"can navigate without GPS"* |
| 🎨 Creative | *"plays an instrument"*, *"has drawn a portrait"* |
| 🏢 Work Culture | *"has taken notes on paper today"*, *"prefers async communication"* |
| 🎭 Personality | *"is the group planner"*, *"always arrives early"* |

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Framework | [React 19](https://react.dev/) |
| Language | [TypeScript](https://www.typescriptlang.org/) |
| Styling | [Tailwind CSS v4](https://tailwindcss.com/) |
| Build tool | [Vite](https://vite.dev/) |
| Testing | [Vitest](https://vitest.dev/) + [Testing Library](https://testing-library.com/) |
| Hosting | [GitHub Pages](https://pages.github.com/) |

---

## 🤝 Contributing

Have a great question idea or a feature request? Open an issue or pull request — contributions are welcome!

---

## 📄 License

MIT © [Harald Kirschner](https://github.com/digitarald) and the VS Code team
