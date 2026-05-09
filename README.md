<h1 align="center">SnapStoryView</h1>
<h3 align="center">Free Snapchat Story Viewer & Spotlight Downloader — View and Download Snap Stories Anonymously</h3>

<p align="center">
  <a href="https://snapstoryview.com"><img src="https://img.shields.io/badge/Website-snapstoryview.com-FFFC00?style=for-the-badge&logo=snapchat&logoColor=black" alt="Website"></a>
  <img src="https://img.shields.io/badge/Node.js-18.x-green?style=for-the-badge&logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/Next.js-14.x-black?style=for-the-badge&logo=next.js" alt="Next.js">
  <img src="https://img.shields.io/badge/yt--dlp-latest-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="yt-dlp">
  <img src="https://img.shields.io/badge/Tailwind-3.x-38BDF8?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome">
</p>

<p align="center">
  <a href="https://snapstoryview.com"><b>🌐 Visit Website</b></a> •
  <a href="#-features"><b>✨ Features</b></a> •
  <a href="#-product-suite"><b>🧰 Product Suite</b></a> •
  <a href="#-how-to-use"><b>📖 How to Use</b></a> •
  <a href="#%EF%B8%8F-tech-stack"><b>🛠️ Tech Stack</b></a> •
  <a href="#-faq"><b>❓ FAQ</b></a>
</p>

---

## 📖 About

**SnapStoryView** is a free, web-based Snapchat Story Viewer and Spotlight Downloader that lets you watch and save public Snapchat content **anonymously** — without logging in, without installing an app, and without revealing your identity to the original poster. Whether you want to catch up on a creator's latest stories, archive a Spotlight clip in HD, or grab a friend's Bitmoji avatar, SnapStoryView gives you a clean, fast, and private way to do it from any browser on any device.

We built SnapStoryView because the existing tools for viewing Snap content are either riddled with intrusive ads, hide their best features behind paywalls, leak user data through third-party trackers, or require shady browser extensions. Our mission is simple: provide a **trustworthy, free, and privacy-respecting** way to interact with public Snapchat content — for fans, journalists, marketers, content creators, and anyone curious about a public Snap profile.

Under the hood, SnapStoryView combines a modern Next.js frontend with a robust Node.js API layer and the industry-standard **yt-dlp** media extraction engine to reliably resolve and download high-quality video assets from public Snap URLs.

