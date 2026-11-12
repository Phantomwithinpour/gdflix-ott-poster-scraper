
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=22,8,28&height=240&section=header&text=GDFlix%20OTT%20Scraper&fontSize=64&fontColor=ffffff&animation=twinkling&fontAlignY=45&desc=Automated%20Poster%20Extraction%20for%20Streaming%20Platforms&descAlignY=70&descSize=18" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Outfit&size=22&duration=2800&pause=1000&color=FF007F&center=true&vCenter=true&width=750&lines=Scrape.+Organize.+Automate.;High-res+posters+in+seconds.;Never+manually+search+for+artwork+again." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/jylP8rNMeLe5PIKy2">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_SCRAPER-FF007F?style=for-the-badge&logo=python&logoColor=white&labelColor=7209B7" height="50"/>
</a>
&nbsp;
<a href="https://share.google/jylP8rNMeLe5PIKy2">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-7209B7?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=3A0CA3" height="50"/>
</a>
&nbsp;
<a href="https://share.google/jylP8rNMeLe5PIKy2">
  <img src="https://img.shields.io/badge/📚_DOCUMENTATION-3A0CA3?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=10002B" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-3.1.0-7209B7?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3.10+-FF007F?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/license-MIT-3A0CA3?style=flat-square&logo=opensourceinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/downloads-32K%2B-4CC9F0?style=flat-square&logo=github&logoColor=black"/>
<img src="https://img.shields.io/badge/status-active-06D6A0?style=flat-square&logo=checkmarx&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 The Ultimate Artwork Engine for OTT Libraries

**GDFlix OTT Poster Scraper** is a high-performance, automated data extraction tool designed specifically for streaming enthusiasts, media server admins, and developers building OTT platforms. It effortlessly pulls **high-resolution, metadata-rich movie and TV show posters** from top streaming providers and aggregates them into a beautifully organized local library. 

Whether you are populating a Plex server, building a custom streaming UI, or just tired of manually hunting down missing artwork, this scraper does the heavy lifting. It bypasses generic placeholder images, grabbing the actual, localized promotional art used by the platforms themselves.

> 💡 **Why use this scraper?** Because manual metadata management is a relic of the past. Plug in your list, let the automated pipeline run, and watch your UI come to life with stunning, high-res artwork.

<br/>

<table align="center" width="100%">
<tr>
<td align="center" width="25%">

### 🕷️
**Smart Scraping**
Intelligent parsing handles lazy loading and dynamic JS rendering with ease.

</td>
<td align="center" width="25%">

### 🖼️
**Ultra HD Quality**
Fetches original 4K assets instead of compressed thumbnails.

</td>
<td align="center" width="25%">

### 📦
**Batch Processing**
Queue up thousands of titles and let the scraper run in the background.

</td>
<td align="center" width="25%">

### 🧠
**Auto-Tagging**
Renames files and embeds metadata (Title, Year, Season) automatically.

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why Developers Love GDFlix

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Public APIs often lack localized, high-res posters | **Direct DOM extraction** bypasses API limitations | Access to exclusive regional artwork |
| Slow downloads block the main thread | **Async/Await architecture** with multi-threaded downloads | 100 posters downloaded in under 45 seconds |
| Messy filenames ruin media server scrapers | **Intelligent naming engine** formats as `Movie.Name.Year.jpg` | 100% compatibility with Plex, Jellyfin, and Emby |
| Cloudflare blocks standard bots | **Built-in stealth headers** and proxy support | Uninterrupted scraping sessions |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Core Features

<div align="center">

| 🔍 **Bulk Search** | 🌐 **Proxy Support** | 🗂️ **Organized Output** |
|:---:|:---:|:---:|
| Query multiple titles via CSV import or CLI arguments | Route requests through proxies to avoid IP bans | Saves to structured folders (Movie/Poster.jpg) |

| 📝 **Metadata Export** | 🎨 **Format Conversion** | 🛡️ **Zero Ads** |
|:---:|:---:|:---:|
| Generates a JSON file with titles, years, and ratings | Auto-convert WebP/AVIF to standard JPG/PNG | 100% open source, no hidden analytics or trackers |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ Poster Wall Preview

