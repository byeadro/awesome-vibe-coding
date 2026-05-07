<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,30:7C3AED,70:F7DF1E,100:58A6FF&height=240&section=header&text=awesome-vibe-coding&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=The%20playbook%20for%20non-technical%20founders%20shipping%20real%20software%20with%20AI&descAlignY=62&descSize=16" />

# 🎯 Awesome Vibe Coding

### A curated, opinionated list of tools, prompts, patterns, and resources for non-technical founders building real software with AI.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/byeadro/awesome-vibe-coding?style=for-the-badge&logo=github&color=F7DF1E)](https://github.com/byeadro/awesome-vibe-coding/stargazers)
[![Contributors](https://img.shields.io/github/contributors/byeadro/awesome-vibe-coding?style=for-the-badge&color=7C3AED)](https://github.com/byeadro/awesome-vibe-coding/graphs/contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2ea043.svg?style=for-the-badge)](CONTRIBUTING.md)
[![Made Without Instructions](https://img.shields.io/badge/Made%20Without-Instructions-7C3AED?style=for-the-badge)](https://medium.com/@byeadro)

</div>

---

## What this is

This is not another "AI coding tools" list.

This is a **playbook for non-technical founders shipping real software with AI** — written by one. Curated by someone who has actually shipped products under these constraints, not someone watching from the outside.

Every entry on this list earns its spot one of two ways:

1. **I've used it personally** to ship something that exists in the world.
2. **A non-technical founder I trust** has shipped with it and vouches for it.

If a tool is trendy on X but doesn't actually help a solo non-technical builder ship a working product — it's not on this list. If a resource is technically impressive but assumes you already know what a `useEffect` is — it's not on this list.

**The bar is: would this help someone with no formal CS background ship a real product they could put in front of customers?** That's it.

> *Some links are affiliate links. They cost you nothing extra and help keep this list maintained.*

---

## What "vibe coding" means

> *Vibe coding* is shipping software by collaborating with AI as your co-developer — not by memorizing syntax, not by going to bootcamp, not by waiting for someone else to build it for you. You bring product instinct, taste, and persistence. The AI brings the syntax, the patterns, and the speed. Together you ship.

Vibe coding is not lazy. It's not "no-code." It's a real skill — and the people doing it well are shipping startups, products, and tools that compete with traditional dev teams.

This list is for them.

---

## 📖 Table of Contents

- [⚡ The Vibe Coder's Loop](#-the-vibe-coders-loop)
- [🛠️ Editors & Coding Agents](#️-editors--coding-agents)
- [🎨 UI & Design Tools](#-ui--design-tools)
- [🚀 Deployment & Hosting](#-deployment--hosting)
- [🗄️ Backends & Databases](#️-backends--databases)
- [🧱 Self-Hosted AI Infrastructure](#-self-hosted-ai-infrastructure)
- [⚡ Boilerplates & Starters](#-boilerplates--starters)
- [🧠 Prompt Patterns & Skills](#-prompt-patterns--skills)
- [🔁 Workflow Automation](#-workflow-automation)
- [📋 Knowledge OS & Second Brain](#-knowledge-os--second-brain)
- [📱 Mobile App Builders](#-mobile-app-builders)
- [💸 Payments & Auth](#-payments--auth)
- [📊 Analytics & Monitoring](#-analytics--monitoring)
- [📝 Content & Build-in-Public](#-content--build-in-public)
- [🎓 Learning Resources](#-learning-resources)
- [📚 Books & Long-form Reads](#-books--long-form-reads)
- [🎙️ Podcasts](#️-podcasts)
- [📺 YouTube Channels](#-youtube-channels)
- [👥 Communities](#-communities)
- [🏗️ Real Builds (Show, Don't Tell)](#️-real-builds-show-dont-tell)
- [💼 Founder Resources](#-founder-resources)
- [⚖️ Legal & Compliance](#️-legal--compliance)
- [🤝 Contributing](#-contributing)

---

## ⚡ The Vibe Coder's Loop

Most lists give you tools. Almost none tell you the actual workflow that ties them together. Here's the one I've shipped most of my work with — it's the same loop whether I'm building a prototype, a production feature, or a skill library.

```
1. CLAUDE CHAT  →  shape the idea, refine the concept, get it sharp
2. CLAUDE CHAT  →  generate a clean, structured prompt for what to build
3. COWORK       →  scaffold the project, create files, set up GitHub + Vercel
4. COWORK       →  generate the next set of build prompts for Claude Code
5. CLAUDE CODE  →  do the actual building, multi-file changes, run tests
6. COWORK       →  double-check what Code did, catch what got missed
7. → loop ←     →  next feature, same rhythm
```

The unlock isn't any single tool — it's that **each tool plays a role it's actually good at**, and you stop trying to make one tool do everything. Chat is for thinking. Cowork is for orchestration and verification. Code is for building.

You don't need a CS degree to run this loop. You need to know which tool to grab, in what order, for what step.

---

## 🛠️ Editors & Coding Agents

The actual surface where you write (or, more accurately, generate) code. This is the most important section of the list — get this wrong and nothing else matters.

- **[Claude Code](https://claude.com/claude-code)** — Terminal-based agentic coding tool from Anthropic. Reads your codebase, makes multi-file changes, runs tests, opens PRs. *This is my primary. I've shipped CEE, wunanddone, FounderOS, and most of Embra with it. If you're serious about building real software with AI, start here.*
- **[Claude (Chat)](https://claude.ai)** — Where I think and plan before I build. Concept refinement, prompt construction, architecture conversations. *I never start in Code; I always start in Chat.*
- **[Cowork](https://claude.ai/cowork)** — Anthropic's desktop tool for non-developers. The orchestration layer that ties Chat and Code together — scaffolds projects, sets up GitHub and Vercel through connectors, and double-checks what Code built. *This is the missing piece in most "AI coding" workflows.*
- **[Codex](https://chat.openai.com)** — OpenAI's coding agent. *I use this for smaller tasks or when I'm trying to conserve Claude usage. Solid for quick fixes, weaker than Claude Code for serious multi-file work.*
- **[v0 by Vercel](https://v0.dev)** — Generates UI components and full pages from prompts. *Best in class for getting a beautiful frontend fast — drop the output straight into Cursor or Claude Code from there.*
- **[Cursor](https://cursor.com)** — VS Code fork with deeply integrated AI. *I used this before Claude Code. Still excellent if you prefer working in an editor surface vs. a terminal.*
- **[Bolt.new](https://bolt.new)** — Browser-based AI builder. Type a prompt, get a working full-stack app, deploy in one click. *Good for prototypes; you'll outgrow it fast for anything serious.*
- **[Lovable](https://lovable.dev)** — Browser-based, opinionated stack. *Solid for landing pages and small apps. Same ceiling as Bolt.*
- **[Replit Agent](https://replit.com/agent)** — Cloud-based AI builder + hosting in one. *Approachable starting point if you don't want to install anything locally.*
- **[Windsurf](https://codeium.com/windsurf)** — Another AI-native editor with strong agentic capabilities. *Worth a look if Cursor isn't clicking for you.*

> 💡 **Honest take:** Once Claude Code and Cowork came out, I stopped using almost everything else. Pick a primary editor, get fluent, and stop tool-hopping. The compounding comes from depth, not breadth.

---

## 🎨 UI & Design Tools

You can vibe-code logic all day, but bad UI kills products. These help.

- **[v0 by Vercel](https://v0.dev)** — Worth listing twice. The fastest way to a beautiful frontend, period.
- **[shadcn/ui](https://ui.shadcn.com)** — Copy-paste component library that's become the default for serious AI-built apps. Beautiful, accessible, owned by you.
- **[Tailwind CSS](https://tailwindcss.com)** — The styling framework AI tools generate best for. Learn enough to read it.
- **[Figma](https://figma.com)** — When you need to design before you build. Free tier is enough.
- **[tweakcn](https://tweakcn.com)** — Theme editor for shadcn/ui. Get a polished look in 2 minutes instead of 2 days.
- **[Aceternity UI](https://ui.aceternity.com)** — Animated, modern components. Great for landing pages.
- **[Magic UI](https://magicui.design)** — Free animated UI components. Drop into shadcn projects.
- **[Lucide Icons](https://lucide.dev)** — Default icon library for most modern stacks. AI tools know it well.
- **[Radix UI](https://radix-ui.com)** — Accessible primitives that shadcn is built on top of.

---

## 🚀 Deployment & Hosting

Where your stuff actually lives on the internet.

- **[Vercel](https://vercel.com)** — The default for Next.js. Push to GitHub, it deploys. *I deploy everything here. The free tier carries you a long way.*
- **[Hostinger KVM VPS](https://hostinger.com/vps)** — When you need a real Linux server (self-hosted Ollama, n8n, Open WebUI). *I run a hybrid stack on this — local models for high-volume tasks, Claude API for strategic work. Not a typical pick for vibe coders, but if you want to control your costs and own your infra, it earns its spot.*
- **[Netlify](https://netlify.com)** — Vercel's biggest competitor. Slightly different feature set, equally solid.
- **[Railway](https://railway.app)** — Backends, databases, cron jobs, all one-click. Closest thing to "Vercel for backends."
- **[Fly.io](https://fly.io)** — When you need full control of a server. More technical but powerful.
- **[Cloudflare Pages](https://pages.cloudflare.com)** — Static sites, edge functions, generous free tier. Fast.

---

## 🗄️ Backends & Databases

The thing your app talks to to remember stuff.

- **[Supabase](https://supabase.com)** — Postgres + auth + storage + realtime + edge functions. *The backend default for vibe coders. I use this for almost every Embra product.*
- **[Firebase](https://firebase.google.com)** — Google's BaaS. *I've shipped with this — Devlog (Chrome extension) runs on Firebase. Great for mobile-first or realtime apps.*
- **[SpacetimeDB](https://spacetimedb.com)** — Realtime database with multiplayer-game-engine roots. *Unusual pick, but I built JARVIS (my personal AI OS) on top of this. If you're building anything realtime — collaborative tools, games, live dashboards — it's worth knowing about.*
- **[Convex](https://convex.dev)** — Realtime backend with TypeScript-first DX. Newer, well-loved.
- **[Neon](https://neon.tech)** — Serverless Postgres. Great for projects that scale to zero.
- **[Turso](https://turso.tech)** — Edge SQLite. Fast, cheap, simple.
- **[Upstash](https://upstash.com)** — Serverless Redis & Kafka. Good for caching and queues.

---

## 🧱 Self-Hosted AI Infrastructure

Most non-technical founders never explore this. They should.

If you're going to build with AI as your primary tool, eventually you'll want to control your costs, run high-volume tasks locally, and stop bleeding API budget on jobs that don't need a frontier model. This is the stack that makes that possible.

- **[Ollama](https://ollama.com)** — Run open-source LLMs locally with one command. *I route high-volume tasks (content scraping, classification, simple completions) here. Saves real money.*
- **[Open WebUI](https://openwebui.com)** — Self-hosted ChatGPT-like interface. Plug it into Ollama and you have your own private chat tool with no per-message cost.
- **[LiteLLM](https://litellm.ai)** — Universal API proxy. Lets you swap between Claude, GPT, Gemini, and local models with one interface. Critical for hybrid routing.
- **[n8n (self-hosted)](https://n8n.io)** — Run automation workflows on your own server. Full control, no per-task fees, integrates with everything.
- **[Hostinger KVM VPS](https://hostinger.com/vps)** — Where I host all of the above. Cheap, simple, enough horsepower for a hybrid local/cloud stack.

> 💡 **Honest take:** You don't need this on day one. But if you're spending $200+/month on AI APIs and most of those calls are repetitive, low-stakes tasks, this stack pays for itself in a month.

---

## ⚡ Boilerplates & Starters

Don't start from `npx create-next-app` if you can avoid it.

- **[T3 Stack](https://create.t3.gg)** — Next.js + TypeScript + Tailwind + tRPC + Prisma. Opinionated and excellent.
- **[Saas-Starter (Next.js)](https://github.com/leerob/next-saas-starter)** — Next.js + Stripe + Auth, by Vercel's Lee Rob.
- **[Supabase Starter](https://github.com/vercel/next.js/tree/canary/examples/with-supabase)** — Vercel's official Next.js + Supabase template.
- **[create-llama](https://github.com/run-llama/create-llama)** — Scaffold an AI app fast.
- **[Nextra](https://nextra.site)** — Documentation site starter. Great for launching landing pages or docs fast.

---

## 🧠 Prompt Patterns & Skills

How you talk to the AI matters as much as the AI itself.

- **[Anthropic's Prompt Engineering Guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview)** — Read this. All of it.
- **[Claude Code Skills](https://docs.claude.com/en/docs/claude-code/skills)** — Reusable workflow definitions. *The single biggest unlock for serious vibe coding. Write a skill once, reuse it across every project. I have skills for content generation, investor outreach, build logs, and a dozen other things — they save hours every week.*
- **[OpenAI Cookbook](https://github.com/openai/openai-cookbook)** — Practical prompt examples and patterns.
- **[Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)** — Massive prompt library. Inspiration source.
- **[Made Without Instructions](https://medium.com/@byeadro)** — *My ongoing essays on the craft of building with AI as a non-technical founder. Bias warning: this is mine.*

### Patterns I use constantly

- **Bible-first development** — Define every architectural rule in a `bible/` folder before writing code. Each task references the bible section it implements. Codebase implements the bible; the bible doesn't describe the codebase. *Used this on CEE — 1,531 tests later, no architectural drift.*
- **Halt-and-resolve** — Before writing code, surface every halt (every unclear decision, every assumption). Resolve each halt against a bible-grounded rationale. Then implement. *Forces you to think before you generate.*
- **Three-tool loop** — Chat for thinking, Cowork for orchestration, Code for building. Each tool plays its role; you stop trying to force one tool to do everything.

---

## 🔁 Workflow Automation

For when "this should run while I sleep."

- **[n8n](https://n8n.io)** — Self-hostable workflow automation. *I run everything here — investor outreach (55+ personalized cold emails), content distribution, daily news digests. Self-hosted on my Hostinger VPS for full control. Genuinely the most leveraged tool in my stack after Claude Code.*
- **[Zapier](https://zapier.com)** — The OG. Easy, expensive at scale.
- **[Make](https://make.com)** — Zapier alternative, more visual, more powerful for complex flows.
- **[Pipedream](https://pipedream.com)** — Code-friendly automation. Great if you want to drop in JavaScript when needed.
- **[Trigger.dev](https://trigger.dev)** — Background jobs and workflows in your code, not in a separate tool.

---

## 📋 Knowledge OS & Second Brain

Most non-technical founders are drowning in their own ideas. Fix that here.

- **[Notion](https://notion.so)** — *Where I plan, draft, and run my businesses. I have a Content Writing Dashboard, an Investor Intelligence DB tracking every conversation, a Claw Command Center for daily focus, and dedicated databases for every active project. The Notion stack is half my operating system.*
- **[Obsidian](https://obsidian.md)** — *My second brain — a vault called `~/SecondBrain` with a 00–08 folder structure. Plain markdown files I own forever, regardless of what app I use to view them. Pairs perfectly with Claude Code (which can read your vault directly).*
- **[Heptabase](https://heptabase.com)** — Visual whiteboard meets card-based note-taking. Great for thinking through complex problems.
- **[Tana](https://tana.inc)** — Outliner with structured fields. Powerful but steeper curve.
- **[Logseq](https://logseq.com)** — Open-source Obsidian alternative.

---

## 📱 Mobile App Builders

Shipping native iOS/Android without becoming an iOS/Android dev.

- **[Claude Code + Xcode](https://docs.claude.com/en/docs/claude-code)** — *Yes, you can vibe-code native iOS apps in Swift. I shipped Embra Signal to the App Store this way. Don't let "I don't know Swift" stop you.*
- **[Expo](https://expo.dev)** — React Native made human. Most AI tools generate Expo-flavored RN well.
- **[FlutterFlow](https://flutterflow.io)** — Visual builder for Flutter apps. Lower ceiling but very fast.

---

## 💸 Payments & Auth

The two things every real product needs.

- **[Stripe](https://stripe.com)** — The default. Excellent docs. AI tools generate Stripe code well.
- **[Lemon Squeezy](https://lemonsqueezy.com)** — Stripe alternative that handles tax/VAT for you. Worth it for indie hackers.
- **[Clerk](https://clerk.com)** — Auth-as-a-service. The fastest way to a production-grade login system.
- **[Auth.js (NextAuth)](https://authjs.dev)** — Open-source auth for Next.js. Free, battle-tested.
- **[Supabase Auth](https://supabase.com/auth)** — If you're already on Supabase, you're already authed.

---

## 📊 Analytics & Monitoring

Knowing if anyone is using your thing and what's broken.

- **[PostHog](https://posthog.com)** — Product analytics + session replay + feature flags. Generous free tier.
- **[Plausible](https://plausible.io)** — Privacy-friendly Google Analytics replacement. Simple.
- **[Vercel Analytics](https://vercel.com/analytics)** — Built into Vercel. Just turn it on.
- **[Sentry](https://sentry.io)** — Error tracking. Catch bugs in production before users complain.
- **[Logsnag](https://logsnag.com)** — Slack-like notifications for product events. Great for early-stage.

---

## 📝 Content & Build-in-Public

Shipping the *story* of what you built matters as much as the build itself.

- **[Substack](https://substack.com)** — Where the building-in-public crowd writes.
- **[Medium](https://medium.com)** — Older audience, still gets traffic.
- **[Hashnode](https://hashnode.com)** — Developer-focused blogging. Free custom domain.
- **[Beehiiv](https://beehiiv.com)** — Newsletter platform. More creator-friendly than Substack on monetization.

---

## 🎓 Learning Resources

For when you need to actually learn the thing, not just generate it.

- **[The Odin Project](https://theodinproject.com)** — Free, comprehensive web dev curriculum. Worth it.
- **[freeCodeCamp](https://freecodecamp.org)** — Same idea, different format.
- **[Frontend Masters](https://frontendmasters.com)** — Paid but excellent.
- **[Roadmap.sh](https://roadmap.sh)** — Visual learning paths for any role.

---

## 📚 Books & Long-form Reads

When you want depth, not a 280-character take.

- **["The Mom Test" by Rob Fitzpatrick](https://www.momtestbook.com)** — How to talk to users without lying to yourself. Essential.
- **["The Lean Startup" by Eric Ries](http://theleanstartup.com)** — The ship-fast-learn-faster bible.
- **["Hackers & Painters" by Paul Graham](http://paulgraham.com/hp.html)** — Why building things still matters.
- **["Atomic Habits" by James Clear](https://jamesclear.com/atomic-habits)** — Shipping is a habit before it's an outcome.
- **["The Four Burners Theory"](https://medium.com/@byeadro)** — *My in-progress book on what to focus on as a solo operator with too many ambitions. ~55,000 word draft live.*

---

## 🎙️ Podcasts

For the commute, the gym, the long walk.

- **[Lenny's Podcast](https://www.lennysnewsletter.com)** — Product strategy. Best in class.
- **[Latent Space](https://www.latent.space)** — AI engineering podcast.
- **[The Twenty Minute VC](https://www.thetwentyminutevc.com)** — If you're fundraising or thinking about it.
- **[Acquired](https://www.acquired.fm)** — Long, deep company stories. Pure inspiration fuel.

---

## 📺 YouTube Channels

- **[Theo - t3.gg](https://youtube.com/@t3dotgg)** — Modern stack opinions and builds.
- **[Fireship](https://youtube.com/@fireship)** — 100-second explainers.
- **[Web Dev Cody](https://youtube.com/@WebDevCody)** — Real-world full-stack builds.
- **[Greg Isenberg](https://youtube.com/@gregisenberg)** — Startup ideas and indie founder energy.

---

## 👥 Communities

Where the actual builders hang out.

- **[Indie Hackers](https://indiehackers.com)** — Forum + community for indie builders.
- **[r/SideProject](https://reddit.com/r/SideProject)** — Reddit. People share what they're building.
- **[r/SaaS](https://reddit.com/r/SaaS)** — SaaS-focused.
- **[Y Combinator Startup School](https://startupschool.org)** — Free, online, excellent.
- **[Build in Public on X](https://twitter.com/search?q=%23buildinpublic)** — The hashtag where the daily building happens.

---

## 💼 Founder Resources

For the operator side of the equation.

- **[YC Startup School](https://startupschool.org)** — Free curriculum. Genuinely excellent.
- **[Stripe Atlas](https://stripe.com/atlas)** — Incorporate a US company in days.
- **[Mercury](https://mercury.com)** — Banking for startups. The default.
- **[Pilot](https://pilot.com)** — Bookkeeping. Automated.
- **[Notion for Startups](https://notion.so/startups)** — Free credits if you qualify.
- **[NVIDIA Inception](https://nvidia.com/inception)** — Free credits, support, and visibility for AI-focused startups. *Embra is a member.*

---

## ⚖️ Legal & Compliance

Boring but the difference between "real company" and "guy who got sued."

- **[Stripe Atlas Legal Templates](https://stripe.com/atlas)** — Free, lawyer-reviewed templates.
- **[Termly](https://termly.io)** — Privacy policies and ToS for early-stage products.
- **[Cooley GO](https://cooleygo.com)** — Free legal docs from a real startup law firm.
- **[Founder's Workbench](https://www.foundersworkbench.com)** — Goodwin's free document generator.

---

## 🤝 Contributing

This list is alive. It only stays useful if real builders keep adding what's working for them.

**To add an entry:**

1. Read [CONTRIBUTING.md](CONTRIBUTING.md)
2. Open a PR
3. Make sure your entry meets the bar: *would this help a non-technical founder ship a real product?*

We don't accept entries based on hype, sponsorship, or follower counts. We accept entries based on whether the thing actually works for the audience this list is for.

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=byeadro/awesome-vibe-coding&type=Date)](https://star-history.com/#byeadro/awesome-vibe-coding&Date)

---

## ✍️ About the Curator

Maintained by [@byeadro](https://github.com/byeadro) — non-technical solo founder, vibe coder, and writer behind [Made Without Instructions](https://medium.com/@byeadro). I'm building [Embra](https://embra.app) (B2B EdTech/LegalTech, NVIDIA Inception, SPARK Accelerator), [CEE](https://github.com/byeadro/cee), and a bunch of other things — all with AI as my co-developer.

If this list is useful to you:

- ⭐ Star the repo
- 🔁 Share it with another non-technical founder
- 📬 Subscribe to [MWI](https://medium.com/@byeadro)
- 🐦 Follow [me on X](https://twitter.com/byeadro)

---

## License

[CC0-1.0](LICENSE) — Public domain. Take it, fork it, remix it.

<div align="center">

### Built without instructions.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F7DF1E,40:7C3AED,100:0D1117&height=120&section=footer" />

</div>
