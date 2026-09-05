### 👋 Hi there, I'm Aryan!

Full-stack developer with a JavaScript/Node.js background, currently branching into Python and AI-adjacent tooling. I build complete, deployed products rather than tutorials-left-half-finished — most of my repos are full-stack apps with a real frontend, backend, and database behind them.

---

### 🛠️ When I code, I rely on

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neon](https://img.shields.io/badge/-Neon-00E599?style=flat-square&logo=neon&logoColor=black)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Socket.IO](https://img.shields.io/badge/-Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Liveblocks](https://img.shields.io/badge/-Liveblocks-000000?style=flat-square&logoColor=white)

---

### 🚀 Featured Projects

#### ⚔️ [CodeClash](https://github.com/Aryannaik-max/CodeClash)
A **1v1 real-time competitive programming platform** — a head-to-head coding duel arena.
- Built with **Next.js, TypeScript, Express, Redis, and PostgreSQL**
- **Monaco Editor** integrated for an in-browser coding experience
- Real-time **WebSocket matchmaking** via Socket.IO
- GitHub OAuth + email/password auth, with **Redux Toolkit** managing frontend auth state
- Custom **pixel-art western theme** — sunset gradients, wood textures, a hand-built "Wanted Poster" profile page using SVG and clip-path corners, Press Start 2P typography
- Backend hardened with a **Prisma transaction fix** for a match-creation race condition; DB migrated to **Neon** after a large-row OOM issue on the free tier
- In progress: pluggable code-execution/judge service (Wandbox/Judge0)

#### 🪐 [Novaspace](https://github.com/Aryannaik-max/Novaspace) + [Novaspace-Backend](https://github.com/Aryannaik-max/Novaspace-Backend)
A **real-time collaborative workspace app** in the spirit of Notion/Linear — workspaces, live collaborative documents, task boards, file sharing, and team chat.
- **React + Vite** frontend, deployed on Vercel
- **Liveblocks** for real-time presence/collaboration
- **Tailwind CSS** for styling, **JWT** for auth
- Split into dedicated frontend and backend repositories

---

### 🧠 Beyond the Code

I'm also active in **competitive programming** — working through Codeforces and CodeChef contests and LeetCode by pattern (sliding window, two pointers, binary search, hashing, monotonic stacks), which feeds directly into how I think about performance and edge cases in my projects (like the CodeClash judge pipeline).

---

### 📊 GitHub Stats

<p align="left">
  <img src="./profile/stats.svg" height="165" alt="Aryan's GitHub stats" />
  <img src="./profile/top-langs.svg" height="165" alt="Top languages" />
</p>

<p align="left">
  <img src="./profile/streak.svg" alt="GitHub streak stats" />
</p>

---

### 📫 Let's Connect

Open to remote full-stack opportunities — feel free to check out [CodeClash](https://github.com/Aryannaik-max/CodeClash) or [Novaspace](https://github.com/Aryannaik-max/Novaspace).

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryan-naik-a75b98324/)
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aryannaik365@gmail.com)

<!--
Rendering notes:
- Profile views badge (komarev) is a live third-party service and renders on its own.
- Stats, top-languages, and streak cards are now self-hosted: a GitHub Actions workflow
  (.github/workflows/update-readme-cards.yml) regenerates them as static SVGs and commits
  them into ./profile/ once a day. This avoids the public Vercel/Heroku instances entirely,
  so they won't go blank from rate limiting.
- Setup: place both this README.md and the .github/workflows folder in a repo named
  EXACTLY `Aryannaik-max` (GitHub's special "profile README" repo), then go to the
  Actions tab and manually run "Update README cards" once (workflow_dispatch) so the
  SVGs exist before anyone views the profile. After that it refreshes daily on its own.
-->
