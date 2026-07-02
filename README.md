# Te Pā Tūwatawata — A Kaupapa Māori Course

A six-module kaupapa Māori course on **whakapapa o te raraunga**, AI, tikanga, and sovereign digital futures. Free to fork, adapt, and translate.

Published live at **[te-pa.org](https://te-pa.org)** and mirrored here as a portable, forkable, linkable course you can drop into any site.

## Ngā wāhanga · The modules

1. **[Whakapapa o te raraunga](modules/module-1.html)** — The whakapapa of data: where does data come from, and who does it belong to?
2. **[Te Pā Tūwatawata hei tauira](modules/module-2.html)** — Te Pā Tūwatawata as a model for Indigenous-led digital infrastructure.
3. **[AI me te raupatu matihiko](modules/module-3.html)** — AI and digital extraction: tracing the colonial logic inside machine learning.
4. **[Tikanga, ture, mana whakahaere](modules/module-4.html)** — Tikanga, law, and governance: how Māori legal frameworks challenge tech power.
5. **[Hoahoa tika](modules/module-5.html)** — Designing ethical systems: what does a decolonised AI architecture look like?
6. **[He anamata rangatira](modules/module-6.html)** — Sovereign digital futures: building Māori-controlled infrastructure for generations.

Plus a **[rhizome map](modules/rhizome.html)** of the course and a **[motifs guide](motifs/index.html)** (koru, kōwhaiwhai, niho taniwha, pā tūwatawata, tākarangi, unaunahi).

## Structure

```
te-pa-course/
├── index.html            # course landing page
├── modules/              # 6 modules + rhizome map
├── motifs/               # motifs guide (koru, kōwhaiwhai, etc.)
├── assets/               # shared CSS + motif SVGs
├── social-kit/           # images embedded in modules
├── manifest.json         # PWA manifest
└── og-image.{png,svg}
```

Pure HTML + CSS. No build step. Serve any way you like — GitHub Pages, Netlify, Vercel, or `python -m http.server`.

## Run locally

```bash
git clone https://github.com/robertmccallnz/te-pa-course.git
cd te-pa-course
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

- **GitHub Pages:** enabled on `main` — see [Settings → Pages](../../settings/pages).
- **Netlify / Vercel:** point at the repo root; no build command needed. Publish directory `/`.
- **Substack / your own site:** iframe individual modules, or copy the HTML directly.

## Fork &amp; adapt

This is designed to be forked. Common patterns:

- **Translate** — copy `modules/` into `modules-mi/`, `modules-en/`, etc., and translate.
- **Rebrand** — edit `assets/kiwi-dialectic.css` for typography and colour.
- **Reuse motifs** — the SVG motifs in `assets/motifs/` are yours to use under the same licence.

## Licence

**[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).** Attribute to **The Kiwi Dialectic** and preserve the licence. Commercial use permitted with attribution.

## Whakapapa

Written by **Robert McCall** for **[The Kiwi Dialectic](https://www.kiwidialectic.com)**. Ngā mihi ki ngā hapori Māori nāna i whakatakoto te whāriki — to the Māori communities who laid the mat this course stands on.

Companion courses: [ai-warrior](https://github.com/robertmccallnz/ai-warrior) · [ai-literacy-for-families](https://github.com/robertmccallnz/ai-literacy-for-families) · [cooperative-aotearoa](https://github.com/robertmccallnz/cooperative-aotearoa).
