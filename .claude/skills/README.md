# Web scraping skills

These Claude Code skills were collected from GitHub on 2026-11-27. Claude Code loads them automatically for this project. Each frontmatter `name:` was renamed so that no two skills share a name. The rest of each skill is unchanged from upstream, apart from the removal of `.git`, `tests` and `__pycache__`.

## Best pick

| Need | Use | Why |
|---|---|---|
| **Best overall, hosted** (needs a `FIRECRAWL_API_KEY`) | `firecrawl` (router) + `firecrawl-*` | Most-installed scraping skill (~100k installs). Covers scrape, crawl, map, search, interactive pages and monitoring through the Firecrawl CLI. |
| **Best free / open-source** | `scrapling` | Built on the Scrapling library (~78k GitHub stars). Picks a fetcher automatically and handles Cloudflare and logins. The SKILL.md is in Chinese, which works fine with Claude. |
| **Best methodology / choosing a tool** | `scraping-playbook` | Explains how to approach a source, diagnose 403/429 errors and validate data. Includes a catalogue of about 170 tools. |

## All skills

| Skill | Source (license) | What it does |
|---|---|---|
| `firecrawl`, `firecrawl-scrape`, `-crawl`, `-map`, `-search`, `-interact`, `-agent`, `-download`, `-monitor`, `-parse`, `-research-index`, `-developer-index`, `-alexandria` | [firecrawl/cli](https://github.com/firecrawl/cli) (ISC, per package.json) | Firecrawl CLI workflows. Needs `npm i -g firecrawl-cli` and an API key. |
| `scrapling` | [Cedriccmh/claude-code-skill-scrapling](https://github.com/Cedriccmh/claude-code-skill-scrapling) (MIT) | Python Scrapling with stealth/Cloudflare and session templates. Needs `pip install scrapling`. |
| `scraping-playbook` | [Murtadha-Najem/scraping-skill](https://github.com/Murtadha-Najem/scraping-skill) (MIT) | Scraping method plus a tool encyclopedia, with probe/scrapekit helper scripts. |
| `scraping-strategy-apify` | [yfe404/web-scraper](https://github.com/yfe404/web-scraper) (MIT) | Finds APIs through traffic interception, sitemap/API/DOM strategies, and TypeScript Apify Actors. |
| `scraping-long-running` | [bcharleson/webscraping-skill](https://github.com/bcharleson/webscraping-skill) (MIT) | Long jobs: tmux, Crawl4AI, checkpoints/resume, rate limits. |
| `python-web-scraping` | [Mindrally/skills](https://github.com/Mindrally/skills) (Apache-2.0) | requests + BeautifulSoup through Selenium/Playwright best practices. |
| `scrapy-web-scraping` | Mindrally/skills (Apache-2.0) | Scrapy spiders, pipelines, middlewares. |
| `beautifulsoup-parsing` | Mindrally/skills (Apache-2.0) | HTML parsing with BeautifulSoup. |
| `playwright` | Mindrally/skills (Apache-2.0) | Playwright browser automation. |
| `puppeteer-automation` | Mindrally/skills (Apache-2.0) | Puppeteer browser automation. |
| `selenium-automation` | Mindrally/skills (Apache-2.0) | Selenium browser automation. |

## Also available as plugins (not copied here)

These are paid services that ship as plugins with MCP servers. Install them from the Claude plugin directory instead of copying them: **Bright Data** (anti-bot unlocker, 40+ site extractors), **Apify** (`apify-ultimate-scraper`, Actor marketplace), **Zyte Web Data**, **Olostep**, **Nimble**.

Scrape responsibly: respect each site's terms of service and robots.txt, and the privacy law that applies to the data.
