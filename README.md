# Alexandru Grecu

I'm a 2026 Automatic Control and Computer Science graduate from Politehnica Bucharest. I build full-stack products, desktop apps, and automation tools, mostly around data, media, collaboration, and developer workflows.

Right now I am most interested in product engineering: taking an idea from a rough prototype to something with auth, billing, file handling, observability, tests, and a UI people can actually use.

[LinkedIn](https://www.linkedin.com/in/alexandrugrecu27/) | [chartbuilder.org](https://chartbuilder.org) | [aeroread.app](https://aeroread.app)

## featured project

### [Divario](https://github.com/GrecuAlexandru/divario)

[Project paper](https://github.com/GrecuAlexandru/divario/blob/main/Divario.pdf)

Hybrid Web2/Web3 workspace for collaborative documents, shared canvases, and PDF proof-of-existence.

Divario was my diploma project. It keeps normal collaboration fast with WebSockets and PostgreSQL, then uses Solidity contracts when a document version needs public verification.

What it does:

- live document editing, shared canvas, workspace tree, organizations, teams, and RBAC
- snapshots, version comparison, PDF generation, and live notifications
- SHA-256 PDF hash notarization on Ethereum Sepolia
- public `/verify` page and temporary MetaMask-based external access

Stack:

- Frontend: `Next.js 15`, `React 19`, `TypeScript`, `TailwindCSS`, `Radix UI`, `Quill 2.0`, `HTML5 Canvas`
- Backend: `Python`, `FastAPI`, `SQLAlchemy`, `PostgreSQL`, `WebSockets`, `ReportLab`
- Web3: `Solidity`, `Web3.py`, `Ethereum Sepolia`, `SHA-256`

## shipped products

### chartbuilder

[chartbuilder.org](https://chartbuilder.org)  
Private repo

AI chart generation platform that turns prompts or uploaded datasets into editable, exportable charts. Built and shipped in 2026.

What I built:

- natural language chart generation with OpenRouter and structured validation
- CSV, TSV, Excel, and JSON upload flows with dataset profiling
- ECharts rendering, chart templates, saved chats, table editing, and visual chart configuration
- Supabase auth workflows, Polar checkout and webhooks, credit billing, usage history, and support tickets
- rate limited API routes, upload hardening, prompt and content safety checks, cron jobs, health checks, Sentry, PostHog, Vitest, and Playwright coverage

Stack: `Next.js 16`, `React 19`, `TypeScript`, `TailwindCSS`, `shadcn/ui`, `Supabase`, `OpenRouter`, `ECharts 6`, `Zod`, `Polar`, `Upstash Redis`, `Resend`, `Sentry`, `PostHog`, `Vitest`, `Playwright`

### aeroread

[aeroread.app](https://aeroread.app)  
Private repo

Desktop reader for EPUB, PDF, and Markdown. The focus is simple: make long reading sessions feel good.

What it includes:

- clean reader UI with responsive layouts and smooth transitions
- Stay on Top mode for reading while working in other apps
- highlight export to Obsidian
- built-in Pomodoro sessions for focused reading

Stack: `Tauri`, `React`, `TypeScript`, `Vite`, `AlignUI`, `TailwindCSS`, `Epub.js`, `PDF.js`

## selected public projects

### [ml_win_logs_anomalies](https://github.com/GrecuAlexandru/ml_win_logs_anomalies)

1st place at Eestec Olympics Main Challenge Hackathon, Bitdefender challenge.

Machine learning project for spotting anomalies in Windows system logs.

Stack: `Python`, `Scikit-learn`, `Pandas`, `NumPy`

### [ShortGen](https://github.com/GrecuAlexandru/ShortGen)

Short video generation system that pulls source content, creates scripts, generates voiceovers, captions the result, and wraps the workflow in a Gradio interface.

Stack: `Python`, `Gradio`, `OpenAI API`, `ElevenLabs`, `Edge TTS`, `Whisper Timestamped`, `MoviePy`, `PyTorch`

### [silent_autopost](https://github.com/GrecuAlexandru/silent_autopost)

Python bot that generates short videos and posts them to YouTube Shorts through the YouTube Data API.

Stack: `Python`, `Google API Client`, `YouTube Data API`, `MoviePy`

### [CivicAlert](https://github.com/GrecuAlexandru/CivicAlert)

Smart city incident reporting platform with maps, reports, and Firebase-backed data.

Stack: `Next.js`, `Firebase`, `ArcGIS Maps SDK`

### [Orix Engine](https://github.com/GrecuAlexandru/orix-engine)

Voxel engine experiment with OpenGL rendering and Steamworks multiplayer.

Stack: `C++20`, `OpenGL`, `SDL2`, `Steamworks SDK`

### [Game Console](https://github.com/GrecuAlexandru/game_console)

Custom game console and WiFi controller built with Rust embedded tooling.

Stack: `Rust Embedded`, `Embassy`

## more builds

- [CodeQuiz](https://github.com/GrecuAlexandru/codequiz): programming and IT quiz platform built with `Python`, `Microsoft SQL Server 2019`, and `Tailwind CSS`
- [IMDB Clone](https://github.com/GrecuAlexandru/imdb_clone): Java app for managing movie information
- [TimedShop](https://github.com/GrecuAlexandru/TIMEDSHOP): clothing store built with `JavaScript`, `HTML`, and `CSS`
- [TextTone](https://github.com/GrecuAlexandru/texttone): tone checker using `Next.js`, `TypeScript`, `Tailwind CSS`, and `IBM Watson NLU`
- [WatchWhatMovie](https://github.com/GrecuAlexandru/WatchWhatMovie): browser watchlist tool built with `HTML`, `CSS`, and `JavaScript`

## toolbox

`Next.js` `React` `TypeScript` `TailwindCSS` `Python` `FastAPI` `PostgreSQL` `Supabase` `Tauri` `Rust` `C++` `Solidity` `ECharts` `Playwright` `Vitest`

## contact

The easiest place to reach me is [LinkedIn](https://www.linkedin.com/in/alexandrugrecu27/).
