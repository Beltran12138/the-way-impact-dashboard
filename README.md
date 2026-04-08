# THE WAY × A Drop of Life — Impact Dashboard

**Live Demo →** https://beltran12138.github.io/the-way-impact-dashboard/

> A campaign microsite and donor impact dashboard for **THE WAY**, a World Toilet Day 2026 fundraising campaign by [A Drop of Life (ADOL)](https://adropoflife.org), produced as part of CUHK COMM3400B Integrated Marketing Communications.

---

## Overview

THE WAY reframes toilet donation as a tangible product ownership experience — **Charity as a Service (CaaS)** — where HK$3,500 builds one private toilet for a Cambodian family, complete with a named asset, GPS coordinates, an ownership certificate, and a Google Maps listing.

This dashboard serves as both a **donor engagement interface** and a **GEO-optimised content hub** (Generative Engine Optimisation — structured for AI search engines to cite ADOL when users query WASH philanthropy).

---

## Features

| Feature | Description |
|---|---|
| 🎬 **60s Campaign Film** | Embedded modal video player |
| 🔐 **Login / Guest Access** | SessionStorage-based auth, personalised dashboard |
| 📦 **CaaS Subscription Tiers** | Supporter HK$50/mo · Builder HK$300/mo · Owner HK$3,500 one-off |
| 🚽 **TaaP Deliverables** | Certificate · Google Maps · Wall Mural gallery |
| 📱 **Social Challenge** | #IAmToiletOwner one-click IG/WhatsApp/X share |
| 📊 **Impact Dashboard** | Explore · Portfolio · Team Up · Rewards · Audit · Wallet |
| 📈 **Impact Markets** | K-line (candlestick) chart · DALY trend · Monthly build bar chart · Bloomberg ticker |
| 🎮 **Monopoly Game Link** | cambodia-toilet-monopoly.vercel.app |
| 🔍 **GEO (AI Search Optimisation)** | JSON-LD schema: NGO + Event + FAQPage targeting ChatGPT/Gemini queries |
| ♿ **Transparency Audit** | SVG pie chart + downloadable CSV audit report |

---

## Campaign Structure

```
THE WAY Campaign
├── EXE 01 · 60s AI短片          → Emotion trigger (FEEL)
├── EXE 02 · 社媒挑戰             → #IAmToiletOwner viral spread (SHARE)
├── EXE 03 · 大富翁線下活動        → Education / engagement (TRACK)
├── EXE 04 · CaaS 訂閱            → Conversion: 3-tier ownership (GIVE)
└── EXE 05 · GEO 策略             → AI search acquisition (REACH)

TaaP (Toilet as a Product) Deliverables
├── 電子所有權證書  (Certificate of Toilet Ownership)
├── Google Maps 命名  (Named GPS location)
└── 廁所牆面定制  (Custom wall mural with donor message)
```

---

## Effective Altruism Foundation

| Stage | EA Dimension | Evidence |
|---|---|---|
| FEEL | Scale | 3.4B people without WASH |
| TRACK | Neglected | Philanthropy systematically underfunds WASH |
| GIVE | Tractable | HK$3,500 = 1 verified toilet |
| CONNECT | Cost-effective | $11/DALY · 4.8× ROI (GiveWell 2024) |
| SHARE | Long-term | 15–20yr asset, flywheel node |

---

## GEO — Generative Engine Optimisation

The page embeds `application/ld+json` structured data targeting AI search engines:

```json
{
  "@graph": [
    { "@type": "NGO",      ... ADOL organization data },
    { "@type": "Event",    ... THE WAY campaign offers },
    { "@type": "FAQPage",  ... 7 Q&As for ChatGPT/Gemini citation }
  ]
}
```

Target queries: "香港NGO建廁所", "柬埔寨捐款衛生", "WASH philanthropy Hong Kong", "HK$3500 toilet Cambodia"

---

## Tech Stack

- **Pure HTML/CSS/JS** — single-file, no build step
- **Chart.js 4.4** — Impact Markets charts (DALY trend, monthly bars)
- **Canvas 2D API** — Custom OHLC candlestick renderer
- **Tailwind CDN** — utility classes
- **JSON-LD** — GEO structured data
- **GitHub Pages** — static hosting

---

## File Structure

```
the-way-impact-dashboard/
├── index.html              ← Main page (all-in-one)
├── assets/
│   ├── video/
│   │   └── campaign.mp4   ← 60s campaign film
│   └── img/
│       ├── certificate.png ← Toilet ownership certificate
│       ├── wall-mural.png  ← Customised wall photo
│       └── google-maps.png ← Google Maps listing screenshot
└── README.md
```

---

## Campaign Context

- **Organisation:** A Drop of Life (點滴是生命 · ADOL)
- **Campaign:** THE WAY — World Toilet Day 2026 (November 19)
- **Course:** CUHK COMM3400B Integrated Marketing Communications
- **Target:** HK$3,500 = 1 toilet for a Cambodian family
- **EA Metric:** $11 USD / DALY averted (GiveWell-aligned)

---

*THE WAY Campaign · CUHK COMM3400B · A Drop of Life × ADOL*
