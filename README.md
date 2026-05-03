<div align="center">



<!-- Animated typing effect badge row -->
<a href="https://github.com/Grexlabs/free-domain-hosting/stargazers"><img src="https://img.shields.io/github/stars/Grexlabs/free-domain-hosting?style=for-the-badge&logo=github&color=f7df1e&labelColor=1a1a2e" alt="Stars"/></a>
<a href="https://github.com/Grexlabs/free-domain-hosting/network"><img src="https://img.shields.io/github/forks/Grexlabs/free-domain-hosting?style=for-the-badge&logo=github&color=0099ff&labelColor=1a1a2e" alt="Forks"/></a>
<a href="https://github.com/Grexlabs/free-domain-hosting/pulls"><img src="https://img.shields.io/badge/PRs-welcome-00c851?style=for-the-badge&logo=git&labelColor=1a1a2e" alt="PRs Welcome"/></a>
<a href="#"><img src="https://img.shields.io/badge/Last%20Verified-May%202026-ff6b6b?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=1a1a2e" alt="Verified"/></a>
<img src="https://img.shields.io/badge/100%25%20FREE-No%20Credit%20Card-00d2ff?style=for-the-badge&logo=heart&logoColor=white&labelColor=1a1a2e" alt="Free"/>

<br/><br/>



