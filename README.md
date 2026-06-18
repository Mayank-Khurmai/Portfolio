# Mayank Kumar Khurmai — Portfolio

Personal portfolio of **Mayank Kumar Khurmai**, Senior Data Engineer.
Live at **[mayankkhurmai.in](https://mayankkhurmai.in/)**.

Ultra-modern, fully responsive, dependency-free static site (no build step) —
deploys directly via GitHub Pages.

## Tech
- Hand-written **HTML5 + CSS3 + vanilla JS** (zero frameworks, zero build)
- Dark/light theme with persistence (`localStorage`)
- Animated aurora background, scroll-reveal, animated stat counters, typewriter hero, scroll-spy nav
- Google Fonts: Sora · Inter · JetBrains Mono

## SEO & standards
- Descriptive `<title>` + meta description + keywords
- Open Graph + Twitter Card tags
- JSON-LD `Person` structured data
- `robots.txt`, `sitemap.xml`, canonical URL
- Custom `404.html`, accessible markup, `prefers-reduced-motion` support

## Structure
```
index.html               Main single-page portfolio
404.html                 Custom not-found page
robots.txt / sitemap.xml SEO
CNAME                     Custom domain (mayankkhurmai.in)
portal.html / docs.html  Standalone redirect utilities
assets/
  css/style.css           All styles
  js/script.js            All interactions
  mayank-hero.jpg         Hero portrait + favicon + social share image
  Mayank_Khurmai_Resume.pdf  Downloadable CV
```

To update the resume, replace `assets/Mayank_Khurmai_Resume.pdf`.

## Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (GitHub Pages)
1. Push to the `master` branch.
2. Repo **Settings → Pages** → Source: `master` / root.
3. Custom domain `mayankkhurmai.in` is set via `CNAME`.
4. Enable **Enforce HTTPS** in Settings → Pages.
