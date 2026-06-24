# Free AI Tools Dataset 🤖

A curated, regularly-updated dataset of **325+ free and free-trial AI tools** across **25 categories** — in clean **CSV** and **JSON**. Ready to drop into your own projects, chatbots, spreadsheets, or research.

**Live, browsable version → [autoventure.live](https://autoventure.live)**
**Always-fresh download → [autoventure.live/dataset](https://autoventure.live/dataset/)**

---

## What's in it

Every entry is a real, working AI tool with a free tier or free trial — hand-checked, not scraped spam. Each row has:

| Field | Description |
|-------|-------------|
| `name` | Tool name |
| `category` | One of 25 categories (Audio, Code, Design, SEO, Video…) |
| `pricing` | `Free`, `Free Trial`, or `Freemium` |
| `description` | One-line summary of what it does |
| `website` | Official tool URL |
| `review_url` | Full review on [autoventure.live](https://autoventure.live) |
| `slug` | URL-safe id, handy as a primary key |

## Files

- **`ai-tools.csv`** — open in Excel / Google Sheets / pandas
- **`ai-tools.json`** — for code, APIs, and apps

```python
import csv
tools = list(csv.DictReader(open("ai-tools.csv")))
print(len(tools), "AI tools")
seo = [t for t in tools if t["category"] == "SEO"]
```

```js
const tools = require("./ai-tools.json");
console.log(`${tools.length} AI tools`);
```

## Categories

Audio · Automation · Chatbot · Code · Customer Service · Data · Design · Ecommerce · Education · Email · Finance · Health · Hiring · Image Generators · Legal · Marketing · Meeting · Productivity · Real Estate · Research · SEO · Social Media · Translation · Video · Writing

## Updates

This dataset is regenerated from the live directory. For the freshest copy, always pull from **[autoventure.live/dataset](https://autoventure.live/dataset/)**. Star ⭐ this repo to follow along.

## License

Released under **[Creative Commons Attribution 4.0 (CC BY 4.0)](LICENSE)**. Free for any use — commercial included. The only ask: **credit [AutoVenture (autoventure.live)](https://autoventure.live)** with a link.

## Found this useful?

- ⭐ Star the repo
- 🔗 Browse the full reviews & side-by-side comparisons at **[autoventure.live](https://autoventure.live)**
- 🐛 Spot a tool that's missing or changed? [Open an issue](../../issues) or [suggest it on the site](https://autoventure.live).