👉 **Try it now:** [https://snapstoryview.com](https://snapstoryview.com)

---

## ✨ Features

| Feature | Description |
| :--- | :--- |
| 👻 **Anonymous Story Viewing** | Watch any public Snapchat user's stories without signing in or being seen |
| ⬇️ **HD Spotlight Downloads** | Save Snapchat Spotlight videos in their original highest quality (powered by yt-dlp) |
| 🧑‍🎨 **Bitmoji Downloader** | Grab Bitmoji avatars from public profiles in PNG format |
| 🔓 **No Login Required** | Zero authentication — never connect a Snapchat account |
| 📱 **Works on Any Device** | Fully responsive on desktop, tablet, Android, and iOS browsers |
| ⚡ **Fast & Lightweight** | Server-side rendered pages and CDN-cached assets for instant load |
| 🆓 **Free & Unlimited** | No daily caps, no premium tier, no surprise paywalls |
| 🌍 **Multi-Language Support** | English, Spanish, and more — localized routes for global users |
| 🛡️ **Privacy-First** | We do not log usernames, store downloads, or share data with third parties |
| 🧼 **Clean, Ad-Light UI** | Distraction-free interface focused entirely on the task |

---

## 🧰 Product Suite

SnapStoryView is a complete toolkit for working with public Snapchat content. Each tool is purpose-built and accessible directly from the website:

### 🌐 [SnapStoryView Home](https://snapstoryview.com/)
The main hub. Search for any public Snapchat username and instantly browse their public stories, profile info, and Spotlight clips — all without an account.

### 👻 [Snapchat Story Downloader](https://snapstoryview.com/story-downloader)
View and **download Snapchat stories anonymously**. Paste a username or a story URL, preview the story, and save it to your device. Great for archiving content, reposting with permission, or simply watching without notifying the creator.

### ⬇️ [Snapchat Spotlight Downloader](https://snapstoryview.com/spotlight-downloader)
Download trending **Snapchat Spotlight videos in HD** with one click. Just paste the Spotlight link and SnapStoryView (powered by **yt-dlp**) fetches the highest-resolution version available — no watermark, no compression artifacts.

### 🧑‍🎨 [Snapchat Bitmoji Downloader (ES)](https://snapstoryview.com/es/snapchat-bitmoji-downloader)
Save any public Snapchat user's **Bitmoji avatar** as a transparent PNG. Available in our localized Spanish experience for our LATAM audience — perfect for memes, profile pics, and creative projects.

> 🌎 More localized experiences and tools are rolling out continuously. Visit [snapstoryview.com](https://snapstoryview.com) for the full menu.

---

## 📖 How to Use

### Viewing a Snapchat Story Anonymously

1. Go to [https://snapstoryview.com](https://snapstoryview.com) or directly to the [Story Downloader](https://snapstoryview.com/story-downloader).
2. Enter the **public Snapchat username** (e.g., `username`) into the search box.
3. Click **View Stories** — SnapStoryView pulls the public story feed.
4. Watch each snap **anonymously** — the original poster is never notified.
5. Click the download icon on any snap to save it locally in original quality.

### Downloading a Spotlight Video in HD

1. Open the [Spotlight Downloader](https://snapstoryview.com/spotlight-downloader).
2. **Copy the Spotlight URL** from the Snapchat app or web (`https://www.snapchat.com/spotlight/...`).
3. Paste it into the input box and click **Download**.
4. SnapStoryView's yt-dlp-powered backend resolves the highest-quality MP4 and offers an instant download.

### Downloading a Bitmoji

1. Visit the [Bitmoji Downloader](https://snapstoryview.com/es/snapchat-bitmoji-downloader).
2. Enter the public Snapchat username.
3. Preview the Bitmoji avatar.
4. Click **Download PNG** to save a transparent, high-resolution image.

> 💡 **Tip:** All three tools are completely browser-based — no apps, plugins, or extensions to install.

---

## 🛠️ Tech Stack

SnapStoryView is engineered with a modern, production-grade stack tuned for speed, scalability, and SEO performance.

### Frontend
- **Next.js 14 (App Router)** — React framework with server components, route handlers, and built-in i18n
- **React 18** — Modern UI library with concurrent rendering
- **TypeScript** — Strict typing across the codebase
- **Tailwind CSS** — Utility-first styling for a consistent design system
- **Shadcn/UI + Radix Primitives** — Accessible, composable UI components
- **Framer Motion** — Smooth, performant animations

### Backend
- **Node.js (v18+)** — Runtime for API routes and server actions
- **Next.js Route Handlers** — REST-style endpoints colocated with the app
- **yt-dlp** — Battle-tested media extraction engine used to resolve and download Snapchat Spotlight videos and other public media at the highest available quality
- **Python 3** — Required runtime for invoking yt-dlp from the Node.js backend
- **child_process / execa** — Safe, sandboxed spawning of yt-dlp subprocesses with timeout and resource limits
- **Axios + Got** — Outbound HTTP clients for fetching Snap public endpoints
- **Cheerio** — Server-side HTML parsing for content extraction
- **Zod** — Runtime input validation for every request
- **Rate-Limiter-Flexible + Redis** — Abuse prevention and fair-use enforcement

### Media Pipeline (yt-dlp)
- **URL validation** — Zod schema ensures only valid public Snapchat URLs reach the extractor
- **yt-dlp subprocess** — Spawned with strict format selection (`bv*+ba/b`) for HD merged MP4 output
- **FFmpeg** — Used by yt-dlp under the hood for muxing video + audio streams
- **Streaming response** — Resolved media is streamed directly to the user; nothing is persisted on disk
- **Auto-update** — yt-dlp is kept on the latest release via a scheduled GitHub Actions job to keep up with Snapchat's changes

### Infrastructure & SEO
- **Vercel / Node.js Edge** — Global edge deployment with automatic scaling (yt-dlp workloads run on a dedicated Node.js server with FFmpeg + Python preinstalled)
- **Cloudflare** — CDN, DDoS protection, image optimization, and SSL
- **PostgreSQL (Neon/Supabase)** — Persistent storage for analytics and i18n strings
- **Redis (Upstash)** — Caching, rate limiting, and session storage
- **next-sitemap** — Automatic XML sitemap generation for every locale
- **next-intl** — Multi-language routing (`/`, `/es/`, and more)
- **JSON-LD structured data** — Rich snippets for Google Search and Discover

### DevOps & Quality
- **GitHub Actions** — CI/CD pipelines (lint, typecheck, test, deploy, scheduled yt-dlp updates)
- **Docker** — Container image bundling Node.js, Python, yt-dlp, and FFmpeg for reproducible deploys
- **ESLint + Prettier** — Consistent code style enforcement
- **Vitest + Playwright** — Unit, integration, and end-to-end testing
- **Sentry** — Production error tracking and performance monitoring
- **Husky + lint-staged** — Pre-commit hooks for code quality

---

## 🚀 Getting Started (Local Development)

### Prerequisites
- Node.js **v18.0.0** or higher
- npm **v9+**, pnpm, or yarn
- **Python 3.8+** (required by yt-dlp)
- **yt-dlp** (`pip install -U yt-dlp` or via your package manager)
- **FFmpeg** (`brew install ffmpeg` on macOS, `apt install ffmpeg` on Debian/Ubuntu)
- Git
- (Optional) Redis instance for rate-limiting in dev

### Installation

```bash
# Clone the repository
git clone https://github.com/aayush988/snapstoryview-downloader.git

# Move into the project directory
cd snapstoryview-downloader

# Install Node.js dependencies
npm install

# Install / update yt-dlp (recommended: keep it on the latest release)
pip install -U yt-dlp

# Verify yt-dlp and ffmpeg are on your PATH
yt-dlp --version
ffmpeg -version

# Copy environment variables template
cp .env.example .env.local

# Run the development server
npm run dev
```

The app will be running at `http://localhost:3000`.

### Available Scripts

| Command | Description |
| :--- | :--- |
| `npm run dev` | Start the Next.js dev server with hot reload |
| `npm run build` | Build the production bundle |
| `npm start` | Run the production server |
| `npm run lint` | Run ESLint across the codebase |
| `npm run typecheck` | Run TypeScript in `--noEmit` mode |
| `npm test` | Run unit and integration tests |
| `npm run test:e2e` | Run Playwright end-to-end tests |
| `npm run ytdlp:update` | Pull the latest yt-dlp release |

---

## 📁 Project Structure

```
snapstoryview-downloader/
├── app/
│   ├── (marketing)/             # Landing pages
│   ├── story-downloader/        # Story viewer & downloader route
│   ├── spotlight-downloader/    # Spotlight HD downloader route
│   ├── es/
│   │   └── snapchat-bitmoji-downloader/  # Localized Bitmoji tool
│   └── api/                     # Route handlers (REST endpoints)
├── components/
│   ├── ui/                      # Shadcn/Radix primitives
│   └── features/                # Feature-specific components
├── lib/
│   ├── snap/                    # Snapchat public API integration
│   ├── ytdlp/                   # yt-dlp subprocess wrapper & format selectors
│   ├── seo/                     # Structured data, sitemaps, metadata
│   └── utils/                   # Shared utilities
├── messages/                    # i18n translation files (en, es, ...)
├── public/                      # Static assets
├── tests/                       # Unit, integration, and E2E tests
├── .env.example
├── Dockerfile                   # Bundles Node.js, Python, yt-dlp, FFmpeg
├── next.config.mjs
├── package.json
└── README.md
```

---

## 🔍 SEO & Performance

SnapStoryView is built with SEO and Core Web Vitals as first-class concerns:

- ✅ **Server-side rendered** for instant content visibility to crawlers
- ✅ **Per-page metadata** — unique titles, descriptions, and OpenGraph tags
- ✅ **JSON-LD structured data** for rich results (SoftwareApplication, FAQPage, BreadcrumbList)
- ✅ **Auto-generated XML sitemap** with locale alternates
- ✅ **Hreflang tags** for international SEO (`en`, `es`, ...)
- ✅ **Optimized images** via Next.js `<Image>` and Cloudflare Polish
- ✅ **Lighthouse 95+** on Performance, Accessibility, Best Practices, and SEO
- ✅ **Mobile-first responsive design**
- ✅ **Fast TTFB** thanks to edge deployment and aggressive caching

---

## ❓ FAQ

**Q: Is SnapStoryView really free?**  
A: Yes — every tool on the site is 100% free. No subscriptions, no premium tiers, no paywalls.

**Q: Do I need a Snapchat account?**  
A: No. SnapStoryView only works with **public** profiles and content, and never asks for any login.

**Q: Will the user know I viewed their story?**  
A: No. SnapStoryView fetches public stories server-side, so the original poster is never notified.

**Q: What can I download?**  
A: Public Snapchat stories, Spotlight videos in HD, and Bitmoji avatars (PNG).

**Q: How do you fetch the videos?**  
A: We use **yt-dlp**, the most reliable open-source media extractor available, paired with FFmpeg for muxing. yt-dlp is auto-updated regularly so the service stays compatible with Snapchat's evolving formats.

**Q: Is it legal to download Snapchat content?**  
A: SnapStoryView only accesses **public** content. Always respect copyright and the original creator's rights — download for personal, fair-use purposes, and ask permission before reposting.

**Q: Do you store my searches or downloads?**  
A: No. We do not log usernames you search for, URLs you submit, or files you download.

**Q: Does it work on mobile?**  
A: Absolutely. The site is fully responsive and works great on iOS Safari, Android Chrome, and tablets.

**Q: Are there any download limits?**  
A: No daily caps for normal use. We rate-limit only obvious automated abuse so the service stays fast for everyone.

**Q: Is there a Spanish version?**  
A: Yes — for example, the [Bitmoji Downloader is available in Spanish](https://snapstoryview.com/es/snapchat-bitmoji-downloader). More locales are rolling out.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/aayush988/snapstoryview-downloader/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure your code passes `npm run lint` and `npm run typecheck` before submitting.

---

## 🙏 Credits & Acknowledgements

SnapStoryView stands on the shoulders of giants. Huge thanks to the maintainers of:

- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — the incredible media extraction engine that powers our HD downloads
- **[FFmpeg](https://ffmpeg.org/)** — for the muxing and transcoding backbone
- **[Next.js](https://nextjs.org/)**, **[React](https://react.dev/)**, and the entire open-source web ecosystem

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 🌐 Links

- **🏠 Homepage:** [https://snapstoryview.com](https://snapstoryview.com)
- **👻 Story Downloader:** [https://snapstoryview.com/story-downloader](https://snapstoryview.com/story-downloader)
- **⬇️ Spotlight Downloader:** [https://snapstoryview.com/spotlight-downloader](https://snapstoryview.com/spotlight-downloader)
- **🧑‍🎨 Bitmoji Downloader (ES):** [https://snapstoryview.com/es/snapchat-bitmoji-downloader](https://snapstoryview.com/es/snapchat-bitmoji-downloader)
- **📦 Repository:** [github.com/aayush988/snapstoryview-downloader](https://github.com/aayush988/snapstoryview-downloader)
- **🐛 Issues:** [Report a bug or request a feature](https://github.com/aayush988/snapstoryview-downloader/issues)

---

<p align="center">
  Made with 💛 by the SnapStoryView team
  <br>
  <a href="https://snapstoryview.com"><b>👉 Visit snapstoryview.com</b></a>
</p>