![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

</div>

<br/>

<div align="center">

### 📊 At a Glance

| 🌍 Free Subdomains<br>& Dynamic DNS | ⚡ Developer<br>PaaS & Hosting | 📦 Classic PHP<br>& MySQL | 💯 100% Free<br>No Catch | 🌐 HTML<br>Static Hosting | 🖥️ Free VPS<br>& Cloud | 🎓 Special<br>Dev Domains | 📧 Free Email<br>& Extras |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **40+** | **30+** | **20+** | **15+** | **12+** | **10+** | **8+** | **10+** |

</div>

<br/>

---

## 📋 Table of Contents

<details open>
<summary><strong>🗂️ Click to expand full index</strong></summary>

- [🪄 How to Use This List](#-how-to-use-this-list)
- [🧑‍💻 **is-a.dev** — Complete Step-by-Step Guide](#-is-adev--complete-claiming-guide)
- [🌍 Free Subdomains & Dynamic DNS (40+ Providers)](#-free-subdomains--dynamic-dns-40-providers)
- [⚡ Developer Hosting & PaaS (30+ Platforms)](#-developer-hosting--paas-30-platforms)
- [📦 Classic PHP Hosting (20+ Providers)](#-classic--php-hosting-20-providers)
- [💯 100% Completely Free Hosting — No Catch](#-100-completely-free-hosting-no-catch)
- [🌐 Free HTML Hosting (No Expiry)](#-free-html-hosting-no-expiry)
- [🖥️ Free VPS & Cloud Compute](#️-free-vps--cloud-compute)
- [🎓 Special Developer Domains (js.org, eu.org, etc.)](#-special-developer-domain-registries)
- [📧 Free Email & Extras](#-free-email-forwarding--extras)
- [🧠 Best Picks by Use Case](#-best-picks--by-use-case)
- [📌 Pro Tips & Reality Check](#-pro-tips--reality-check)
- [🤝 Contribute & Support](#-contribute--support)

</details>

<br/>

---

## 🪄 How to Use This List

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│  Step 1 → Choose your use case (subdomain / app / PHP / HTML)   │
│  Step 2 → Click any provider link — all verified May 2026       │
│  Step 3 → Mix & match for a full free stack                     │
│                                                                 │
│  Example Free Full-Stack:                                       │
│  DuckDNS + Cloudflare Pages + Supabase + Heliohost             │
│  = Domain + Frontend + DB + Backend  →  $0 / month ✅          │
└─────────────────────────────────────────────────────────────────┘
```

</div>

| Step | Action | Time |
|:----:|--------|:----:|
| **1** | Pick your use-case category from the table above | 10s |
| **2** | Click the provider link — read the full details row | 30s |
| **3** | Sign up (most require only an email, no credit card) | 2 min |
| **4** | Deploy your site or claim your domain | 5 min |
| **5** | Point Cloudflare DNS for free CDN + HTTPS | 10 min |

<br/>

---

## 🧑‍💻 is-a.dev — Complete Claiming Guide

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00D2FF&center=true&vCenter=true&width=600&lines=Get+yourname.is-a.dev+completely+free!;Perfect+for+developer+portfolios+%26+projects;Powered+by+GitHub+Pull+Requests;CNAME%2C+A%2C+AAAA%2C+TXT+records+supported" alt="is-a.dev typing"/>

</div>

**What is is-a.dev?**
[is-a.dev](https://is-a.dev) is a free subdomain service exclusively for **developers**. You get `yourname.is-a.dev` pointing to any hosting provider — GitHub Pages, Vercel, Netlify, Cloudflare Pages, or your own server. It's community-maintained and 100% free forever.

**Supported DNS Records:** `A` · `AAAA` · `CNAME` · `MX` · `TXT` · `NS` · `CAA` · `DS`

---

### 📋 Step-by-Step: Claim Your `yourname.is-a.dev` Domain

#### Step 1 — Fork the Repository

```
https://github.com/is-a-dev/register
```

Go to the repo → Click **Fork** (top right) → Fork to your GitHub account.

---

#### Step 2 — Create Your JSON File

Inside the fork, navigate to the **`domains/`** folder and create a new file:

```
domains/yourname.json
```

> Replace `yourname` with your desired subdomain. Lowercase only, hyphens allowed, no spaces.

---

#### Step 3 — Fill in the JSON

**Option A — Point to GitHub Pages:**
```json
{
  "description": "My developer portfolio",
  "repo": "https://github.com/yourusername/your-repo",
  "owner": {
    "username": "yourusername",
    "email": "you@example.com"
  },
  "record": {
    "CNAME": "yourusername.github.io"
  }
}
```

**Option B — Point to Vercel:**
```json
{
  "description": "My Next.js app",
  "repo": "https://github.com/yourusername/your-repo",
  "owner": {
    "username": "yourusername",
    "email": "you@example.com"
  },
  "record": {
    "CNAME": "cname.vercel-dns.com"
  }
}
```

**Option C — Point to a custom IP (A record):**
```json
{
  "description": "My VPS server",
  "repo": "https://github.com/yourusername/your-site",
  "owner": {
    "username": "yourusername",
    "email": "you@example.com"
  },
  "record": {
    "A": ["1.2.3.4"]
  }
}
```

**Option D — Point to Netlify:**
```json
{
  "description": "My Netlify site",
  "repo": "https://github.com/yourusername/your-repo",
  "owner": {
    "username": "yourusername",
    "email": "you@example.com"
  },
  "record": {
    "CNAME": "yoursite.netlify.app"
  }
}
```

**Option E — Point to Cloudflare Pages:**
```json
{
  "description": "My Cloudflare Pages project",
  "repo": "https://github.com/yourusername/your-repo",
  "owner": {
    "username": "yourusername",
    "email": "you@example.com"
  },
  "record": {
    "CNAME": "yourproject.pages.dev"
  }
}
```

---

#### Step 4 — Open a Pull Request

1. Commit your JSON file to your fork
2. Go to the original repo: `github.com/is-a-dev/register`
3. Click **"Compare & pull request"**
4. Title it: `feat: add yourname.is-a.dev`
5. Fill in the PR description template (GitHub auto-fills it)
6. Submit the PR

---

#### Step 5 — Wait for Approval

| Stage | Time | Details |
|-------|------|---------|
| 🤖 CI checks | ~2 min | Automated JSON linting & validation |
| 👀 Review | 1–7 days | Community maintainers review the PR |
| ✅ Merged | Instant | DNS propagates within 1–5 minutes |

---

#### Step 6 — Configure Your Hosting Provider

After the PR is merged, add the custom domain in your hosting panel:

**GitHub Pages:** `Settings → Pages → Custom domain → yourname.is-a.dev`

**Vercel:** `Project → Settings → Domains → Add → yourname.is-a.dev`

**Netlify:** `Site Settings → Domain Management → Add domain → yourname.is-a.dev`

**Cloudflare Pages:** `Custom domains → Set up a custom domain → yourname.is-a.dev`

---

#### ✅ Rules & Requirements

| Rule | Details |
|------|---------|
| 🧑‍💻 **Developers only** | Must have an active GitHub account with real projects |
| 📁 **Active repo required** | The `repo` field must link to a real, public repository |
| 🚫 **No commercial use** | Personal projects, portfolios, OSS tools only |
| 🔤 **Lowercase only** | Letters, numbers, hyphens. No dots or underscores |
| 🔒 **HTTPS recommended** | Use Let's Encrypt or your host's free SSL |
| 1️⃣ **One subdomain per person** | One domain per GitHub account (exceptions for OSS) |

---

#### 💡 Popular Use Cases for is-a.dev

```
yourname.is-a.dev          → Personal portfolio
api.yourname.is-a.dev      → Not supported (apex only)
yourname.is-a.dev          → Open source project landing page
yourname.is-a.dev          → Dev blog
yourname.is-a.dev          → SaaS MVP
```

> **Note:** Wildcards (`*.yourname.is-a.dev`) are generally not supported. Each subdomain needs its own JSON file.

<br/>

---

## 🌍 Free Subdomains & Dynamic DNS (40+ Providers)

> Get a permanent `yourname.provider.com` for home servers, IoT, projects, and dev tools.

<details open>
<summary><strong>🔽 View all 40+ providers</strong></summary>

| # | Provider | Free Domain Example | Update Method | Special Features | Limits |
|---|----------|---------------------|---------------|-----------------|--------|
| 1 | [**DuckDNS**](https://duckdns.org) 🦆 | `yourname.duckdns.org` | Cron/curl script | Simplest DDNS ever | Unlimited subdomains |
| 2 | [**Dynv6**](https://dynv6.com) | `yourname.dynv6.net` | REST API | IPv6-first support | 3 zones free |
| 3 | [**FreeDNS (Afraid.org)**](https://freedns.afraid.org) | `yourname.mooo.com` + 100s more | Web / client | Huge shared domain library | Unlimited |
| 4 | [**No-IP**](https://noip.com) | `yourname.no-ip.org` | Desktop client | Most popular DDNS | 30-day confirmation |
| 5 | [**ClouDNS**](https://cloudns.net) ☁️ | `yourname.cloudns.be` | API / GUI | GeoDNS, DNSSEC | 1 free zone, 50 records |
| 6 | [**Dynu**](https://dynu.com) | `yourname.dynu.com` | Email / Client | + Free email forwarding | Unlimited hosts |
| 7 | [**ChangeIP**](https://changeip.com) | `yourname.changeip.net` | Client app | Live DNS push | 5 hosts free |
| 8 | [**IPv64**](https://ipv64.net) | `yourname.ipv64.net` | HTTP GET | IPv6-first, REST | Unlimited |
| 9 | [**dns.he.net**](https://dns.he.net) | Bring your own domain | IPv6 tunnel | Free full DNS hosting | Unlimited zones |
| 10 | [**nsupdate.info**](https://nsupdate.info) | `yourname.nsupdate.info` | API / RFC 2136 | Open source platform | Unlimited |
| 11 | [**FreeDomain.one**](https://freedomain.one) | `yourname.freedomain.one` | Web panel | New 2025 provider | Free forever |
| 12 | [**Mydns.bz**](https://www.mydns.bz) | `yourname.jp / .net / .asia` | POP3 / HTTP | Dynamic multi-TLD DDNS | Unlimited |
| 13 | [**Nxtdev**](https://nxtdev.xyz) | `yourname.nxtdev.xyz` | REST API | <1s sync via Cloudflare Edge | Unlimited |
| 14 | [**Open Domains**](https://open-domains.net) | `*.is-cool.dev`, `*.is-local.org` | GitHub PR | DNSSEC, full SSL/TLS | Free forever |
| 15 | [**is-a.dev**](https://is-a.dev) 🧑‍💻 | `yourname.is-a.dev` | GitHub PR | CNAME / A / AAAA / TXT | Devs only |
| 16 | [**js.org**](https://js.org) | `yourname.js.org` | GitHub PR | JavaScript projects only | Free forever |
| 17 | [**eu.org**](https://nic.eu.org) | `yourname.eu.org` | Web form | Free second-level domain! | Manual review |
| 18 | [**US.KG**](https://register.us.kg) | `yourname.us.kg` | GitHub auth | Lifetime extension | Free |
| 19 | [**Cloudflare DNS**](https://cloudflare.com) ☁️ | Bring your own domain | Web / API | Free CDN + DDoS protect | Unlimited records |
| 20 | [**Domains Project**](https://github.com/domainsproject/register) | Various community domains | GitHub PR | 100% community-run | Free |
| 21 | [**Kevin Service Registry**](https://github.com/KevvTheGoat/Kevin-Service-Registry) | Community subdomains | GitHub PR | Non-commercial use | Free |
| 22 | [**FreeSubdomains**](https://github.com/rdwz/freesubdoma.in) | 24+ subdomain options | Web / GitHub | Directory aggregator | Free |
| 23 | [**serv00.com**](https://www.serv00.com) ✨ | `yourname.serv00.net` | DevilWEB Panel | 3 GB SSD, unlimited transfer | SSH + 10 DBs |
| 24 | [**freedns.zone**](https://freedns.zone) | `yourname.freedns.zone` | Web | Classic provider | Free |
| 25 | [**PointDNS**](https://pointhq.com) | Bring your own domain | Web GUI | Easy management | 2 zones free |
| 26 | [**myownip.net**](https://myownip.net) | `yourname.myownip.net` | Dynamic client | Minimalist DDNS | Free |
| 27 | [**Afraid.org shared**](https://freedns.afraid.org) | 1000+ shared domain pool | API / Web | Huge community zones | Unlimited hosts |
| 28 | [**cloudns.ph**](https://www.cloudns.net/free-subdomain/) | `yourname.cloudns.ph` | Web GUI | 1 subdomain, 50 records | Free tier |
| 29 | [**is-a-good.dev**](https://github.com/is-a-good-dev/register) | `yourname.is-a-good.dev` | GitHub PR | Similar to is-a.dev | Devs only |
| 30 | [**under.jp**](https://under.jp) | `yourname.under.jp` | Web | Japanese DDNS service | Free |
| 31 | [**cluster.ws**](https://cluster.ws) | `yourname.cluster.ws` | Web panel | Legacy free DDNS | Free |
| 32 | [**is-local.org**](https://is-local.org) | `yourname.is-local.org` | GitHub PR | For local dev projects | Free |
| 33 | [**localto.net**](https://localto.net) | Tunnel URLs | CLI | Ngrok alternative | Free tier |
| 34 | [**is-a-fullstack.dev**](https://github.com/is-a-fullstack-dev/register) | `yourname.is-a-fullstack.dev` | GitHub PR | Full-stack devs | Free |
| 35 | [**wip.la**](https://wip.la) | `yourname.wip.la` | GitHub PR | Work-in-progress projects | Free |
| 36 | [**koyeb.app**](https://koyeb.com) | `yourname.koyeb.app` | Auto with deploy | Included with Koyeb hosting | Free |
| 37 | [**fly.dev**](https://fly.io) | `yourname.fly.dev` | Auto with deploy | Included with Fly.io | Free |
| 38 | [**vercel.app**](https://vercel.com) | `yourproject.vercel.app` | Auto with deploy | Best CDN performance | Free |
| 39 | [**netlify.app**](https://netlify.com) | `yourproject.netlify.app` | Auto with deploy | Instant deploy subdomain | Free |
| 40 | [**pages.dev**](https://pages.cloudflare.com) | `yourproject.pages.dev` | Auto with deploy | Cloudflare edge network | Free |

</details>

> 💡 **Pro Tip:** `DuckDNS` + `Cloudflare DNS` = free DDNS with CDN & DDoS protection on any domain.

<br/>

---

## ⚡ Developer Hosting & PaaS (30+ Platforms)

> Optimized for Jamstack, serverless, containers, and modern web apps.

<details open>
<summary><strong>🔽 View all 30+ platforms</strong></summary>

| # | Platform | Free Tier | Languages / Stack | Auto Deploy | Sleep? | Notes |
|---|----------|-----------|-------------------|:-----------:|:------:|-------|
| 1 | [**Vercel**](https://vercel.com) ▲ | 100 GB bandwidth, 6,000 build min/mo | Next.js, React, Vue, Svelte, static | ✅ Git | ❌ Never | Industry leader; best for frontend |
| 2 | [**Netlify**](https://netlify.com) | 100 GB BW + 300 build min/mo | Static, serverless functions | ✅ Git | ❌ Never | Drag & drop deploy, form handling |
| 3 | [**Cloudflare Pages**](https://pages.cloudflare.com) ☁️ | Unlimited requests, 500 builds/mo | Jamstack, Workers, static | ✅ Git | ❌ Never | Fastest global CDN, Workers included |
| 4 | [**Render**](https://render.com) | 750 hrs/mo (shared CPU) | Node, Python, Go, Ruby, Docker | ✅ Git | 😴 15 min | Postgres also free; spins down on idle |
| 5 | [**HostingGuru**](https://hostingguru.io) ✨ | 1 always-on app, 512 MB RAM | 14+ frameworks, any Docker image | ✅ GitHub | ❌ Never | **Never sleeps** — production-ready |
| 6 | [**Railway**](https://railway.app) 🚂 | $5 credit/mo (~500 hrs) | Any language, Docker | ✅ GitHub | ❌ No | Best DX; Postgres, Redis free too |
| 7 | [**Fly.io**](https://fly.io) | 3 shared VMs (256 MB), 3 GB storage | Docker, any language | ✅ CLI | ❌ No | Global edge, Postgres free tier |
| 8 | [**Koyeb**](https://koyeb.com) | 1 nano VM (512 MB RAM) | Docker, native containers | ✅ Git | ❌ No | Frankfurt + Washington edge |
| 9 | [**Deno Deploy**](https://deno.com/deploy) 🦕 | 100k requests/day, 100 GB BW | TypeScript, JavaScript | ✅ GitHub | ❌ Never | Edge JS runtime, instant deploys |
| 10 | [**GitHub Pages**](https://pages.github.com) | 1 GB storage, 100 GB BW/mo | Static only (HTML/CSS/JS) | ✅ GitHub Actions | ❌ Never | Official GitHub product, custom domain |
| 11 | [**GitLab Pages**](https://pages.gitlab.com) | 1 GB storage | Static + custom CI pipeline | ✅ GitLab CI | ❌ Never | FOSS-friendly, self-hostable |
| 12 | [**Codeberg Pages**](https://codeberg.page) 🌱 | Unlimited storage | Static sites | ✅ Git | ❌ Never | Open-source alternative to GitHub |
| 13 | [**Neocities**](https://neocities.org) 🏛️ | 1 GB storage, 200 GB BW | Static HTML/CSS/JS | ✅ Web / CLI | ❌ Never | Retro web revival; community built-in |
| 14 | [**Surge**](https://surge.sh) 🌊 | Unlimited publishes | CLI static hosting | ❌ Manual CLI | ❌ Never | `surge ./folder` — done in 5 seconds |
| 15 | [**Glitch**](https://glitch.com) ✨ | Live coding environment | Node.js, frontend | ✅ Auto | 😴 5 min | Remix-any-project; great for learning |
| 16 | [**Replit**](https://replit.com) | Always-on (limited CPU/RAM) | 50+ languages | ✅ From IDE | 😴 Limited | Full IDE in browser; Deployments paid |
| 17 | [**Firebase Hosting**](https://firebase.google.com) 🔥 | 10 GB storage, 360 MB/day transfer | Static + Cloud Functions | ✅ CLI / GitHub | ❌ Never | Google-backed; Auth + Firestore free |
| 18 | [**Supabase**](https://supabase.com) 🧠 | 500 MB DB, 1 GB storage | Auth, DB, Storage, Edge Functions | ✅ Git | 😴 7 days | Open-source Firebase alternative |
| 19 | [**Back4app**](https://back4app.com) | 25k requests/mo, 250 MB | Parse Server / BaaS | ✅ CLI | ❌ No | Great for mobile backend |
| 20 | [**Adaptable.io**](https://adaptable.io) | 1 app + 1 DB | Node, Python, Go | ✅ Git | 😴 Varies | Simple alternative to Heroku |
| 21 | [**Cyclic**](https://cyclic.sh) ♻️ | 10k requests/mo | Node.js | ✅ GitHub | ❌ No | Zero cold starts, free S3 storage |
| 22 | [**Zeabur**](https://zeabur.com) 🆕 | $5 free credit/mo | Node, Python, Go, Docker | ✅ GitHub | ❌ No | Supports Postgres, Redis, MongoDB |
| 23 | [**Kinsta Static**](https://kinsta.com/static-site-hosting/) | 100 GB CDN bandwidth | Static sites only | ✅ GitHub | ❌ Never | Enterprise-grade CDN for free |
| 24 | [**Sevalla**](https://sevalla.com) 🆕 | Static sites free | Static + headless CMS | ✅ Git | ❌ Never | New 2025 platform, Kinsta spin-off |
| 25 | [**Coolify**](https://coolify.io) 🧊 | Self-hosted (unlimited everything) | Any (on your VPS) | ✅ Git | ❌ Never | Host on Oracle Free VPS = free stack |
| 26 | [**PocketHost**](https://pockethost.io) | 1 PocketBase instance | PocketBase (Go backend) | ✅ Auto | ❌ No | Instant backend: auth + DB + files |
| 27 | [**val.town**](https://val.town) | Unlimited vals (small functions) | TypeScript / JavaScript | ✅ Auto | ❌ Never | Run serverless JS snippets as URLs |
| 28 | [**Pipedream**](https://pipedream.com) | 10k events/mo | Node.js, Python | ✅ Auto | ❌ Never | Automation + API webhooks |
| 29 | [**Stormkit**](https://stormkit.io) | 1 free app | React, Vue, Nuxt | ✅ Git | ❌ No | Serverless deployments, A/B testing |
| 30 | [**DigitalOcean App Platform**](https://www.digitalocean.com/products/app-platform) | 3 static sites free | Static only | ✅ GitHub | ❌ Never | Trusted brand, easy UI |

</details>

<br/>

---

## 📦 Classic & PHP Hosting (20+ Providers)

> WordPress, legacy PHP apps, MySQL databases — traditional cPanel-style hosting.

<details open>
<summary><strong>🔽 View all 20+ providers</strong></summary>

| # | Provider | Disk | Bandwidth | MySQL DBs | Ads | Panel | Notes |
|---|----------|:----:|:---------:|:---------:|:---:|-------|-------|
| 1 | [**InfinityFree**](https://infinityfree.net) ∞ | 5 GB | Unmetered | 400 MB each | ❌ | Own panel | Best free PHP host; no ads injected |
| 2 | [**serv00.com**](https://www.serv00.com) 🆕 | 3 GB SSD | Unlimited | 10 DBs | ❌ | DevilWEB + SSH | SSH access, cron, 3 VM slots |
| 3 | [**GoogieHost**](https://googiehost.com) | 1 GB | 100 GB | Unlimited | ❌ | cPanel-like | No ads, LiteSpeed server |
| 4 | [**Heliohost**](https://heliohost.org) 🚀 | Unlimited | Unmetered | Unlimited | ❌ | cPanel | Python, Ruby, PHP; real cPanel |
| 5 | [**Freehostingnoads.net**](https://freehostingnoads.net) | 10 GB | Unmetered | Unlimited | ❌ | cPanel | 10 GB is massive for free |
| 6 | [**FreeWebHostingArea**](https://freewebhostingarea.com) | 1.5 GB | Unmetered | Unlimited | ❌ | DirectAdmin | Old school, very stable |
| 7 | [**ProFreeHost**](https://profreehost.com) | 5 GB | Unmetered | Unlimited | ❌ | Custom | Good PHP 7.4+ support |
| 8 | [**ByetHost**](https://byet.host) | 1 GB | 50 GB | 2 DBs | ❌ | VistaPanel | InfinityFree network |
| 9 | [**AwardSpace**](https://awardspace.com) 🏆 | 1 GB | 5 GB | 1 DB | ✅ optional | VistaPanel | Optional ad model |
| 10 | [**FreeHostia**](https://freehostia.com) | 250 MB | 6 GB | 6 DBs | ❌ | Custom | Custom-built panel |
| 11 | [**x10Hosting**](https://x10hosting.com) | 2 GB | Unmetered | 2 DBs | ❌ | Own panel | Community-focused |
| 12 | [**Hostss.com**](https://hostss.com) 🆕 | SSD | Unmetered | PHP/MySQL | ❌ | cPanel + builder | New 2025, website builder included |
| 13 | [**000webhost**](https://000webhost.com) | 300 MB | 3 GB | 1 DB | ✅ small | Own panel | Hostinger-owned; beginner-friendly |
| 14 | [**FreeHosting.com**](https://freehosting.com) | Unlimited | Unmetered | ✅ | ❌ | cPanel | Unlimited storage claim |
| 15 | [**Atspace**](https://atspace.com) | 1 GB | 5 GB | 1 DB | ✅ | Own panel | Very long-running provider |
| 16 | [**AEON Free**](https://aeonfree.com) | 5 GB | Unmetered | 5 DBs | ❌ | cPanel | Clean cPanel experience |
| 17 | [**HyperHost**](https://hyperhost.com) | 1 GB | 50 GB | 10 DBs | ❌ | cPanel | Good DB allowance |
| 18 | [**Zymic**](https://zymic.com) | 5 GB | 50 GB | 1 DB | ❌ | Own panel | Classic provider |
| 19 | [**EasyPHP Hosting**](https://easyphp.org) | 2 GB | Unlimited | ✅ | ❌ | Custom | French provider, stable |
| 20 | [**Your-Hosting.net**](https://your-hosting.net) 🆕 | Unspecified | Unmetered | PHP/MySQL | ❌ | Instant | Instant site creation |

</details>

<br/>

---

## 💯 100% Completely Free Hosting — No Catch

> Genuinely free forever: no credit card, no expiry, no injected ads, no forced upgrades.

| # | Provider | Stack | Standout Feature | Disk | Bandwidth |
|---|----------|-------|-----------------|:----:|:---------:|
| 1 | [**InfinityFree**](https://infinityfree.net) ∞ | PHP + MySQL | 5 GB disk, 400 MB MySQL per DB, no ads | 5 GB | Unmetered |
| 2 | [**GoogieHost**](https://googiehost.com) | PHP + MySQL | LiteSpeed, cPanel-like, zero ads | 1 GB | 100 GB |
| 3 | [**serv00.com**](https://www.serv00.com) | Shell + PHP + MySQL | SSH, DevilWEB, cron jobs, 10 DBs | 3 GB SSD | Unlimited |
| 4 | [**Heliohost**](https://heliohost.org) 🚀 | PHP / Python / Ruby | Real cPanel, server-side runtimes | Unlimited | Unmetered |
| 5 | [**Freehostingnoads.net**](https://freehostingnoads.net) | PHP + MySQL | 10 GB disk, zero ads whatsoever | 10 GB | Unmetered |
| 6 | [**ProFreeHost**](https://profreehost.com) | PHP + MySQL | 5 GB disk, unlimited MySQL, no ads | 5 GB | Unmetered |
| 7 | [**ByetHost**](https://byet.host) | PHP + MySQL | VistaPanel, no ads | 1 GB | 50 GB |
| 8 | [**FreeWebHostingArea**](https://freewebhostingarea.com) | PHP + MySQL | DirectAdmin, unlimited DBs | 1.5 GB | Unmetered |
| 9 | [**Cloudflare Pages**](https://pages.cloudflare.com) ☁️ | Static / Jamstack | Unlimited CDN, zero ads, Workers | Unlimited | Unlimited |
| 10 | [**GitHub Pages**](https://pages.github.com) | Static | Official GitHub product, no expiry | 1 GB | 100 GB |
| 11 | [**Vercel**](https://vercel.com) ▲ | Static + Serverless | Best CDN performance, zero ads | 1 GB | 100 GB |
| 12 | [**Netlify**](https://netlify.com) | Static + Functions | Drag & drop, form handling | Unlimited | 100 GB |
| 13 | [**Neocities**](https://neocities.org) 🏛️ | Static HTML | Community, custom domain | 1 GB | 200 GB |
| 14 | [**PocketHost**](https://pockethost.io) | PocketBase BaaS | Auth + DB + files, always on | 1 GB | Fair |
| 15 | [**Deno Deploy**](https://deno.com/deploy) 🦕 | Edge TypeScript/JS | 100k req/day, never sleeps | — | 100 GB |

> 💡 **Best free full-stack combo:** `InfinityFree` (PHP backend) + `Cloudflare Pages` (frontend) + `Supabase` (database) = **100% free, no ads, no expiry**.

<br/>

---

## 🌐 Free HTML Hosting (No Expiry)

> Host plain HTML/CSS/JS for portfolios, landing pages, or Claude-generated code. No server needed.

### 🖊️ Step-by-Step Guides

<details>
<summary><strong>Option 1 — GitHub Pages (Recommended, Never Expires)</strong></summary>

1. Create a GitHub repo named `yourusername.github.io`
2. Add your `index.html` to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Visit `https://yourusername.github.io` — live in seconds

**Custom domain:** Settings → Pages → Custom domain → `yourname.is-a.dev`

✅ No ads injected. Full control. Free SSL. Custom domain. Never expires.

</details>

<details>
<summary><strong>Option 2 — Netlify Drop (Drag & Drop, No Signup)</strong></summary>

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag your HTML folder onto the browser window
3. Get a live `random.netlify.app` URL instantly
4. Create a free account to make the URL permanent + add custom domain

✅ Zero login needed for instant deploy. Best for Claude-generated HTML output.

</details>

<details>
<summary><strong>Option 3 — Tiiny.host (Easiest, Zero Signup)</strong></summary>

1. Go to [tiiny.host](https://tiiny.host)
2. Upload your `.html` file or a `.zip` of your site
3. Get `yourname.tiiny.site` instantly
4. Files stay up indefinitely on the free tier

✅ Zero signup. Zero ads. Clean URL. Shareable in under 60 seconds.

</details>

<details>
<summary><strong>Option 4 — Surge.sh (CLI, Instant)</strong></summary>

```bash
npm install -g surge
surge /path/to/your/folder yourname.surge.sh
```

✅ No account needed for first deploy. CNAME for custom domain. Free SSL.

</details>

<details>
<summary><strong>Option 5 — Cloudflare Pages (Enterprise-Grade CDN, Free)</strong></summary>

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repo
3. Set build command to blank (or `npm run build` for frameworks)
4. Deploy — get `yourproject.pages.dev`

✅ Unlimited requests. Global CDN. Custom domain. Workers included.

</details>

<details>
<summary><strong>Option 6 — Blogger Static Page Trick</strong></summary>

1. Create a Blogger blog at [blogger.com](https://blogger.com)
2. Go to **Pages → New Page → HTML mode**
3. Paste your full HTML code
4. Use a blank layout theme (strip header/footer/sidebar)
5. Publish → live at `yourname.blogspot.com/p/your-page.html`

⚠️ Blogger injects Google scripts. Use blank theme for clean output.

</details>

### 📋 HTML Hosting Comparison

| Provider | URL Style | Ads | Expiry | Custom Domain | Notes |
|----------|-----------|:---:|:------:|:-------------:|-------|
| [GitHub Pages](https://pages.github.com) | `user.github.io` | ❌ | ❌ Never | ✅ | Best for devs |
| [Netlify](https://netlify.com) | `random.netlify.app` | ❌ | ❌ Never | ✅ | Drop & deploy |
| [Vercel](https://vercel.com) | `project.vercel.app` | ❌ | ❌ Never | ✅ | Fastest CDN |
| [Cloudflare Pages](https://pages.cloudflare.com) | `project.pages.dev` | ❌ | ❌ Never | ✅ | Unlimited req |
| [Tiiny.host](https://tiiny.host) | `name.tiiny.site` | ❌ | ❌ Never | ❌ Paid | No signup needed |
| [Surge.sh](https://surge.sh) | `name.surge.sh` | ❌ | ❌ Never | ✅ CNAME | CLI-based |
| [Neocities](https://neocities.org) | `name.neocities.org` | ❌ | ❌ Never | ✅ Paid | 1 GB free |
| [GitLab Pages](https://pages.gitlab.com) | `user.gitlab.io` | ❌ | ❌ Never | ✅ | CI/CD pipeline |
| [Codeberg Pages](https://codeberg.page) | `user.codeberg.page` | ❌ | ❌ Never | ✅ | OSS-friendly |
| [Blogger](https://blogger.com) | `name.blogspot.com` | ✅ | ❌ Never | ✅ | Page trick needed |
| [DigitalOcean](https://www.digitalocean.com/products/app-platform) | Custom | ❌ | ❌ Never | ✅ | 3 static sites |
| [Kinsta Static](https://kinsta.com/static-site-hosting/) | Custom | ❌ | ❌ Never | ✅ | 100 GB CDN free |

<br/>

---

## 🎓 Special Developer Domain Registries

> Free second-level and subdomain registries for developers, open-source projects, and communities.

### 🏷️ How to Claim Each Domain

| Registry | Domain Given | How to Claim | Requirements | Approval Time |
|----------|:------------:|-------------|:------------:|:-------------:|
| [**is-a.dev**](https://is-a.dev) | `yourname.is-a.dev` | GitHub Pull Request to `is-a-dev/register` | Active GitHub + public repo | 1–7 days |
| [**js.org**](https://js.org) | `yourname.js.org` | GitHub PR to `js-org/js.org` | JavaScript/Node.js project | 1–5 days |
| [**eu.org**](https://nic.eu.org) | `yourname.eu.org` | Web form at nic.eu.org | Any legitimate use | 2–8 weeks |
| [**Open Domains**](https://open-domains.net) | `*.is-cool.dev` etc. | GitHub PR | DNSSEC, public project | 1–3 days |
| [**US.KG**](https://register.us.kg) | `yourname.us.kg` | Web form + GitHub auth | GitHub account | Instant–24 hrs |
| [**Domains Project**](https://github.com/domainsproject/register) | Various | GitHub PR | Public project | 1–7 days |
| [**is-a-good.dev**](https://github.com/is-a-good-dev/register) | `yourname.is-a-good.dev` | GitHub PR | Active developer | 1–5 days |
| [**wip.la**](https://wip.la) | `yourname.wip.la` | GitHub PR | Work-in-progress project | 1–3 days |

### 📝 Step-by-Step: Claim `yourname.js.org`

1. Your project must be a **JavaScript/Node.js** open-source project on GitHub
2. Fork `https://github.com/js-org/js.org`
3. Edit `cnames_active.js` — add your entry:
   ```js
   "yourname": "yourusername.github.io/your-repo",
   ```
4. Open a Pull Request with title: `feat: add yourname.js.org`
5. Wait for automated checks + maintainer review
6. After merge, add `yourname.js.org` as custom domain in GitHub Pages settings

### 📝 Step-by-Step: Claim `yourname.eu.org`

1. Go to [nic.eu.org/arf/whois/](https://nic.eu.org/arf/whois/)
2. Register for an account at [nic.eu.org/arf/add.html](https://nic.eu.org/arf/add.html)
3. Fill in the registration form — you need to supply DNS nameservers
4. Use Cloudflare free DNS (ns1.cloudflare.com / ns2.cloudflare.com) as your nameservers
5. Submit — expect 2–8 weeks for manual review
6. Once approved, manage DNS via your Cloudflare dashboard

> **eu.org** gives you a real second-level domain (like a `.com`), completely free. It's one of the best-kept secrets in the free domain world.

<br/>

---

## 🖥️ Free VPS & Cloud Compute

> Full root access, real Linux environments — for when you need more than shared hosting.

| # | Provider | Free Specs | Region | Notes |
|---|----------|-----------|:------:|-------|
| 1 | [**Oracle Cloud Free Tier**](https://www.oracle.com/cloud/free/) | 4 ARM cores / 24 GB RAM + 2 AMD x86 VMs | Global | **Best free VPS.** Always free, credit card for verification only |
| 2 | [**Google Cloud Free Tier**](https://cloud.google.com/free) | e2-micro: 0.25–0.5 vCPU, 1 GB RAM | US only | Always free + $300 90-day credit |
| 3 | [**AWS Free Tier**](https://aws.amazon.com/free/) | t2.micro: 750 hrs/mo for 12 months | US-East | Broad services; largest ecosystem |
| 4 | [**Microsoft Azure Free**](https://azure.microsoft.com/en-us/free/) | B1S VM: 750 hrs/mo for 12 months | Global | + $200 credit for first 30 days |
| 5 | [**Cloudflare Workers**](https://workers.cloudflare.com/) | 100k req/day, 10ms CPU/req | Edge (global) | Edge compute; not a VM but very powerful |
| 6 | [**Huawei Cloud Free**](https://www.huaweicloud.com/intl/en-us/free) | 1 ECS instance, 40 GB SSD | Asia/EU | Good for APAC coverage |
| 7 | [**IBM Cloud Lite**](https://www.ibm.com/cloud/free) | 256 MB Cloud Foundry runtime | US | + Cloudant NoSQL free tier |
| 8 | [**VPSWala.org**](https://vpswala.org) | Community-driven free VPS | Varies | No corporate complexity; community-run |
| 9 | [**Euserv**](https://euserv.com) | 1 vCore, 1 GB RAM, 10 GB SSD | Germany | Free KVM VPS for EU users |
| 10 | [**serv00.com**](https://www.serv00.com) ✨ | 3 GB SSD, 10 DBs, 3 VM slots | EU | SSH + cron + MySQL; not a VPS but close |

### 🏆 Free VPS Setup Guide: Oracle Cloud ARM (Best Free Tier)

```bash
# 1. Sign up at oracle.com/cloud/free — credit card needed for verification, NOT charged
# 2. Go to Compute → Instances → Create Instance
# 3. Choose: Ampere (ARM) shape → VM.Standard.A1.Flex
#    Set: 4 OCPUs, 24 GB RAM (maximum free allocation)
# 4. Choose Ubuntu 22.04 or Oracle Linux
# 5. Generate SSH key pair (download private key)
# 6. Create instance — takes ~3 minutes
# 7. Open port 22 (SSH), 80 (HTTP), 443 (HTTPS) in Security List
# 8. SSH in:
ssh -i your-private-key.pem ubuntu@YOUR_PUBLIC_IP

# 9. Install Coolify (open-source Heroku alternative) to manage apps:
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | bash

# Result: Free 4-core ARM server with 24 GB RAM, running forever ✅
```

<br/>

---

## 📧 Free Email Forwarding & Extras

> Free email, analytics, databases, and other useful services to complete your stack.

| Service | Type | Free Tier | Notes |
|---------|:----:|-----------|-------|
| [**Cloudflare Email Routing**](https://cloudflare.com/email-routing/) | Email forward | Unlimited rules | Forward `you@yourdomain.com` → Gmail. Best option. |
| [**ImprovMX**](https://improvmx.com) | Email forward | 25 aliases | Forward custom domain email free |
| [**ForwardEmail**](https://forwardemail.net) | Email forward | Unlimited | Open-source, privacy-first |
| [**Zoho Mail**](https://zoho.com/mail) | Full email hosting | 5 GB mailbox | Free custom domain email client |
| [**Mailersend**](https://mailersend.com) | Transactional email | 3,000 emails/mo | For app email sending |
| [**Brevo (Sendinblue)**](https://brevo.com) | Email marketing | 300 emails/day | Newsletter + transactional |
| [**Supabase**](https://supabase.com) | Database | 500 MB Postgres | Full Postgres + auth + storage |
| [**PlanetScale**](https://planetscale.com) | Database | 5 GB MySQL | Serverless MySQL, branching |
| [**Turso**](https://turso.tech) | Database | 500 MB SQLite | Edge SQLite, 9 GB total free |
| [**Upstash Redis**](https://upstash.com) | Cache / Queue | 10k cmd/day | Serverless Redis + Kafka |
| [**Plausible (self-host)**](https://plausible.io) | Analytics | Free self-hosted | Privacy-first Google Analytics alt |
| [**Umami**](https://umami.is) | Analytics | Free self-hosted | Simple, open-source analytics |
| [**Cloudflare Analytics**](https://cloudflare.com/analytics/) | Analytics | Unlimited | Included with any Cloudflare site |
| [**Cronitor**](https://cronitor.io) | Cron monitoring | 5 monitors | Monitor your free cron jobs |
| [**UptimeRobot**](https://uptimerobot.com) | Uptime monitoring | 50 monitors | Ping every 5 min, alerts free |

<br/>

---

## 🧠 Best Picks — By Use Case

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                    CHOOSE YOUR USE CASE                             ║
╠══════════════════════════════════════════════════════════════════════╣
║  🏠 Homelab / IoT DDNS        →  DuckDNS or Dynv6                  ║
║  📁 Static Site (React/Vue)   →  Vercel, Netlify, or CF Pages       ║
║  🟢 Node.js App (No Sleep)    →  HostingGuru (never sleeps)         ║
║  🐘 PHP + MySQL (WordPress)   →  InfinityFree or serv00.com         ║
║  🐳 Docker Container          →  Fly.io or Koyeb                    ║
║  🌍 Free CDN + DNS            →  Cloudflare (any domain)            ║
║  📄 HTML Page (Quick Share)   →  Tiiny.host or Netlify Drop         ║
║  🐍 Python / Go Backend       →  Render or Deno Deploy              ║
║  🖥️  Linux VPS (Always Free)  →  Oracle Cloud ARM (4c/24GB)         ║
║  🧑‍💻 Dev Subdomain (Portfolio) →  is-a.dev via GitHub PR            ║
║  📦 JS Project Domain         →  js.org via GitHub PR               ║
║  🌐 Free Second-Level Domain  →  eu.org (free .org-like TLD)        ║
║  🔄 Free Backend-as-a-Service →  PocketHost or Supabase             ║
║  📧 Free Custom Email         →  Cloudflare Email Routing           ║
║  🔐 Free Database             →  Supabase (Postgres) or Turso       ║
║  🤖 Host AI/Claude HTML Code  →  Netlify Drop (60 sec deploy)       ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

### 🏆 Recommended Free Stacks

**Stack 1 — Developer Portfolio (Zero Cost)**
```
Domain:    yourname.is-a.dev (GitHub PR → approved in days)
Frontend:  GitHub Pages (auto-deploys from your repo)
Analytics: Cloudflare Analytics (free with Pages)
Email:     Cloudflare Email Routing → forwards to Gmail
Cost:      $0 / month ✅
```

**Stack 2 — Full-Stack Web App (Never Sleeps)**
```
Domain:    yourname.us.kg or Cloudflare free DNS
Frontend:  Cloudflare Pages (unlimited requests, global CDN)
Backend:   HostingGuru free tier (never sleeps, Docker support)
Database:  Supabase (500 MB Postgres + auth + storage)
Cost:      $0 / month ✅
```

**Stack 3 — WordPress / PHP Site**
```
Domain:    yourname.is-a.dev → CNAME to host
Hosting:   InfinityFree (5 GB, unlimited MySQL, no ads)
Database:  InfinityFree MySQL (400 MB per DB)
CDN:       Cloudflare free (add InfinityFree IP)
Cost:      $0 / month ✅
```

**Stack 4 — Unlimited VPS (Ultimate Free)**
```
Server:    Oracle Cloud ARM (4 cores, 24 GB RAM, always free)
Panel:     Coolify self-hosted (manage all apps via GUI)
Domain:    eu.org (free second-level domain)
DNS:       Cloudflare (point eu.org NS to Cloudflare)
SSL:       Let's Encrypt (auto via Coolify)
Cost:      $0 / month ✅ — handles dozens of apps
```

<br/>

---

## 📌 Pro Tips & Reality Check

<div align="center">

| Tip | Details |
|:---|:---|
| ⚡ **Free Tier Limits** | CPU, memory, bandwidth caps apply. Always read the fine print before production use. |
| 🧪 **Best For** | Prototypes, staging, personal projects, MVPs, portfolios, open-source tools. |
| 💾 **Always Backup** | Free hosts can suspend accounts. Keep a local copy + GitHub backup. |
| 🌐 **Use Custom Domains** | Most free hosts support CNAME — looks professional, costs nothing. |
| 🧩 **Combine Services** | Cloudflare DNS + Vercel + Supabase = 100% free full-stack. |
| 🔒 **Free SSL Everywhere** | Every platform listed includes Let's Encrypt HTTPS. Never pay for SSL. |
| 🤖 **AI-Generated HTML** | Drop Claude output on Netlify or Tiiny.host in under 60 seconds. |
| 😴 **Avoid Cold Starts** | Use HostingGuru or Cloudflare Pages for always-on free hosting. |
| 🛡️ **DDoS Protection** | Route any domain/IP through Cloudflare free — instant DDoS mitigation. |
| 📊 **Monitor Uptime** | Use UptimeRobot (free, 50 monitors) to get alerted if free hosts go down. |
| 🔄 **Keep DDNS Active** | DuckDNS needs a ping every 30 days. Set a cron or they may expire. |
| 🎯 **eu.org for .com Look** | `yourname.eu.org` looks like a real TLD — perfect for serious projects. |

</div>

<br/>

---

## 🤝 Contribute & Support

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1200&color=00C851&center=true&vCenter=true&width=600&lines=Found+a+broken+link%3F+Open+an+issue!;Know+a+free+service+we+missed%3F+PR+welcome!;Star+the+repo+to+help+others+find+it+⭐" alt="contribute typing"/>

</div>

- ⭐ **Star this repository** to help others discover it
- 🍴 **Fork** and send a **Pull Request** with new services
- 🐛 **[Open an issue](https://github.com/Grexlabs/free-domain-hosting/issues)** for dead links or outdated info
- 📢 **Share** with your dev friends and communities
- 💬 **[Start a discussion](https://github.com/Grexlabs/free-domain-hosting/discussions)** to suggest improvements

<br/>

<div align="center">

<a href="https://github.com/Grexlabs/free-domain-hosting/stargazers"><img src="https://img.shields.io/github/stars/Grexlabs/free-domain-hosting?style=flat-square&logo=github&color=f7df1e" alt="Stars"></a>
<a href="https://github.com/Grexlabs/free-domain-hosting/network/members"><img src="https://img.shields.io/github/forks/Grexlabs/free-domain-hosting?style=flat-square&logo=github&color=0099ff" alt="Forks"></a>
<a href="https://github.com/Grexlabs/free-domain-hosting/issues"><img src="https://img.shields.io/github/issues/Grexlabs/free-domain-hosting?style=flat-square&logo=github&color=ff6b6b" alt="Issues"></a>
<img src="https://img.shields.io/badge/License-MIT-00d2ff.svg?style=flat-square" alt="License">

</div>

<br/>

---

<div align="center">

### 📊 Totals at a Glance

| Category | Count |
|:--------:|:-----:|
| 🌍 Free Subdomain / DDNS Providers | **40+** |
| ⚡ Developer Hosting & PaaS | **30+** |
| 📦 Classic PHP / MySQL Hosts | **20+** |
| 💯 100% Free No-Catch Hosts | **15+** |
| 🌐 Free HTML Hosting Options | **12+** |
| 🖥️ Free VPS / Cloud Compute | **10+** |
| 🎓 Special Dev Domain Registries | **8+** |
| 📧 Email & Extras | **10+** |
| **🎯 TOTAL RESOURCES** | **145+** |

<br/>

![line](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<sub><strong>Last verified:</strong> May 2026 — all links confirmed active and free.</sub>

<br/>

Made with ❤️ by **[GrexLabs](https://github.com/Grexlabs)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f093fb,50:764ba2,100:667eea&height=140&section=footer&text=Happy%20Building%20🚀&fontSize=28&fontAlignY=65&fontColor=ffffff&animation=twinkling" width="100%"/>

</div>
