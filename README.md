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

---

## What "vibe coding" means

> *Vibe coding* is shipping software by collaborating with AI as your co-developer — not by memorizing syntax, not by going to bootcamp, not by waiting for someone else to build it for you. You bring product instinct, taste, and persistence. The AI brings the syntax, the patterns, and the speed. Together you ship.

Vibe coding is not lazy. It's not "no-code." It's a real skill — and the people doing it well are shipping startups, products, and tools that compete with traditional dev teams.

This list is for them.

---

## 📖 Table of Contents

- [🛠️ Editors & Coding Agents](#️-editors--coding-agents)
- [🎨 UI & Design Tools](#-ui--design-tools)
- [🚀 Deployment & Hosting](#-deployment--hosting)
- [🗄️ Backends & Databases](#️-backends--databases)
- [⚡ Boilerplates & Starters](#-boilerplates--starters)
- [🧠 Prompt Patterns & Skills](#-prompt-patterns--skills)
- [🔁 Workflow Automation](#-workflow-automation)
- [📱 Mobile App Builders](#-mobile-app-builders)
- [💸 Payments & Auth](#-payments--auth)
- [📊 Analytics & Monitoring](#-analytics--monitoring)
- [📝 Content & Writing Tools](#-content--writing-tools)
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

## 🛠️ Editors & Coding Agents

The actual surface where you write (or, more accurately, generate) code.

- **[Claude Code](https://claude.com/claude-code)** — Terminal-based agentic coding tool from Anthropic. The current state of the art for serious solo building. Reads your codebase, makes multi-file changes, runs tests, opens PRs. *This is what most of us in here use.*
- **[Cursor](https://cursor.com)** — VS Code fork with deeply integrated AI. Excellent for real-time pair programming with AI in a familiar editor.
- **[Windsurf](https://codeium.com/windsurf)** — Another AI-native editor with strong agentic capabilities.
- **[GitHub Copilot](https://github.com/features/copilot)** — The OG. Now has agentic mode. Generally weaker than Claude Code or Cursor for non-technical builders.
- **[v0 by Vercel](https://v0.dev)** — Generates UI components and full pages from prompts. Best in class for getting a beautiful frontend fast.
- **[Bolt.new](https://bolt.new)** — Browser-based AI builder. Type a prompt, get a working full-stack app, deploy in one click. Great for prototypes.
- **[Lovable](https://lovable.dev)** — Similar to Bolt, browser-based, opinionated stack. Solid for landing pages and simple apps.
- **[Replit Agent](https://replit.com/agent)** — Cloud-based AI builder + hosting in one. Lower ceiling than Claude Code but very approachable.

---

## 🎨 UI & Design Tools

You can vibe-code logic all day, but bad UI kills products. These help.

- **[v0 by Vercel](https://v0.dev)** — Worth listing twice. The fastest way to a beautiful frontend.
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

- **[Vercel](https://vercel.com)** — The default for Next.js. Push to GitHub, it deploys. Generous free tier.
- **[Netlify](https://netlify.com)** — Vercel's biggest competitor. Slightly different feature set, equally solid.
- **[Railway](https://railway.app)** — Backends, databases, cron jobs, all one-click. Closest thing to "Vercel for backends."
- **[Fly.io](https://fly.io)** — When you need full control of a server. More technical but powerful.
- **[Cloudflare Pages](https://pages.cloudflare.com)** — Static sites, edge functions, generous free tier. Fast.
- **[Render](https://render.com)** — Heroku replacement. Easy deploys for full-stack apps and databases.

---

## 🗄️ Backends & Databases

The thing your app talks to to remember stuff.

- **[Supabase](https://supabase.com)** — Postgres + auth + storage + realtime + edge functions. The backend default for vibe coders. Generous free tier.
- **[Firebase](https://firebase.google.com)** — Google's BaaS. Great for mobile-first or realtime apps.
- **[Convex](https://convex.dev)** — Realtime backend with TypeScript-first DX. Newer, well-loved.
- **[Neon](https://neon.tech)** — Serverless Postgres. Great for projects that scale to zero.
- **[Turso](https://turso.tech)** — Edge SQLite. Fast, cheap, simple.
- **[PlanetScale](https://planetscale.com)** — Serverless MySQL with branching workflows.
- **[Upstash](https://upstash.com)** — Serverless Redis & Kafka. Good for caching and queues.

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
- **[Claude Code Skills](https://docs.claude.com/en/docs/claude-code/skills)** — Reusable workflow definitions. The single biggest unlock for serious vibe coding. Write once, reuse forever.
- **[OpenAI Cookbook](https://github.com/openai/openai-cookbook)** — Practical prompt examples and patterns.
- **[Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)** — Massive prompt library. Inspiration source.
- **["Vibe Coding": A Builder's Guide](https://medium.com/@byeadro)** — Long-form essays on the craft of building software with AI.

---

## 🔁 Workflow Automation

For when "this should run while I sleep."

- **[n8n](https://n8n.io)** — Self-hostable workflow automation. Like Zapier but you own it.
- **[Zapier](https://zapier.com)** — The OG. Easy, expensive at scale.
- **[Make](https://make.com)** — Zapier alternative, more visual, more powerful for complex flows.
- **[Pipedream](https://pipedream.com)** — Code-friendly automation. Great if you want to drop in JavaScript when needed.
- **[Trigger.dev](https://trigger.dev)** — Background jobs and workflows in your code, not in a separate tool.

---

## 📱 Mobile App Builders

Shipping native iOS/Android without becoming an iOS/Android dev.

- **[Expo](https://expo.dev)** — React Native made human. Most AI tools generate Expo-flavored RN well.
- **[Claude Code + Xcode](https://github.com/byeadro/awesome-vibe-coding)** — Yes, you can vibe-code native iOS apps in Swift. Several of us here have shipped to the App Store this way.
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

## 📝 Content & Writing Tools

For shipping the *story* of what you built.

- **[Substack](https://substack.com)** — Where the building-in-public crowd writes.
- **[Medium](https://medium.com)** — Older audience, still gets traffic.
- **[Hashnode](https://hashnode.com)** — Developer-focused blogging. Free custom domain.
- **[Beehiiv](https://beehiiv.com)** — Newsletter platform. More creator-friendly than Substack on monetization.
- **[Notion](https://notion.so)** — Where most of us plan and draft.

---

## 🎓 Learning Resources

For when you need to actually learn the thing, not just generate it.

- **[The Odin Project](https://theodinproject.com)** — Free, comprehensive web dev curriculum. Worth it.
- **[freeCodeCamp](https://freecodecamp.org)** — Same idea, different format.
- **[Frontend Masters](https://frontendmasters.com)** — Paid but excellent. The deep-dive courses are worth it.
- **[YouTube: Theo - t3.gg](https://youtube.com/@t3dotgg)** — Modern web dev opinions, hot takes, real builds.
- **[YouTube: Fireship](https://youtube.com/@fireship)** — 100-second explainers on every topic.
- **[Roadmap.sh](https://roadmap.sh)** — Visual learning paths for any role.

---

## 📚 Books & Long-form Reads

When you want depth, not a 280-character take.

- **["The Mom Test" by Rob Fitzpatrick](https://www.momtestbook.com)** — How to talk to users without lying to yourself. Essential.
- **["The Lean Startup" by Eric Ries](http://theleanstartup.com)** — The ship-fast-learn-faster bible.
- **["Hackers & Painters" by Paul Graham](http://paulgraham.com/hp.html)** — Why building things still matters.
- **["Atomic Habits" by James Clear](https://jamesclear.com/atomic-habits)** — Shipping is a habit before it's an outcome.

---

## 🎙️ Podcasts

For the commute, the gym, the long walk.

- **[Lenny's Podcast](https://www.lennysnewsletter.com)** — Product strategy. Best in class.
- **[Latent Space](https://www.latent.space)** — AI engineering podcast. Get smart on what's actually possible.
- **[The Twenty Minute VC](https://www.thetwentyminutevc.com)** — If you're fundraising or thinking about it.
- **[Acquired](https://www.acquired.fm)** — Long, deep company stories. Pure inspiration fuel.

---

## 📺 YouTube Channels

- **[Theo - t3.gg](https://youtube.com/@t3dotgg)** — Modern stack opinions and builds.
- **[Fireship](https://youtube.com/@fireship)** — Fast, fun, technical.
- **[Web Dev Cody](https://youtube.com/@WebDevCody)** — Real-world full-stack builds.
- **[Greg Isenberg](https://youtube.com/@gregisenberg)** — Startup ideas and indie founder energy.

---

## 👥 Communities

Where the actual builders hang out.

- **[Indie Hackers](https://indiehackers.com)** — Forum + community for indie builders.
- **[r/SideProject](https://reddit.com/r/SideProject)** — Reddit. People share what they're building.
- **[r/SaaS](https://reddit.com/r/SaaS)** — Reddit. SaaS-focused.
- **[Y Combinator Startup School](https://startupschool.org)** — Free, online, excellent.
- **[Build in Public on X](https://twitter.com/search?q=%23buildinpublic)** — The hashtag where the daily building happens.

---

## 🏗️ Real Builds (Show, Don't Tell)

Public repos by non-technical founders who've actually shipped real things with AI. Proof that this works.

> *Have a real build to add? [Open a PR](CONTRIBUTING.md). The bar: it shipped, you (or someone like you) built it, AI was the primary collaborator.*

- **[byeadro/cee](https://github.com/byeadro/cee)** — Claude Execution Engine. A deterministic Python pipeline for prompt construction. 1,531 tests. Built by a non-technical solo founder using Claude Code.
- **[byeadro/wunanddone](https://github.com/byeadro/wunanddone)** — $1/month single-task web app. Live and deployed.
- *Add yours →*

---

## 💼 Founder Resources

For the operator side of the equation.

- **[YC Startup School](https://startupschool.org)** — Free curriculum. Genuinely excellent.
- **[Stripe Atlas](https://stripe.com/atlas)** — Incorporate a US company in days.
- **[Mercury](https://mercury.com)** — Banking for startups. The default.
- **[Pilot](https://pilot.com)** — Bookkeeping. Automated.
- **[Notion for Startups](https://notion.so/startups)** — Free credits if you qualify.

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

## ✍️ About the Curator

Maintained by [@byeadro](https://github.com/byeadro) — non-technical solo founder, vibe coder, and writer behind [Made Without Instructions](https://medium.com/@byeadro). I'm building [Embra](https://embra.app) (B2B EdTech/LegalTech), [CEE](https://github.com/byeadro/cee), and a bunch of other things — all with AI as my co-developer.

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
