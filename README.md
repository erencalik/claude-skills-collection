<p align="center"><img src="assets/banner.svg" alt="Claude Skills Collection" width="100%"></p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude-Skills-D97757?style=for-the-badge" alt="Claude Skills">
  <img src="https://img.shields.io/badge/Skills-8-6E56CF?style=for-the-badge" alt="8 skills">
  <img src="https://img.shields.io/badge/Languages-TR%20%7C%20EN-1F6FEB?style=for-the-badge" alt="TR | EN">
  <img src="https://img.shields.io/badge/License-MIT-2EA043?style=for-the-badge" alt="MIT">
</p>

<p align="center"><b>Claude skills for running a content operation end to end: research, planning, writing, design, video rendering and QA.</b><br>
Each skill lives in its own repo and installs with one command.</p>

---

## 🗺️ How they fit together

```mermaid
flowchart LR
    P["Instagram Weekly Content Planner"] --> S["İş Hikayesi İçerik Üretici"]
    S --> C["Instagram Caption ve Carousel"]
    C --> H["Sosyal Medya Metni İnsanlaştırıcı"]
    S --> D["Instagram Carousel Design System"]
    S --> M["Motion Graphics Video Generator"]
    Q["Quote Reels Editing Guide"] --> G["Render & QA Gate"]
    M --> G
```

## 🧰 Skills

### 📈 Instagram growth

| Skill | What it does | Lang |
|---|---|:---:|
| **[Instagram Weekly Content Planner](https://github.com/erencalik/instagram-weekly-content-planner-claude)** | Weekly plan, niche research and post audits, ranked by evidence | ![EN](https://img.shields.io/badge/EN-1F6FEB?style=flat-square) |
| **[Instagram Caption ve Carousel](https://github.com/erencalik/instagram-aciklama-carousel-metni-claude)** | Caption, hashtag, alt metin ve carousel metni, kontrol makbuzuyla | ![TR](https://img.shields.io/badge/TR-E30A17?style=flat-square) |
| **[Sosyal Medya Metni İnsanlaştırıcı](https://github.com/erencalik/sosyal-medya-metni-insanlastirma-claude)** | Türkçe metinden yapay zeka izlerini temizler, beş kontrolle puanlar | ![TR](https://img.shields.io/badge/TR-E30A17?style=flat-square) |

### 🎨 Content production

| Skill | What it does | Lang |
|---|---|:---:|
| **[İş Hikayesi İçerik Üretici](https://github.com/erencalik/is-hikayesi-icerik-uretici-claude)** | Şirket ve kurucu hikayelerinden doğrulanmış carousel ve Reels | ![TR](https://img.shields.io/badge/TR-E30A17?style=flat-square) |
| **[Instagram Carousel Design System](https://github.com/erencalik/instagram-carousel-design-system-claude)** | From a brand interview to pixel-checked 1080×1350 PNG slides | ![EN](https://img.shields.io/badge/EN-1F6FEB?style=flat-square) |
| **[Motion Graphics Video Generator](https://github.com/erencalik/motion-graphics-video-generator-claude)** | One request to a scored MP4: HTML, headless Chromium, ffmpeg | ![EN](https://img.shields.io/badge/EN-1F6FEB?style=flat-square) |

### 🎬 Video operations

| Skill | What it does | Lang |
|---|---|:---:|
| **[Quote Reels Editing Guide](https://github.com/erencalik/quote-reels-editing-guide-claude)** | One-page editing spec for a daily quote Reels series | ![EN](https://img.shields.io/badge/EN-1F6FEB?style=flat-square) |
| **[Render & QA Gate](https://github.com/erencalik/video-render-qa-gate-claude)** | Hang-proof rendering and a pre-delivery quality gate | ![EN](https://img.shields.io/badge/EN-1F6FEB?style=flat-square) |

Skills that work on Turkish text and Turkish sources are written in Turkish; everything else is in English.

## ⚙️ Install

```bash
git clone https://github.com/erencalik/<repo>.git ~/.claude/skills/<repo-without-claude-suffix>
```

On claude.ai, download a repo as a ZIP (Code → Download ZIP) and upload it under Settings → Capabilities → Skills.

## 🧭 Design principles

- **Writes and reads, never publishes.** No skill posts or schedules anything without the user's approval.
- **No invented numbers.** Unknown values stay marked as `{{number}}`.
- **Checks itself before showing.** Renders, scores and check receipts are reviewed before they reach the user.
- **Credits its sources.** Adapted methods name their original authors.

## 🇹🇷 Türkçe özet

Bir içerik operasyonunu (araştırma, planlama, metin, tasarım, video render, kalite kontrol) uçtan uca yürütmek için geliştirdiğim Claude skill'leri. Türkçe metin ve Türk kaynaklarıyla çalışan skill'ler Türkçe, diğerleri İngilizce yazıldı. Her biri kendi reposunda ve tek komutla kurulur.

## 📄 License

Every repo is MIT licensed.
