<div align="center"><img src="./assests/banner.png" width="100%" alt="WaPlus — The Developer-First WhatsApp Bot Framework"><br><img src="./assests/icon.svg" width="100" alt="WaPlus Icon">֎ W A P L U S

The Developer-First WhatsApp Bot Framework

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=800&lines=Build+features.+Drop+plugins.+Don't+fight+the+boilerplate.;A+WhatsApp+starter+made+for+developers.;Clean+architecture.+Powerful+plugins.+Zero+mess.;Built+by+Musteqeem+%7C+AKA+Future+Scientist;Developer+of+XADON+AI" alt="Animated WaPlus tagline"><br><img src="https://img.shields.io/badge/Node.js-20%2B-00C853?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js 20+">
<img src="https://img.shields.io/badge/@musteqeem%2Fbaileys-WhatsApp-00B8D4?style=for-the-badge" alt="Baileys">
<img src="https://img.shields.io/badge/License-MIT-FFD600?style=for-the-badge" alt="MIT License">
<img src="https://img.shields.io/badge/Architecture-Plugin--Based-7C4DFF?style=for-the-badge" alt="Plugin Architecture">
<img src="https://img.shields.io/badge/AI-Gemini%20%7C%20Groq%20%7C%20OpenAI-FF4081?style=for-the-badge" alt="AI Providers"><br><br>

<a href="https://github.com/waplusdev/waplus_ai">
<img src="https://img.shields.io/badge/GitHub-WaPlus-181717?style=for-the-badge&logo=github&logoColor=white" alt="WaPlus GitHub">
</a>
<a href="https://github.com/waplusdev/waplus_ai/stargazers">
<img src="https://img.shields.io/github/stars/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=STAR%20WAPLUS&color=gold" alt="GitHub Stars">
</a>
<a href="https://github.com/waplusdev/waplus_ai/fork">
<img src="https://img.shields.io/github/forks/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=FORK" alt="GitHub Forks">
</a>
<a href="https://github.com/waplusdev/waplus_ai/issues">
<img src="https://img.shields.io/github/issues/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=ISSUES" alt="GitHub Issues">
</a><br><br>

֎ Created by Musteqeem

AKA Future Scientist · Developer of XADON AI

<br><img src="./assests/Welcome.gif" width="80%" alt="Animated WaPlus Welcome"><br>«Build features. Drop plugins. Don't fight the boilerplate.»

<br><a href="#-quick-start">🚀 Quick Start</a> ·
<a href="#-features">✨ Features</a> ·
<a href="#-the-plugin-system">🧩 Plugins</a> ·
<a href="#-ai-engine">🤖 AI Engine</a> ·
<a href="#-deployment">☁️ Deployment</a> ·
<a href="#-contributing">🤝 Contributing</a>

</div>---

📑 Table of Contents