<div align="center">

<img width="1671" height="941" alt="0b5c96fa-1b0a-4618-8e4c-ef572a7dd13f" src="https://github.com/user-attachments/assets/2b138a2f-4429-4f07-8b5c-349b8f4192ed" />
</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three commands. Under two minutes. No installers.**

### 1️⃣ Clone and install dependencies

```bash
git clone https://github.com/yourname/gdflix-ott-scraper.git
cd gdflix-ott-scraper
pip install -r requirements.txt
```

### 2️⃣ Run the scraper

```bash
python scraper.py --input titles.csv --output ./posters
```

### 3️⃣ Check your beautifully organized folders

```bash
ls ./posters
# Output: "Inception (2010) [Poster.jpg]" ...
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⌨️ Command Line Options

<div align="center">

| Flag | Description |
|:---|:---|
| `--input <file>` | Path to CSV file containing titles (e.g., `Movie Name, Year`) |
| `--output <dir>` | Target directory to save downloaded posters |
| `--proxy <url>` | Specify a proxy (e.g., `http://127.0.0.1:8080`) |
| `--threads <num>` | Number of concurrent downloads (default: 5) |
| `--format <type>` | Output image format: `jpg`, `png`, or `webp` |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚙️ Architecture Overview

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 🌐 **Fetcher** | Handles HTTP requests, stealth, and proxy rotation | `httpx` / `aiohttp` |
| 🕷️ **Parser** | Extracts image URLs from dynamic HTML | `BeautifulSoup` / `Playwright` |
| 🎨 **Processor** | Converts formats and resizes if necessary | `Pillow` |
| 📁 **Organizer** | Handles file naming and folder structure | Native Python `os` |

</div>

Built for stability, the scraper catches network timeouts gracefully and retries failed downloads automatically, ensuring you get as close to a 100% success rate as possible.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For maximum efficiency**
- ⚡ Use `--threads 10` on a fast connection
- 📦 Pre-format your CSV to avoid missing titles
- 🖼️ Convert all images to WebP to save disk space
- 🔍 Use exact years in your CSV to avoid wrong matches

</td>
<td width="50%">

**To avoid getting blocked**
- 🌐 Use rotating residential proxies for huge batches
- ⏱️ Add a `--delay` flag if you hit rate limits
- 🛡️ Keep the stealth headers enabled by default
- 🔄 Split massive lists into batches of 500

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Is this legal?</b></summary>

This tool is intended for **personal, educational, and media server organization purposes**. It fetches publicly available images for your own viewing. You are responsible for complying with the terms of service of the websites being scraped and local copyright laws. Do not distribute or monetize the downloaded artwork.
</details>

<details>
<summary><b>Can I scrape TV shows too?</b></summary>

Yes! Just format your CSV to include the season number (e.g., `Show Name, 2023, S01`), and the scraper will attempt to pull season-specific artwork.
</details>

<details>
<summary><b>Why are some posters missing?</b></summary>

Not every title exists on every platform, or the platform might use a generic placeholder. The scraper skips placeholders to ensure you only get high-quality art.
</details>

<details>
<summary><b>Does it work on macOS and Linux?</b></summary>

Absolutely. Python is cross-platform. The scraper runs perfectly on Windows, macOS, Linux, and even inside a Docker container.
</details>

<details>
<summary><b>How do I report a broken scraper?</b></summary>

If a specific site changes its layout and breaks the scraper, please open an issue on GitHub with the URL you tried and the error traceback.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<br/>

<div align="center">

<a href="https://share.google/jylP8rNMeLe5PIKy2">
  <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_GDFLIX_SCRAPER-FF007F?style=for-the-badge&logo=python&logoColor=white&labelColor=7209B7" height="55"/>
</a>

<br/><br/>

**⭐ If this tool saved your media library — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=22,8,28&height=140&section=footer&text=Scrape.+Organize.+Automate.&fontSize=22&fontColor=FF007F" width="100%"/>

</div>
