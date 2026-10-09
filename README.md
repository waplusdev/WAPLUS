<div align="center"><img src="./assets/waplus-unicode-animated.gif" width="220" alt="WaPlus animated Unicode logo">֎ W A P L U S

The Developer-First WhatsApp Bot Framework

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=800&lines=Build+features.+Drop+plugins.+Don't+fight+the+boilerplate.;A+WhatsApp+starter+made+for+developers.;Clean+architecture.+Powerful+plugins.+Zero+mess.;Built+by+Musteqeem+%7C+AKA+Future+Scientist;Developer+of+XADON+AI" alt="Typing animation"><br>""Node.js" (https://img.shields.io/badge/Node.js-20%2B-00C853?style=for-the-badge&logo=node.js&logoColor=white)" (https://nodejs.org/)
""Baileys" (https://img.shields.io/badge/@musteqeem%2Fbaileys-WhatsApp-00B8D4?style=for-the-badge)" (https://www.npmjs.com/package/@musteqeem/baileys)
""License" (https://img.shields.io/badge/License-MIT-FFD600?style=for-the-badge)" (#-license)
""Architecture" (https://img.shields.io/badge/Architecture-Plugin--Based-7C4DFF?style=for-the-badge)" (#-the-plugin-system)
""AI" (https://img.shields.io/badge/AI-Gemini%20%7C%20Groq%20%7C%20OpenAI-FF4081?style=for-the-badge)" (#-ai-engine)
""GitHub" (https://img.shields.io/badge/GitHub-WaPlus-181717?style=for-the-badge&logo=github)" (https://github.com/waplusdev/waplus_ai)

<br>֎ Created by Musteqeem

AKA Future Scientist

Developer of XADON AI

<br><a href="https://github.com/waplusdev/waplus_ai/stargazers">
<img src="https://img.shields.io/github/stars/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=STAR%20WAPLUS&color=gold">
</a><a href="https://github.com/waplusdev/waplus_ai/fork">
<img src="https://img.shields.io/github/forks/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=FORK">
</a><a href="https://github.com/waplusdev/waplus_ai/issues">
<img src="https://img.shields.io/github/issues/waplusdev/waplus_ai?style=for-the-badge&logo=github&label=ISSUES">
</a><br><br>

«Build features. Drop plugins. Don't fight the boilerplate.»

</div>---

֎ What is WaPlus?

WaPlus is a clean, powerful and fully editable WhatsApp bot starter framework built on "@musteqeem/baileys".

It is made for developers who want to build WhatsApp bots without spending days rebuilding:

connection logic
pairing systems
message serializers
command dispatchers
permission systems
plugin loaders
UI helpers
AI integrations
database layers
deployment configuration

WaPlus turns all of that into a developer-friendly foundation.

                         ֎ WAPLUS
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

---

✦ The Vision

WaPlus was created with one simple philosophy:

«Developers should build features — not fight boilerplate.»

Instead of creating a giant:

message-handler.js

with thousands of lines containing every possible feature, WaPlus separates responsibilities.

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
Plugin Registry    ├── Anti-spam
   │               ├── Welcome
   ▼               ├── Chatbot
execute(ctx)       └── Logger

The result?

Clean core.

Small handlers.

Powerful plugins.

Happy developers.

## ⚠️ STRICT NOTE - PLEASE READ

> ### 🔌 For Beginners
> Finding it difficult to create your own `msg handler` file? Use our pre-built version with **5 command handlers**:
> **🔗 [waplusdev/WAPLUS_HANDLER](https://github.com/waplusdev/WAPLUS_HANDLER)**

> ### 🚧 Main Project Status
> **Project:** [waplusdev/WAPLUS_AI](https://github.com/waplusdev/WAPLUS_AI)
> **Status:** `ROUGH SKETCH` - May contain errors. Not recommended for deployment yet.

![Status](https://img.shields.io/badge/Status-Rough_Sketch-red)
![Handler](https://img.shields.io/badge/Handler-Ready-green)

---

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
<td>🧩 Plugin Powered

Create a file, export a command, drop it into the commands directory and let the loader handle the rest.

</td>
<td>🧠 AI Ready

Gemini, Groq and OpenAI-compatible providers can live behind one clean AI layer.

</td>
</tr>
<tr>
<td>🎨 Rich UI

Reusable cards, Unicode interfaces, buttons, notices, status displays and premium decorations.

</td>
<td>🚀 Deployment Ready

Designed for local development, VPS, Pterodactyl, Railway, Render, Koyeb and similar Node.js environments.

</td>
</tr>
</table>---

🎞️ WaPlus in One Animation

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=20&duration=1800&pause=500&color=7C4DFF&center=true&vCenter=true&width=700&lines=WhatsApp+%E2%86%92+Baileys+%E2%86%92+Dispatcher;Dispatcher+%E2%86%92+Plugin+Registry;Plugin+Registry+%E2%86%92+Your+Feature;Your+Feature+%E2%86%92+Your+Bot+%E2%9C%A6" alt="WaPlus architecture animation"></div>---

🚀 Quick Start

Requirements

Requirement| Version
Node.js| 20+
npm| Latest recommended
WhatsApp| Required
Internet| Required

Check your environment:

node -v
npm -v

---

1. Clone

git clone https://github.com/waplusdev/waplus_ai.git
cd waplus_ai

---

2. Install

npm install

---

3. Configure

Copy:

.env.example

to:

.env

Example:

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

---

4. Pair WhatsApp

npm run pair

or:

node index.js pair

Then follow the pairing instructions.

If the web pairing panel is enabled:

http://localhost:3000

---

5. Start

npm start

Then send:

.menu

to your bot.

֎ Welcome to WaPlus.

---

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

---

🧩 The Plugin System

This is the heart of WaPlus.

Traditional bot:

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

WaPlus:

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

---

🪄 Create Your First Command

Create:

src/commands/tools/hello.js

Then:

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

Reload:

.reload

Then:

.hello

That's it.

No giant handler edit.

No command registration file.

No complicated routing.

No unnecessary boilerplate.

---

🧠 The Command Context

A command can receive:

Property| Description
"sock"| WhatsApp socket
"m"| Normalized message
"args"| Parsed arguments
"text"| Full command text
"reply()"| Reply helper
"fail()"| Error response
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

Example:

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

Visual concept:

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

That means:

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

instead of forcing every developer to rebuild the same UI.

---

🤖 AI ENGINE

WaPlus includes an extensible AI architecture.

                 ֎ AI ENGINE
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

---

Gemini

AI_PROVIDER=gemini
GEMINI_API_KEY=your_key
GEMINI_MODEL=gemini-2.0-flash

---

OpenAI-compatible

AI_PROVIDER=openai
OPENAI_API_KEY=your_key
OPENAI_MODEL=gpt-4o-mini
OPENAI_BASE_URL=https://api.openai.com/v1/chat/completions

---

Groq

AI_PROVIDER=groq
GROQ_API_KEY=your_key
GROQ_MODEL=your_model

Then:

.ai Explain JavaScript closures

or:

.ask What makes WaPlus different?

Automatic chatbot:

.chatbot on

Disable:

.chatbot off

---

🧠 AI Reply Awareness

A powerful pattern is:

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

Anti-link

.antilink on
.antilink off
.antilink

Anti-spam

.antispam on
.antispam off
.antispam

Anti-tag-all

.antitagall on
.antitagall off
.antitagall

Welcome

.welcome on
.welcome off
.welcome

Per-group settings can be stored independently.

---

🐙 GitHub Integration

Optional GitHub controls can be configured using:

GITHUB_TOKEN=your_token
GITHUB_OWNER=your_username

Example:

.github status
.github repos
.github issues owner/repository
.github issue owner/repository Fix login bug
.github dispatch owner/repository workflow.yml main

🔐 Security

Never expose:

GITHUB_TOKEN
OPENAI_API_KEY
GEMINI_API_KEY
GROQ_API_KEY

inside plugins or public source code.

---

📋 Commands

Category| Command| Description
General| ".menu"| Full command menu
General| ".ping"| Latency test
General| ".alive"| Bot status
General| ".about"| Project information
General| ".runtime"| Runtime statistics
General| ".owner"| Owner contact
AI| ".ai"| Ask AI
AI| ".ask"| AI assistant
Tools| ".sticker"| Image → sticker
Tools| ".vv"| View-once helper
Tools| ".fancy"| Unicode fonts
Tools| ".getpp"| Profile picture
Group| ".groupinfo"| Group information
Group| ".tagall"| Mention members
Group| ".kick"| Remove member
Owner| ".premium"| Premium settings
Owner| ".settings"| Bot configuration
Developer| ".plugins"| Loaded plugins
Developer| ".reload"| Reload plugins
Moderation| ".antilink"| Anti-link
Moderation| ".antispam"| Anti-spam
Moderation| ".antitagall"| Anti-tag-all
Moderation| ".welcome"| Welcome system

«The exact command list depends on the plugins included in your current checkout.»

---

📁 Architecture

WaPlus/
│
├── .github/
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

Examples
Templates
Documentation
Reference implementations
Experimental features
Optional integrations
Deployment examples
Developer education

For example:

PLUGIN_TEMPLATE.js.example

exists to demonstrate how a plugin can be structured.

Likewise, some adapters, utilities or example commands may not be part of the essential runtime path.

This is intentional.

WaPlus is also an educational starter.

We want developers to be able to open the repository and discover:

"Ah... so THIS is how I build a feature."

instead of:

"What the hell is this 4,000-line handler?"

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

«GitHub renders Mermaid diagrams in supported Markdown contexts.»

---

🧬 Architecture in One Picture

                         ┌────────────────────┐
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

---

🧪 Development

Run the offline checker:

npm run check

This allows you to test the project without necessarily logging into WhatsApp.

Inspect plugins:

.plugins

Reload:

.reload

---

🧑‍💻 Recommended Workflow

      ┌──────────────┐
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
      │ npm check    │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │    .reload   │
      └──────┬───────┘
             ▼
      ┌──────────────┐
      │    Deploy    │
      └──────────────┘

---

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

Generic production start:

npm start

---

🖥️ VPS

git clone https://github.com/waplusdev/waplus_ai.git
cd waplus_ai
npm install

cp .env.example .env
nano .env

node index.js pair
npm start

For PM2:

npm install -g pm2

pm2 start index.js --name waplus
pm2 save
pm2 startup

Logs:

pm2 logs waplus

---

🐳 Pterodactyl

Use Node.js 20+.

Install:

npm install

Pair:

node index.js pair

Start:

npm start

Keep the session persistent.

Do not allow:

sessions/

to disappear after a container restart.

---

🚂 Railway / Render / Koyeb

Build/install:

npm install

Start:

npm start

Configure environment variables from the hosting provider.

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

The free repository is intended to be downloaded, studied, modified and deployed.

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

Never publish:

.env
sessions/
auth/
creds.json
private tokens
API keys
private databases

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
AI chatbot per chat
AI memory
AI tools
AI agents

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
.API adapters
.plugin marketplace
.multi-session
.scheduler

</details>---

🤝 Contributing

Want to make WaPlus better?

The easiest contribution is a plugin.

1. Create

src/commands/<category>/<command>.js

2. Export

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

╭──────────────────────────────────────────╮
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

---

❤️ Why This Project Exists

WaPlus wasn't created just to make another WhatsApp bot.

It was created to make building WhatsApp bots easier for the next developer.

A developer should be able to clone the project and think:

"Okay..."

"I understand the structure."

"I know where commands go."

"I know where plugins go."

"I can create my own feature."

"I don't need to rewrite the handler."

"Let's build."

That is the experience WaPlus aims for.

---

👑 About the Creator

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=800&size=24&duration=2500&pause=800&color=FFD600&center=true&vCenter=true&width=700&lines=Musteqeem;AKA+Future+Scientist;Developer+of+XADON+AI;Creator+of+WaPlus;Building+tools+for+the+next+generation+of+developers" alt="Creator animation"><br>֎ Musteqeem

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
- Every developer who tests, forks, contributes and builds with WaPlus

---

⚠️ Responsible Use

WaPlus is a developer framework.

Use it responsibly and comply with applicable laws and platform rules.

Do not use it for:

Spam
Harassment
Unauthorized access
Credential theft
Malicious automation
Abuse

The project is provided for legitimate development, experimentation and automation.

---

⭐ Give WaPlus a Star

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2200&pause=700&color=00E5FF&center=true&vCenter=true&width=750&lines=If+WaPlus+helped+you...;Star+the+repository+%E2%AD%90;Fork+it+%F0%9F%8D%B4;Build+a+plugin+%F0%9F%A7%A9;Make+something+amazing+%F0%9F%9A%80" alt="Star animation"><br><br>

<a href="https://github.com/waplusdev/waplus_ai/stargazers"><img src="https://img.shields.io/badge/%E2%98%85%20STAR%20WAPLUS-FFD600?style=for-the-badge&logo=github&logoColor=black&labelColor=181717"></a><a href="https://github.com/waplusdev/waplus_ai/fork"><img src="https://img.shields.io/badge/%E2%9C%A6%20FORK%20WAPLUS-7C4DFF?style=for-the-badge&logo=github&logoColor=white&labelColor=181717"></a></div>---

֎ Final Message

<div align="center"><img src="./assets/waplus-unicode-animated.gif" width="180" alt="WaPlus ֎">WAPLUS

Build. Drop. Extend.

<br>╔════════════════════════════════════════════╗
║                                            ║
║              ֎  W A P L U S  ֎            ║
║                                            ║
║       Built by Musteqeem                  ║
║       AKA Future Scientist                ║
║       Developer of XADON AI               ║
║                                            ║
║       Build features.                     ║
║       Drop plugins.                       ║
║       Don't fight the boilerplate.        ║
║                                            ║
╚════════════════════════════════════════════╝

Made for developers. Built to be extended.

<br>⭐ Star the repository.

🍴 Fork the project.

🧩 Build the next plugin.

🚀 Build something bigger.

<br>֎ WaPlus — Where developers come to build.

</div>---

<div align="center">MIT License • Built with Node.js • Powered by "@musteqeem/baileys"

<br><img src="https://komarev.com/ghpvc/?username=waplusdev&repo=waplus_ai&style=for-the-badge&color=00E5FF" alt="Repository views"></div>