- "֎ What Is WaPlus?" (#-what-is-waplus)
- "✦ The Vision" (#-the-vision)
- "⚠️ Important Project Notes" (#️-important-project-notes)
- "⚡ Why WaPlus?" (#-why-waplus)
- "🎞️ WaPlus in One Animation" (#️-waplus-in-one-animation)
- "🚀 Quick Start" (#-quick-start)
- "✨ Feature Matrix" (#-feature-matrix)
- "🧩 The Plugin System" (#-the-plugin-system)
- "🪄 Create Your First Command" (#-create-your-first-command)
- "🧠 The Command Context" (#-the-command-context)
- "🎨 Rich UI Engine" (#-rich-ui-engine)
- "💎 Premium UI Layer" (#-premium-ui-layer)
- "🤖 AI Engine" (#-ai-engine)
- "🧠 AI Reply Awareness" (#-ai-reply-awareness)
- "🛡️ Moderation" (#️-moderation)
- "🐙 GitHub Integration" (#-github-integration)
- "📋 Commands" (#-commands)
- "📁 Architecture" (#-architecture)
- "🔄 Message Lifecycle" (#-message-lifecycle)
- "🧪 Development" (#-development)
- "🧑‍💻 Recommended Workflow" (#-recommended-workflow)
- "☁️ Deployment" (#️-deployment)
- "📦 Free Bot vs npm Framework" (#-free-bot-vs-npm-framework)
- "🔐 Security Checklist" (#-security-checklist)
- "🧰 Future Ideas" (#-future-ideas)
- "🤝 Contributing" (#-contributing)
- "👑 About the Creator" (#-about-the-creator)
- "🙏 Credits" (#-credits)
- "⚠️ Responsible Use" (#️-responsible-use)
- "⭐ Give WaPlus a Star" (#-give-waplus-a-star)

---

֎ What Is WaPlus?

WaPlus is a clean, powerful, and fully editable WhatsApp bot starter framework built on "@musteqeem/baileys".

It is made for developers who want to build WhatsApp bots without spending days rebuilding:

- Connection logic
- Pairing systems
- Message serializers
- Command dispatchers
- Permission systems
- Plugin loaders
- UI helpers
- AI integrations
- Database layers
- Deployment configuration

WaPlus turns all of that into a developer-friendly foundation.

<div align="center">                         ֎ WAPLUS
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       SIMPLE            MODULAR          POWERFUL
          │                 │                 │
          ▼                 ▼                 ▼
     Easy to learn     Drop-in plugins    Easy to extend
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                    YOUR WHATSAPP BOT

</div>---

✦ The Vision

WaPlus was created with one simple philosophy:

<div align="center">✨ Developers should build features — not fight boilerplate.

</div>Instead of creating a giant "message-handler.js" with thousands of lines containing every possible feature, WaPlus separates responsibilities.

WhatsApp
   │
   ▼
Baileys
   │
   ▼
Serializer
   │
   ▼
Message Dispatcher
   │
   ├───────────────┐
   │               │
   ▼               ▼
Commands        Events
   │               │
   ▼               ├── Anti-link
Plugin Registry   ├── Anti-spam
   │               ├── Welcome
   ▼               ├── Chatbot
execute(ctx)       └── Logger

The result?

- Clean core.
- Small handlers.
- Powerful plugins.
- Happy developers.

---

⚠️ Important Project Notes

«🔌 For Beginners

Finding it difficult to create your own "msg handler" file?

Use our pre-built version with 5 command handlers:

"🔗 waplusdev/WAPLUS_HANDLER" (https://github.com/waplusdev/WAPLUS_HANDLER)»

«🚧 Main Project Status

Project: "waplusdev/WAPLUS_AI" (https://github.com/waplusdev/WAPLUS_AI)

Status: "ROUGH SKETCH"

This project may contain errors and is not recommended for production deployment without testing.»

<div align="center"><img src="https://img.shields.io/badge/Status-Rough_Sketch-red?style=for-the-badge" alt="Project Status">
<img src="https://img.shields.io/badge/Handler-Ready-green?style=for-the-badge" alt="Handler Status"></div>---

⚡ Why WaPlus?

<table>
<tr>
<td width="50%">֎ Beginner Friendly

You don't need to understand the entire WhatsApp protocol before creating your first command.

</td>
<td width="50%">⚡ Developer Focused

The architecture is designed around the developer experience, not just the bot's command count.

</td>
</tr>
<tr>
<td width="50%">🧩 Plugin Powered

Create a file, export a command, drop it into the commands directory, and let the loader handle the rest.

</td>
<td width="50%">🧠 AI Ready

Gemini, Groq, and OpenAI-compatible providers can live behind one clean AI layer.

</td>
</tr>
<tr>
<td width="50%">🎨 Rich UI

Reusable cards, Unicode interfaces, buttons, notices, status displays, and premium decorations.

</td>
<td width="50%">🚀 Deployment Ready

Designed for local development, VPS, Pterodactyl, Railway, Render, Koyeb, and similar Node.js environments.

</td>
</tr>
</table>---

🎞️ WaPlus in One Animation

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=1800&pause=500&color=7C4DFF&center=true&vCenter=true&width=700&lines=WhatsApp+%E2%86%92+Baileys+%E2%86%92+Dispatcher;Dispatcher+%E2%86%92+Plugin+Registry;Plugin+Registry+%E2%86%92+Your+Feature;Your+Feature+%E2%86%92+Your+Bot+%E2%9C%A6" alt="Animated WaPlus architecture"><br><img src="./assests/Welcome.gif" width="70%" alt="WaPlus animated welcome"></div>---

🚀 Quick Start

Requirements

Requirement| Version
Node.js| 20+
npm| Latest recommended
WhatsApp| Required for bot operation
Internet| Required

Check Your Environment

node -v
npm -v

1. Clone

git clone https://github.com/waplusdev/waplus_ai.git
cd waplus_ai

2. Install

npm install

3. Configure

Copy ".env.example" to ".env".

Example configuration:

BOT_NAME=WaPlus
BOT_VERSION=2.0.0

OWNER_NAME=Musteqeem
OWNER_NUMBER=2348012345678

PREFIX=.

REQUEST_PAIRING=true
PAIRING_NUMBER=2348012345678

SESSION_NAME=sessions

PUBLIC_MODE=true
AUTO_READ=false
AUTO_TYPING=false

PORT=3000
COMMAND_COOLDOWN_MS=1000

Important: Replace example phone numbers and other placeholder values with your own configuration. Never commit real credentials or API keys to a public repository.

4. Pair WhatsApp

Run:

npm run pair

Or:

node index.js pair

Follow the pairing instructions.

If the web pairing panel is enabled, open:

"http://localhost:3000"

5. Start the Bot

npm start

Then send:

.menu

to your bot.

<div align="center">֎ Welcome to WaPlus.

</div>---

✨ Feature Matrix

System| Included| Extensible
WhatsApp Pairing| ✅| ✅
Plugin Loader| ✅| ✅
Command Registry| ✅| ✅
Hot Reload| ✅| ✅
Permission System| ✅| ✅
Unicode UI| ✅| ✅
Buttons| ✅| ✅
AI Engine| ✅| ✅
Gemini| ✅| ✅
Groq| ✅| ✅
OpenAI-compatible| ✅| ✅
SQLite / Database Layer| ✅| ✅
GitHub Integration| ✅| ✅
Anti-link| ✅| ✅
Anti-spam| ✅| ✅
Anti-tag-all| ✅| ✅
Welcome System| ✅| ✅
Message Logging| Optional| ✅
Media Adapters| Optional| ✅
Web Panel| Optional| ✅
VPS Deployment| ✅| ✅
Pterodactyl| ✅| ✅
Railway| ✅| ✅
Render| ✅| ✅
Termux| ✅| ✅

Availability depends on the actual modules included in your current checkout and their configuration.

---

🧩 The Plugin System

This is the heart of WaPlus.

Traditional Bot

message-handler.js
│
├── ping
├── menu
├── sticker
├── antilink
├── antispam
├── chatbot
├── welcome
├── downloader
├── github
├── notes
├── admin
├── owner
└── EVERYTHING ELSE

WaPlus

src/
└── commands/
    ├── core/
    ├── ai/
    ├── moderation/
    ├── group/
    ├── tools/
    ├── developer/
    └── utility/

Each feature gets its own home.

This makes your project easier to maintain, debug, extend, and understand.

---

🪄 Create Your First Command

Create this file:

"src/commands/tools/hello.js"

Add the following code:

module.exports = {
  name: 'hello',
  aliases: ['hi'],
  category: 'tools',
  desc: 'Say hello',

  async run({ reply, text }) {
    await reply(
      `֎ Hello ${text || 'Developer'}!\n\n` +
      `Welcome to WaPlus.`
    );
  }
};

Reload the plugins:

.reload

Then execute:

.hello

That's it.

- No giant handler edit.
- No command registration file.
- No complicated routing.
- No unnecessary boilerplate.

---

🧠 The Command Context

A command can receive the following properties, depending on the implementation of the current dispatcher.

Property| Description
"sock"| WhatsApp socket
"m"| Normalized message
"args"| Parsed arguments
"text"| Full command text
"reply()"| Reply helper
"fail()"| Error response helper
"ui"| UI system
"ui.fonts"| Unicode font helpers
"db"| Database layer
"target()"| Mention/reply/user resolver
"isOwner"| Owner permission
"isAdmin"| Group-admin permission
"isBotAdmin"| Bot-admin permission
"group"| Group information

---

🎨 Rich UI Engine

WaPlus isn't satisfied with:

Bot online.

It can create structured Unicode interfaces.

Example

await reply(
  ui.card({
    icon: '֎',
    title: 'WaPlus',
    subtitle: 'Runtime Information',

    rows: [
      ['Developer', 'Musteqeem'],
      ['Alias', 'Future Scientist'],
      ['Runtime', process.uptime()],
      ['Status', 'ONLINE']
    ]
  })
);

Visual Concept

╭────────────────────────────────────╮
│ ֎  WAPLUS                          │
│                                    │
│  RUNTIME INFORMATION               │
│                                    │
│  Developer    Musteqeem            │
│  Alias        Future Scientist     │
│  Status       ONLINE               │
│  Runtime      04h 21m              │
│                                    │
│  ──────────────────────────────    │
│  Build. Drop. Extend.              │
╰────────────────────────────────────╯

The example assumes that the current UI implementation exposes "ui.card()" and that the command context provides "ui".

---

💎 Premium UI Layer

The premium layer can provide reusable message decoration such as:

Feature| Purpose
AI badge| Brand AI responses
Verified-style quote| Rich reply presentation
Channel context| Newsletter/channel presentation
Service labels| Additional message decoration
Buttons| Quick actions
URL buttons| Open links
Copy buttons| Copy content
Lists| Structured menus
Cards| Consistent visual responses
Signal bars| Ping/runtime displays
Error boxes| Consistent failures

The architecture keeps these features out of individual commands.

COMMAND
   │
   ▼
reply(...)
   │
   ▼
UI / Premium Layer
   │
   ▼
WhatsApp

Instead of forcing every developer to rebuild the same UI, WaPlus centralizes reusable presentation logic.

---

🤖 AI Engine

WaPlus includes an extensible AI architecture.

<div align="center">                 ֎ AI ENGINE
                      │
       ┌──────────────┼──────────────┐
       ▼              ▼              ▼
    Gemini          Groq       OpenAI-compatible
       │              │              │
       └──────────────┼──────────────┘
                      ▼
                  AI SERVICE
                      │
                      ▼
                 WaPlus Bot

</div>Gemini

AI_PROVIDER=gemini
GEMINI_API_KEY=your_key
GEMINI_MODEL=gemini-2.0-flash

OpenAI-Compatible

AI_PROVIDER=openai
OPENAI_API_KEY=your_key
OPENAI_MODEL=gpt-4o-mini
OPENAI_BASE_URL=https://api.openai.com/v1/chat/completions

Groq

AI_PROVIDER=groq
GROQ_API_KEY=your_key
GROQ_MODEL=your_model

Security: Store API keys in environment variables. Never hard-code them into plugins or publish them in your repository.

Example Commands

Ask AI:

.ai Explain JavaScript closures

Ask a general question:

.ask What makes WaPlus different?

Enable automatic chatbot responses:

.chatbot on

Disable them:

.chatbot off

These commands require the corresponding AI and chatbot plugins to be present and configured.

---

🧠 AI Reply Awareness

A powerful pattern is allowing AI to understand a message's context.

User
 │
 ├── .ai question
 │
 └── Reply to a message
          │
          ▼
       AI Engine
          │
          ▼
     Understand context
          │
          ▼
       Response

This allows AI commands to evolve without rewriting the entire bot architecture.

---

🛡️ Moderation

WaPlus treats moderation as plugins rather than permanent handler clutter.

Anti-Link

.antilink on
.antilink off
.antilink

Anti-Spam

.antispam on
.antispam off
.antispam

Anti-Tag-All

.antitagall on
.antitagall off
.antitagall

Welcome System

.welcome on
.welcome off
.welcome

Per-group settings can be stored independently, depending on the implementation of the relevant plugins and database layer.

---

🐙 GitHub Integration

Optional GitHub controls can be configured using:

GITHUB_TOKEN=your_token
GITHUB_OWNER=your_username

Example Commands

.github status
.github repos
.github issues owner/repository
.github issue owner/repository Fix login bug
.github dispatch owner/repository workflow.yml main

🔐 Security

Never expose:

- "GITHUB_TOKEN"
- "OPENAI_API_KEY"
- "GEMINI_API_KEY"
- "GROQ_API_KEY"

Keep credentials in environment variables or a suitable secrets manager.

---

📋 Commands

The following is the intended command overview. The exact command list depends on the plugins included in your current checkout.

Category| Command| Description
General| ".menu"| Full command menu
General| ".ping"| Latency test
General| ".alive"| Bot status
General| ".about"| Project information
General| ".runtime"| Runtime statistics
General| ".owner"| Owner contact
AI| ".ai"| Ask AI
AI| ".ask"| AI assistant
Tools| ".sticker"| Image to sticker
Tools| ".vv"| View-once helper
Tools| ".fancy"| Unicode fonts
Tools| ".getpp"| Profile picture
Group| ".groupinfo"| Group information
Group| ".tagall"| Mention members
Group| ".kick"| Remove members
Owner| ".premium"| Premium settings
Owner| ".settings"| Bot configuration
Developer| ".plugins"| Loaded plugins
Developer| ".reload"| Reload plugins
Moderation| ".antilink"| Anti-link
Moderation| ".antispam"| Anti-spam
Moderation| ".antitagall"| Anti-tag-all
Moderation| ".welcome"| Welcome system

---

📁 Architecture

The intended project structure is outlined below. Individual files may differ depending on the current checkout.

WaPlus/
│
├── .github/
│
├── assests/
│   ├── icon.svg
│   ├── Welcome.gif
│   └── banner.png
│
├── assets/
│   └── waplus-unicode-animated.gif
│
├── Public/
├── public/
├── library/
├── scripts/
├── settings/
│
├── src/
│   ├── commands/
│   │   ├── core/
│   │   ├── ai/
│   │   ├── moderation/
│   │   ├── developer/
│   │   ├── group/
│   │   ├── tools/
│   │   └── utility/
│   │
│   ├── plugin/
│   └── lib/
│       ├── ui.js
│       ├── fonts.js
│       ├── premium.js
│       ├── serialize.js
│       ├── database.js
│       └── ai.js
│
├── bot.js
├── cli.js
├── config.js
├── index.js
├── PLUGIN_GUIDE.md
├── PLUGIN_TEMPLATE.js.example
├── package.json
├── package-lock.json
├── railway.json
├── render.yaml
└── README.md

---

⚠️ Example & Reference Files

Not every file exists because the bot absolutely needs it.

Some files are included specifically for:

- Examples
- Templates
- Documentation
- Reference implementations
- Experimental features
- Optional integrations
- Deployment examples
- Developer education

For example:

"PLUGIN_TEMPLATE.js.example"

exists to demonstrate how a plugin can be structured.

Likewise, some adapters, utilities, or example commands may not be part of the essential runtime path.

This is intentional.

WaPlus is also an educational starter.

We want developers to be able to open the repository and discover:

«"Ah... so THIS is how I build a feature."»

instead of:

«"What the hell is this 4,000-line handler?"»

---

🔄 Message Lifecycle

flowchart TD
    A["📱 WhatsApp"] --> B["@musteqeem/baileys"]
    B --> C["Message Serializer"]
    C --> D["Central Dispatcher"]

    D --> E["Event Plugins"]
    D --> F["Command Parser"]

    E --> G["Moderation"]
    E --> H["Chatbot"]
    E --> I["Welcome"]
    E --> J["Logging"]

    F --> K["Plugin Registry"]
    K --> L["Permission Checks"]
    L --> M["Command Execution"]

    G --> N["Response"]
    H --> N
    I --> N
    J --> N
    M --> N

    N --> A

GitHub renders Mermaid diagrams in supported Markdown contexts.

---

🧬 Architecture in One Picture

<div align="center">                         ┌────────────────────┐
                         │      WHATSAPP      │
                         └─────────┬──────────┘
                                   │
                                   ▼
                         ┌────────────────────┐
                         │ @musteqeem/baileys │
                         └─────────┬──────────┘
                                   │
                                   ▼
                         ┌────────────────────┐
                         │     SERIALIZER     │
                         └─────────┬──────────┘
                                   │
                                   ▼
                         ┌────────────────────┐
                         │     DISPATCHER     │
                         └───────┬──┴─────────┘
                                 │
                  ┌──────────────┴──────────────┐
                  │                             │
                  ▼                             ▼
         ┌─────────────────┐          ┌─────────────────┐
         │     EVENTS      │          │    COMMANDS     │
         └────────┬────────┘          └────────┬────────┘
                  │                            │
                  ▼                            ▼
         ┌─────────────────┐          ┌─────────────────┐
         │ Plugin System   │          │ Plugin Registry │
         └────────┬────────┘          └────────┬────────┘
                  │                            │
                  └──────────────┬─────────────┘
                                 ▼
                       ┌─────────────────────┐
                       │    YOUR FEATURE     │
                       └──────────┬──────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │    RICH UI / AI     │
                       └──────────┬──────────┘
                                  │
                                  ▼
                             WHATSAPP

</div>---

🧪 Development

Run the offline checker:

npm run check

This allows you to test the project without necessarily logging into WhatsApp, provided the checker is implemented to run offline.

Inspect plugins:

.plugins

Reload plugins:

.reload

Suggested Development Checks

Before deploying changes, verify:

- [ ] The application starts without syntax errors.
- [ ] Environment variables are configured.
- [ ] Plugins load successfully.
- [ ] Invalid commands fail gracefully.
- [ ] Permission checks work correctly.
- [ ] API errors are handled.
- [ ] Sensitive credentials are not logged.
- [ ] The WhatsApp session persists as expected.

---

🧑‍💻 Recommended Workflow

<div align="center">      ┌──────────────┐
      │ Clone WaPlus │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │ npm install  │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │ Configure    │
      │    .env      │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │ Pair WhatsApp│
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │ Create Plugin│
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │ npm run check│
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │    .reload   │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │    Deploy    │
      └──────────────┘

</div>---

☁️ Deployment

WaPlus targets Node.js 20+ environments.

Platform| Support
Local PC| ✅
VPS| ✅
Pterodactyl| ✅
Railway| ✅
Render| ✅
Koyeb| ✅
Termux| ✅

Actual deployment compatibility depends on the repository's dependencies, configuration, storage requirements, and platform restrictions.

Generic Production Start

npm start

---

🖥️ VPS

Clone and install:

git clone https://github.com/waplusdev/waplus_ai.git
cd waplus_ai
npm install

Configure:

cp .env.example .env
nano .env

Pair WhatsApp:

node index.js pair

Start:

npm start

PM2

Install PM2:

npm install -g pm2

Start the application:

pm2 start index.js --name waplus
pm2 save
pm2 startup

View logs:

pm2 logs waplus

Note: Confirm that the project's "start" script and entry point match your current installation before configuring a process manager.

---

🐳 Pterodactyl

Use Node.js 20+.

Install dependencies:

npm install

Pair WhatsApp:

node index.js pair

Start:

npm start

Keep the session persistent.

Do not allow the "sessions/" directory to disappear after a container restart.

---

🚂 Railway / Render / Koyeb

Build/install:

npm install

Start:

npm start

Configure environment variables through your hosting provider.

If the host uses ephemeral storage, configure persistent storage for your WhatsApp session or use an appropriate external session strategy.

---

📦 Free Bot vs npm Framework

WaPlus has two conceptual distributions.

֎ Free Source Bot

Complete application
│
├── Editable source
├── Plugin system
├── Commands
├── Configuration
├── Deployment files
└── Beginner-friendly architecture

📦 npm Framework

Install separately:

npm install waplus

Conceptually:

WaPlus npm
│
├── Framework
├── Runtime
├── APIs
├── Reusable components
└── Developer ecosystem

They are separate distributions.

The free repository is intended to be downloaded, studied, modified, and deployed.

Verify the npm package name and published package contents before installing or distributing the framework.

---

🔐 Security Checklist

Before production:

Check| Status
".env" ignored| ✅
"sessions/" ignored| ✅
API keys protected| ✅
GitHub token protected| ✅
Strong owner configuration| ✅
Bot permissions reviewed| ✅
Untrusted plugins avoided| ✅
Logging reviewed| ✅
Production secrets excluded| ✅

These are security goals to verify, not guarantees that the current checkout already satisfies them.

Never publish:

- ".env"
- "sessions/"
- "auth/"
- "creds.json"
- Private tokens
- API keys
- Private databases

---

🧰 Future Ideas

WaPlus is designed to grow.

<details>
<summary><b>🎬 Media & Downloaders</b></summary>.play
.ytmp4
.tiktok
.instagram
.facebook
.spotify
.pinterest

</details><details>
<summary><b>🧠 Advanced AI</b></summary>.imagine
.tts
.transcribe
.translate
.remini

Potential extensions:

- AI chatbot per chat
- AI memory
- AI tools
- AI agents

</details><details>
<summary><b>🛡️ Advanced Moderation</b></summary>.warn
.mute
.unmute
.promote
.demote
.hidetag
.poll
.goodbye
.anticall
.antidelete

</details><details>
<summary><b>🧰 Developer Tools</b></summary>.eval
.restart
.broadcast
.webhook

Potential extensions:

- API adapters
- Plugin marketplace
- Multi-session support
- Scheduler

</details>---

🤝 Contributing

Want to make WaPlus better?

The easiest contribution is a plugin.

1. Create a File

src/commands/<category>/<command>.js

2. Export a Command

module.exports = {
  name: 'example',
  aliases: ['ex'],
  category: 'tools',
  desc: 'Example command',

  async run({ reply }) {
    await reply('֎ Hello from WaPlus');
  }
};

3. Check

npm run check

4. Reload

.reload

5. Document

Explain:

- What it does
- Command syntax
- Arguments
- Permissions
- Required environment variables
- External APIs

---

🌟 The WaPlus Rule

<div align="center">╭──────────────────────────────────────────╮
│                                          │
│             ֎ WAPLUS RULE                │
│                                          │
│   If a feature can be a plugin,          │
│   make it a plugin.                      │
│                                          │
│   Keep the core small.                   │
│   Keep plugins powerful.                 │
│   Keep developers free.                  │
│                                          │
╰──────────────────────────────────────────╯

Build. Drop. Extend.

</div>---

❤️ Why This Project Exists

WaPlus wasn't created just to make another WhatsApp bot.

It was created to make building WhatsApp bots easier for the next developer.

A developer should be able to clone the project and think:

«"Okay..."»

«"I understand the structure."»

«"I know where commands go."»

«"I know where plugins go."»

«"I can create my own feature."»

«"I don't need to rewrite the handler."»

«"Let's build."»

That is the experience WaPlus aims for.

---

👑 About the Creator

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=800&size=24&duration=2500&pause=800&color=FFD600&center=true&vCenter=true&width=700&lines=Musteqeem;AKA+Future+Scientist;Developer+of+XADON+AI;Creator+of+WaPlus;Building+tools+for+the+next+generation+of+developers" alt="Animated creator introduction"><br><img src="./assests/icon.svg" width="90" alt="WaPlus icon">֎ Musteqeem

AKA Future Scientist

Creator of WaPlus

Developer of XADON AI

</div>---

🙏 Credits

- Musteqeem AKA Future Scientist — Creator of WaPlus
- XADON AI — Development inspiration and ecosystem
- "@musteqeem/baileys" — WhatsApp Web protocol layer
- Open-source Node.js ecosystem
- Baileys ecosystem contributors
- Every developer who tests, forks, contributes, and builds with WaPlus

---

⚠️ Responsible Use

WaPlus is a developer framework.

Use it responsibly and comply with applicable laws and platform rules.

Do not use it for:

- Spam
- Harassment
- Unauthorized access
- Credential theft
- Malicious automation
- Abuse

The project is provided for legitimate development, experimentation, and automation.

---

⭐ Give WaPlus a Star

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2200&pause=700&color=00E5FF&center=true&vCenter=true&width=750&lines=If+WaPlus+helped+you...;Star+the+repository+%E2%AD%90;Fork+it+%F0%9F%8D%B4;Build+a+plugin+%F0%9F%A7%A9;Make+something+amazing+%F0%9F%9A%80" alt="Animated GitHub call to action"><br><br>

<a href="https://github.com/waplusdev/waplus_ai/stargazers">
<img src="https://img.shields.io/badge/%E2%98%85%20STAR%20WAPLUS-FFD600?style=for-the-badge&logo=github&logoColor=black&labelColor=181717" alt="Star WaPlus">
</a><a href="https://github.com/waplusdev/waplus_ai/fork">
<img src="https://img.shields.io/badge/%E2%9C%A6%20FORK%20WAPLUS-7C4DFF?style=for-the-badge&logo=github&logoColor=white&labelColor=181717" alt="Fork WaPlus">
</a><br><br>

If WaPlus helps you build something amazing, give the repository a star!

</div>---

֎ Final Message

<div align="center"><img src="./assets/waplus-unicode-animated.gif" width="180" alt="Animated WaPlus Unicode logo"><img src="./assests/icon.svg" width="70" alt="WaPlus icon">W A P L U S

Build. Drop. Extend.

<br>╔════════════════════════════════════════════╗
║                                            ║
║              ֎  W A P L U S  ֎            ║
║                                            ║
║       Built by Musteqeem                   ║
║       AKA Future Scientist                 ║
║       Developer of XADON AI                ║
║                                            ║
║       Build features.                      ║
║       Drop plugins.                        ║
║       Don't fight the boilerplate.         ║
║                                            ║
╚════════════════════════════════════════════╝

Made for developers. Built to be extended.

<br>⭐ Star the repository.

🍴 Fork the project.

🧩 Build the next plugin.

🚀 Build something bigger.

<br>֎ WaPlus — Where developers come to build.

<br><a href="https://github.com/waplusdev/waplus_ai/stargazers">
<img src="https://img.shields.io/github/stars/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=STAR%20WAPLUS&color=gold" alt="Star WaPlus">
</a><a href="https://github.com/waplusdev/waplus_ai/fork">
<img src="https://img.shields.io/github/forks/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=FORK" alt="Fork WaPlus">
</a></div>---

<div align="center">MIT License · Built with Node.js · Powered by "@musteqeem/baileys"

<br><img src="https://komarev.com/ghpvc/?username=waplusdev&repo=waplus_ai&style=for-the-badge&color=00E5FF" alt="Repository views"><br><br>

<img src="./assests/Welcome.gif" width="60%" alt="WaPlus animated welcome"><br>֎ WAPLUS — BUILD WITHOUT LIMITS.

</div>