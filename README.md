# Awesome Web Scraping 2026 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Stars](https://img.shields.io/github/stars/spinov001-art/awesome-web-scraping-2026?style=social)](https://github.com/spinov001-art/awesome-web-scraping-2026)

> A curated list of web scraping tools, frameworks, libraries, and APIs for 2026. Maintained weekly.
>
> **⭐ Star this repo** to keep it in your bookmarks — new tools added every week.

## Contents

- [Frameworks & Libraries](#frameworks--libraries)
  - [Python](#python)
  - [JavaScript / TypeScript](#javascript--typescript)
  - [Go](#go)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [PHP](#php)
- [Browser Automation](#browser-automation)
- [Headless Browsers](#headless-browsers)
- [Anti-Detection & Stealth](#anti-detection--stealth)
- [Proxy Services](#proxy-services)
- [CAPTCHA Solving](#captcha-solving)
- [Cloud Scraping Platforms](#cloud-scraping-platforms)
- [Free APIs (No Scraping Needed)](#free-apis-no-scraping-needed)
- [Pre-Built Scrapers (Apify Store)](#pre-built-scrapers-apify-store)
- [Data Parsing & Extraction](#data-parsing--extraction)
- [Anti-Bot Detection](#anti-bot-detection)
- [Scraping Infrastructure](#scraping-infrastructure)
- [Tutorials & Articles](#tutorials--articles)
- [Related Awesome Lists](#related-awesome-lists)

---

## Frameworks & Libraries

### Python

| Tool | Stars | Description |
|------|-------|-------------|
| [Scrapy](https://github.com/scrapy/scrapy) | 53k+ | The most popular Python scraping framework. Async, middlewares, pipelines, built-in export. |
| [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) | — | HTML/XML parser. Simple API, forgiving of bad markup. Use with `requests`. |
| [Requests-HTML](https://github.com/psf/requests-html) | 13k+ | Pythonic HTML parsing with JS rendering support via Chromium. |
| [httpx](https://github.com/encode/httpx) | 13k+ | Modern async HTTP client. HTTP/2 support, better than `requests` for scraping. |
| [Parsel](https://github.com/scrapy/parsel) | 1k+ | CSS + XPath selector library extracted from Scrapy. |
| [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) | 4k+ | Stateful web browsing (form submission, cookies) — like a human clicking. |
| [Grab](https://github.com/lorien/grab) | 2k+ | Web scraping framework. Network requests, DOM parsing, spider. |
| [Selectolax](https://github.com/rushter/selectolax) | 1k+ | Fast HTML parser (10-20x faster than lxml). C-level speed. |
| [gazpacho](https://github.com/maxhumber/gazpacho) | 700+ | Simple, modern web scraping. Minimal API surface. |
| [Crawlee (Python)](https://github.com/apify/crawlee-python) | 5k+ | Apify's scraping framework for Python. BeautifulSoup + Playwright crawlers. |

### JavaScript / TypeScript

| Tool | Stars | Description |
|------|-------|-------------|
| [Crawlee](https://github.com/apify/crawlee) | 15k+ | Full-featured scraping framework by Apify. Cheerio, Playwright, Puppeteer crawlers. |
| [Cheerio](https://github.com/cheeriojs/cheerio) | 28k+ | Fast jQuery-like HTML parser for Node.js. No browser needed. |
| [node-crawler](https://github.com/bda-research/node-crawler) | 7k+ | HTTP crawler with jQuery-style selectors, rate limiting, retries. |
| [x-ray](https://github.com/matthewmueller/x-ray) | 6k+ | Declarative web scraping with schema definitions. |
| [Apify SDK](https://github.com/apify/apify-sdk-js) | 4k+ | Toolkit for building Apify actors — storage, proxies, queue. |

### Go

| Tool | Stars | Description |
|------|-------|-------------|
| [Colly](https://github.com/gocolly/colly) | 23k+ | Fast and elegant scraping framework for Go. |
| [goquery](https://github.com/PuerkitoBio/goquery) | 14k+ | jQuery-like HTML selector in Go. |
| [Ferret](https://github.com/MontFerret/ferret) | 6k+ | Declarative web scraping with FQL query language. |
| [Geziyor](https://github.com/geziyor/geziyor) | 2k+ | Fast web scraping with concurrent requests and caching. |

### Ruby

| Tool | Stars | Description |
|------|-------|-------------|
| [Nokogiri](https://github.com/sparklemotion/nokogiri) | 6k+ | HTML/XML parser, industry standard for Ruby. |
| [Mechanize](https://github.com/sparklemotion/mechanize) | 4k+ | Automated web interaction (clicks, forms, cookies). |
| [Kimurai](https://github.com/vifreefly/kimuraframework) | 1k+ | Modern Ruby web scraping framework. |

### Rust

| Tool | Stars | Description |
|------|-------|-------------|
| [spider](https://github.com/spider-rs/spider) | 3k+ | Fastest web crawler. Written in Rust, 20-100x faster. |
| [reqwest](https://github.com/seanmonstar/reqwest) | 10k+ | Ergonomic HTTP client for Rust with async support. |
| [scraper](https://github.com/causal-agent/scraper) | 2k+ | CSS selector-based HTML parser for Rust. |

### PHP

| Tool | Stars | Description |
|------|-------|-------------|
| [Goutte](https://github.com/FriendsOfPHP/Goutte) | 9k+ | Screen scraping and web crawling library for PHP. |
| [Roach](https://github.com/roach-php/core) | 2k+ | Scrapy-inspired web scraping for PHP. |
| [Panther](https://github.com/symfony/panther) | 3k+ | Browser testing and scraping with real browsers in PHP. |

## Browser Automation

| Tool | Stars | Description |
|------|-------|-------------|
| [Playwright](https://github.com/microsoft/playwright) | 68k+ | Cross-browser automation by Microsoft. Chromium, Firefox, WebKit. Best anti-detection. |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | 89k+ | Chrome automation by Google. Mature ecosystem. |
| [Selenium](https://github.com/SeleniumHQ/selenium) | 31k+ | The OG browser automation. Supports all browsers. |
| [Cypress](https://github.com/cypress-io/cypress) | 47k+ | Testing-focused but works for scraping interactive SPAs. |
| [Rod](https://github.com/go-rod/rod) | 5k+ | Playwright/Puppeteer alternative for Go. DevTools Protocol. |
| [Splash](https://github.com/scrapinghub/splash) | 4k+ | Lightweight browser as a service. JS rendering via HTTP API. |

## Headless Browsers

| Tool | Description |
|------|-------------|
| [Browserless](https://github.com/browserless/browserless) | Chrome as a service. Docker-ready. Free self-hosted. |
| [chrome-headless-shell](https://developer.chrome.com/blog/chrome-headless-shell) | Official Google headless Chrome. Smallest footprint. |
| [Playwright Docker](https://mcr.microsoft.com/en-us/product/playwright/about) | Official Playwright Docker images with all browsers. |

## Anti-Detection & Stealth

| Tool | Stars | Description |
|------|-------|-------------|
| [undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver) | 10k+ | Patched ChromeDriver that passes bot detection. |
| [puppeteer-extra-stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth) | 12k+ | Plugin bundle to evade detection (WebGL, navigator, etc.) |
| [curl-impersonate](https://github.com/lwthiker/curl-impersonate) | 13k+ | curl that impersonates Chrome/Firefox TLS fingerprint. |
| [Camoufox](https://github.com/daijro/camoufox) | 5k+ | Anti-detect Firefox browser for scraping. |

## Proxy Services

| Service | Free Tier | Description |
|---------|-----------|-------------|
| [Bright Data](https://brightdata.com/) | Trial | 72M+ residential IPs. Enterprise grade. |
| [Oxylabs](https://oxylabs.io/) | Trial | Residential and datacenter proxies. |
| [ScraperAPI](https://www.scraperapi.com/) | 1000 free | API that handles proxies and CAPTCHAs. |
| [Smartproxy](https://smartproxy.com/) | Trial | 65M+ residential proxies. |
| [IPRoyal](https://iproyal.com/) | — | Budget residential proxies from $1.75/GB. |

## CAPTCHA Solving

| Service | Price | Description |
|---------|-------|-------------|
| [2Captcha](https://2captcha.com/) | $1-3/1000 | Human-powered CAPTCHA solving API. |
| [Anti-Captcha](https://anti-captcha.com/) | $1-2/1000 | reCAPTCHA, hCaptcha, image CAPTCHA. |
| [CapSolver](https://www.capsolver.com/) | $0.8/1000 | AI-powered CAPTCHA solving. |

## Cloud Scraping Platforms

| Platform | Free Tier | Description |
|----------|-----------|-------------|
| [Apify](https://apify.com/) | $5/mo free | Run scrapers in cloud. 2000+ pre-built actors. Proxies included. |
| [ScrapingBee](https://www.scrapingbee.com/) | 1000 free | API: send URL, get HTML. JS rendering, proxies. |
| [Firecrawl](https://firecrawl.dev/) | 500 free | Turn websites into LLM-ready markdown. Great for AI. |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Open source | LLM-friendly web crawler. Markdown extraction. |
| [ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai) | Open source | AI-powered scraping — just describe what you want. |
| [Browserbase](https://www.browserbase.com/) | Free tier | Headless browser infrastructure. API-based. |

## Free APIs (No Scraping Needed)

Why scrape when you can use official APIs? These require **no API key**:

| API | Data | Rate Limit |
|-----|------|-----------|
| [Reddit JSON](https://www.reddit.com/r/python.json) | Posts, comments, subreddits | ~60/min |
| [Hacker News](https://github.com/HackerNews/API) | Stories, comments, users | ~1/sec |
| [YouTube Innertube](https://dev.to/0012303/youtubes-secret-innertube-api-extract-comments-transcripts-channel-data-without-api-keys-mil) | Comments, transcripts, channels | No hard limit |
| [Wikipedia](https://en.wikipedia.org/api/rest_v1/) | Articles, summaries, media | 200/sec |
| [arXiv](https://arxiv.org/help/api) | 2M+ research papers | 1/3sec |
| [npm Registry](https://registry.npmjs.org/) | Package metadata | No hard limit |
| [PyPI JSON](https://pypi.org/pypi/requests/json) | Python package info | No hard limit |
| [GitHub REST](https://docs.github.com/en/rest) | Repos, users, issues | 60/hr unauth |
| [Open-Meteo](https://open-meteo.com/) | Weather forecasts | Unlimited |
| [CoinGecko](https://www.coingecko.com/en/api) | Crypto prices | 30/min |
| [Crossref](https://api.crossref.org/) | 150M+ academic papers | 50/sec |
| [RDAP](https://rdap.org/) | Domain WHOIS data | Varies |

> 📚 **[Full list: 300+ Free APIs →](https://github.com/spinov001-art/awesome-free-apis-2026)**

## Pre-Built Scrapers (Apify Store)

Ready-to-use scrapers — no code required. Run on [Apify](https://apify.com/store) free tier.

| Scraper | Method | Data |
|---------|--------|------|
| [Reddit Scraper](https://apify.com/knotless_cadence/reddit-scraper-pro) | JSON API | Posts, comments, scores |
| [YouTube Comments](https://apify.com/knotless_cadence/youtube-comments-scraper) | Innertube | Comments without API key |
| [YouTube Transcript](https://apify.com/knotless_cadence/youtube-transcript-scraper) | Captions XML | Subtitles and captions |
| [Hacker News](https://apify.com/knotless_cadence/hacker-news-scraper) | Firebase | Stories and comments |
| [Trustpilot Reviews](https://apify.com/knotless_cadence/trustpilot-review-scraper) | JSON-LD | Reviews via structured data |
| [Google News](https://apify.com/knotless_cadence/google-news-scraper) | RSS | 15 languages |
| [SEO Audit](https://apify.com/knotless_cadence/seo-audit-tool) | Multi | 50+ on-page factors |
| [Email Extractor](https://apify.com/knotless_cadence/email-extractor-pro) | HTML | Emails, phones, socials |
| [Tech Stack Detector](https://apify.com/knotless_cadence/website-tech-stack-detector) | Headers+JS | 80+ technologies |
| [Bluesky Scraper](https://apify.com/knotless_cadence/bluesky-scraper) | AT Protocol | Profiles and posts |

> 🔍 **[All 77 scrapers →](https://apify.com/store?q=knotless_cadence)**

## Data Parsing & Extraction

| Tool | Stars | Description |
|------|-------|-------------|
| [lxml](https://github.com/lxml/lxml) | 2k+ | Fastest XML/HTML parser for Python. XPath + XSLT. |
| [Readability](https://github.com/mozilla/readability) | 8k+ | Firefox's reader mode as a library. Extract article content. |
| [Trafilatura](https://github.com/adbar/trafilatura) | 3k+ | Extract main text from web pages. Removes boilerplate. |
| [newspaper3k](https://github.com/codelucas/newspaper) | 14k+ | Article scraping and NLP. Titles, authors, text, images. |
| [extruct](https://github.com/scrapinghub/extruct) | 800+ | Extract JSON-LD, Microdata, OpenGraph from HTML. |
| [markdownify](https://github.com/matthewwithanm/python-markdownify) | 1k+ | Convert HTML to Markdown. Great for LLM pipelines. |

## Anti-Bot Detection

Tools to **test** your scraper against detection (for authorized testing only):

| Tool | Description |
|------|-------------|
| [CreepJS](https://abrahamjuliot.github.io/creepjs/) | Browser fingerprint test — see what sites see about you. |
| [Fingerprint.com](https://fingerprint.com/) | Browser fingerprinting service. |

## Scraping Infrastructure

| Tool | Stars | Description |
|------|-------|-------------|
| [Scrapyd](https://github.com/scrapy/scrapyd) | 3k+ | Deploy and run Scrapy spiders as a service. |
| [Gerapy](https://github.com/Gerapy/Gerapy) | 3k+ | Distributed Scrapy management with Django UI. |
| [Portia](https://github.com/scrapinghub/portia) | 9k+ | Visual scraping tool — point and click, no code. |
| [Scrapy-Redis](https://github.com/rmax/scrapy-redis) | 5k+ | Distributed Scrapy with Redis. Scale to millions of pages. |

## Tutorials & Articles

- [I Built a Script That Finds Hidden APIs on Any Website](https://dev.to/0012303/i-built-a-script-that-finds-hidden-apis-on-any-website-heres-the-code-2e5j)
- [API-First vs CSS Selectors — Why APIs Win](https://dev.to/0012303/building-reliable-web-scrapers-why-api-first-beats-css-selectors-every-time-3boe)
- [YouTube's Secret Innertube API](https://dev.to/0012303/youtubes-secret-innertube-api-extract-comments-transcripts-channel-data-without-api-keys-mil)
- [I Scraped 10,000 Reddit Posts — Best Strategy 2026](https://dev.to/0012303/i-scraped-10000-reddit-posts-to-find-the-best-web-scraping-strategy-in-2026-58ab)
- [Free 9-Tool SEO Audit Suite](https://dev.to/0012303/free-9-tool-seo-audit-suite-no-login-no-api-keys-structured-json-657)
- [Web Scraping Cheatsheet 2026](https://github.com/spinov001-art/web-scraping-cheatsheet)

## Related Awesome Lists

- [awesome-web-scraping](https://github.com/lorien/awesome-web-scraping) — The original awesome web scraping list
- [awesome-crawler](https://github.com/BruceDone/awesome-crawler) — Web crawler tools by language
- [awesome-free-apis-2026](https://github.com/spinov001-art/awesome-free-apis-2026) — 300+ free APIs, no key needed
- [awesome-data-engineering-2026](https://github.com/spinov001-art/awesome-data-engineering-2026) — 150+ data engineering tools
- [awesome-mcp-servers-2026](https://github.com/spinov001-art/awesome-mcp-servers-2026) — MCP servers for AI agents

---

## Need Custom Scraping?

I build data extraction tools for any website — APIs, scrapers, pipelines.

**[Hire me →](https://spinov001-art.github.io)** | Email: Spinov001@gmail.com

## License

MIT
