# 👋 Hi, I'm Z (a.k.a z-scraper)

I build high-performance APIs so you don’t have to scrape the web yourself.

_Currently focused on:_

- 🪙 **Crypto API** – crypto news aggregation + AI sentiment analysis
- 👔 **LinkedIn API** – structured LinkedIn data for lead gen & recruiting tools

---

## 🪙 Crypto API – Crypto news + AI sentiment

A high-performance API built on Cloudflare Workers that aggregates crypto news from **6 major sources**:

- Bitcoinist
- CoinDesk
- Cointelegraph
- Crypto Daily
- Crypto News
- Decrypt

### Core features

- **Unified news feed** – single API to fetch the latest crypto news across all sources
- **Detail endpoints** – get full article content, not just headlines
- **AI sentiment analysis** – positive / negative / neutral labels for each article
- **Multi-source aggregation** – premium tier merges all sources with duplicate detection
- **Edge performance** – deployed on Cloudflare Workers for sub-100ms responses

### Perfect for

- Trading bots using **news + sentiment** as signals
- Crypto dashboards & alerting systems
- Research tools & data pipelines

👉 **Try it on RapidAPI:** [Crypto API](https://rapidapi.com/zscraper/api/z-crypto-news)  
👉 Subscribe, grab your API key, and plug it into the SDKs below.

---

## 👔 LinkedIn API – Data for lead gen & recruiting

A comprehensive API for LinkedIn data extraction, also built on Cloudflare Workers.

### Core features

- **Profiles** – basic info, contact, skills, education, experience, recommendations
- **Activity** – posts, comments, images, videos, documents, reactions
- **Companies** – company profiles, posts, jobs, employees
- **Jobs** – job details, listings, filters for search
- **Advanced search** – people, companies, jobs with 20+ filters (location, title, industry, etc.)

### Perfect for

- Lead gen tools (enrich leads with LinkedIn data)
- Recruiting tools & ATS integrations
- Market research & competitive intelligence dashboards

👉 **Try it on RapidAPI:** _Coming soon – currently in active development._

---

## 📦 SDKs & Example Projects

I’m building SDKs and example apps so you can plug these APIs into your stack in minutes.

### Available SDKs for Crypto API

- **TypeScript / JavaScript**

  - Repo: **[crypto-api](https://github.com/z-scraper/crypto-api)**
  - npm: `@z-scraper/crypto-api`

  ```bash
  npm install @z-scraper/crypto-api
  # or
  yarn add @z-scraper/crypto-api
  ```

- **Go**

  - Repo: **[cryptoapi-go](https://github.com/z-scraper/cryptoapi-go)**
  - Module: `github.com/z-scraper/cryptoapi-go`

  ```bash
  go get github.com/z-scraper/cryptoapi-go
  ```

---

## 💡 What you can build with my APIs

- Crypto trading bots using **news + AI sentiment**
- Real-time dashboards tracking sentiment across crypto news sources
- Lead gen tools combining **LinkedIn people + company + job** search
- Recruiter tools to find candidates using advanced LinkedIn filters
- Internal analytics tools for sales, recruiting, and market research

If you’re building any of these, I’d love to see it.

---

## 🤝 How to reach me

- Open an **Issue** in any repo if you need help with the APIs
- Use **Discussions** to share what you’re building or request features
- Star the repos if you find them useful – it helps a lot 💙

Thanks for stopping by & happy building!
