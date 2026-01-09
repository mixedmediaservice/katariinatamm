# SEO & Technical Site Audit - katariinatamm.com

Generated: January 9, 2025

## 1) Project Overview

**Stack:** Plain HTML/CSS/JS static site
- No build process or frameworks detected
- Single-page application with modal overlays
- Embedded CSS and JavaScript inline within HTML
- External stylesheet: styles.css

**Deployment:** No deployment configuration files found
- No package.json, netlify.toml, vercel.json, or GitHub Actions
- No build scripts or CI/CD configuration
- Likely deployed via simple file upload or GitHub Pages

## 2) File Map

### Directory Structure
```
katariinatamm/
├── .DS_Store
├── .claude/
│   └── settings.local.json
├── .idea/
│   ├── katariinatamm.iml
│   ├── modules.xml
│   ├── vcs.xml
│   └── workspace.xml
├── android-chrome-192x192.png (3KB)
├── android-chrome-512x512.png (8KB)
├── apple-touch-icon.png (3KB)
├── favicon-16x16.png (0KB)
├── favicon-32x32.png (1KB)
├── favicon.ico (0KB)
├── hero-image.avif (22KB)
├── hero-image.jpg (224KB)
├── hero-image.webp (42KB)
├── index.html (28KB)
├── katariina-tamm-1200x630.jpg (411KB)
├── katariinatammcom.zip
├── logo.png (43KB)
├── site.webmanifest
├── sitemap.xml
└── styles.css
```

### HTML Files
- `index.html` - Main homepage (28,454 bytes)

### Key Files
- `sitemap.xml` - XML sitemap (442 bytes)
- `site.webmanifest` - Web app manifest
- `robots.txt` - **MISSING**

## 3) Indexing & Crawl Controls

### robots.txt
**Status:** ❌ NOT FOUND
- No robots.txt file exists in the root directory

### sitemap.xml
**Status:** ✅ Present but contains stale reference
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://katariinatamm.com/</loc>
    <lastmod>2025-11-03</lastmod>
    <changefreq>monthly</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://katariinatamm.com/index-video.html</loc>
    <lastmod>2025-11-03</lastmod>
    <changefreq>yearly</changefreq>
    <priority>0.8</priority>
  </url>
</urlset>
```

### Meta Robots Tags
**index.html (line 11):**
```html
<meta content="index,follow,max-image-preview:large" name="robots"/>
```

## 4) Canonicals + hreflang

### index.html
- **Title:** "Katariina Tamm - Actor"
- **Meta Description:** "Estonian actor Katariina Tamm - RADA graduate, theatre performer, and Estonian Annual Theatre Awards nominee. Official website."
- **Canonical:** `https://katariinatamm.com/` (line 12)

### Issues Found
✅ No duplicate titles/descriptions (only one HTML file)
✅ Canonical URL properly set
❌ No hreflang tags (not applicable for single-language site)

## 5) Open Graph + Twitter

### index.html Open Graph Tags
```html
<meta content="website" property="og:type"/>
<meta content="https://katariinatamm.com/" property="og:url"/>
<meta content="Katariina Tamm" property="og:site_name"/>
<meta content="Katariina Tamm - Actor" property="og:title"/>
<meta content="Estonian actor Katariina Tamm - RADA graduate, theatre performer, and Estonian Annual Theatre Awards nominee. Official website." property="og:description"/>
<meta content="https://katariinatamm.com/katariina-tamm-1200x630.jpg?v=4" property="og:image"/>
<meta content="1200" property="og:image:width"/>
<meta content="630" property="og:image:height"/>
<meta content="Portrait of actor Katariina Tamm" property="og:image:alt"/>
```

### Twitter Card Tags
```html
<meta content="summary_large_image" name="twitter:card"/>
<meta content="https://katariinatamm.com/" name="twitter:url"/>
<meta content="Katariina Tamm - Actor" name="twitter:title"/>
<meta content="Estonian actor Katariina Tamm - RADA graduate, theatre performer, and Estonian Annual Theatre Awards nominee. Official website." name="twitter:description"/>
<meta content="https://katariinatamm.com/katariina-tamm-1200x630.jpg?v=4" name="twitter:image"/>
<meta content="Portrait of actor Katariina Tamm" name="twitter:image:alt"/>
```

### Consistency Check
✅ og:url matches canonical URL
✅ All required Open Graph tags present
✅ Twitter card properly configured
✅ Image dimensions specified

## 6) Structured Data

### JSON-LD Block 1: Person Schema (lines 39-51)
```json
{
  "@context":"https://schema.org",
  "@type":"Person",
  "name":"Katariina Tamm",
  "jobTitle":"Actor",
  "url":"https://katariinatamm.com/",
  "image":"https://katariinatamm.com/katariina-tamm-1200x630.jpg",
  "knowsLanguage":["et","en"],
  "nationality":"Estonia",
  "sameAs":["https://www.imdb.com/name/nm5518685/"]
}
```

### JSON-LD Block 2: WebSite Schema (lines 53-61)
```json
{
  "@context":"https://schema.org",
  "@type":"WebSite",
  "url":"https://katariinatamm.com/",
  "name":"Katariina Tamm",
  "inLanguage":"en"
}
```

### Validation Status
✅ Both JSON-LD blocks are valid JSON
✅ Proper schema.org context and types
✅ Person schema includes relevant properties for an actor
⚠️ Missing properties: birthDate, birthPlace, gender, alumniOf (could enhance schema)

## 7) Internal Links + Status (local)

### All References Checked
| Source File | Reference | Type | Status |
|-------------|-----------|------|---------|
| index.html | apple-touch-icon.png | Icon | ✅ EXISTS |
| index.html | favicon-32x32.png | Icon | ✅ EXISTS |
| index.html | favicon-16x16.png | Icon | ✅ EXISTS |
| index.html | site.webmanifest | Manifest | ✅ EXISTS |
| index.html | favicon.ico | Icon | ✅ EXISTS |
| index.html | styles.css | Stylesheet | ✅ EXISTS |
| index.html | hero-image.jpg | Background | ✅ EXISTS |
| index.html | mailto:contact@katariinatamm.com | Email | ✅ VALID |
| index.html | https://www.imdb.com/name/nm5518685/ | External | ✅ VALID |
| index.html | #bio | Anchor | ✅ EXISTS |
| index.html | #showreel | Anchor | ✅ EXISTS |

### Broken References
❌ **NONE FOUND** - All local asset references are valid

## 8) Performance Hygiene (static checks)

### Image Analysis
| File | Size | Type | Issues |
|------|------|------|---------|
| android-chrome-192x192.png | 3KB | Icon | ✅ Good |
| android-chrome-512x512.png | 8KB | Icon | ✅ Good |
| apple-touch-icon.png | 3KB | Icon | ✅ Good |
| favicon-16x16.png | 0KB | Icon | ✅ Good |
| favicon-32x32.png | 1KB | Icon | ✅ Good |
| favicon.ico | 0KB | Icon | ✅ Good |
| hero-image.avif | 22KB | Hero | ✅ Excellent (modern format) |
| hero-image.jpg | 224KB | Hero | ✅ Reasonable for hero image |
| hero-image.webp | 42KB | Hero | ✅ Good (modern format) |
| katariina-tamm-1200x630.jpg | 411KB | Social | ⚠️ Large but within acceptable range for social sharing |
| logo.png | 43KB | Logo | ✅ Good |

### Performance Issues
⚠️ **Social share image is 411KB** - Consider optimization
✅ **Modern image formats available** (AVIF, WebP)
❌ **No width/height attributes** on images in HTML
❌ **No responsive image implementation** (srcset/sizes)

## 9) Favicons / App Icons

### Icon Files Present
✅ favicon.ico (0KB)
✅ favicon-16x16.png (1KB)
✅ favicon-32x32.png (1KB)
✅ apple-touch-icon.png (3KB) - 180x180
✅ android-chrome-192x192.png (3KB)
✅ android-chrome-512x512.png (8KB)

### HTML References
✅ All icon files properly referenced in HTML head
✅ Web app manifest linked
✅ Appropriate sizes and types specified

### Web App Manifest (site.webmanifest)
```json
{
  "name": "Katariina Tamm",
  "short_name": "KT",
  "start_url": "/",
  "display": "standalone",
  "background_color": "#000000",
  "theme_color": "#000000",
  "icons": [
    {
      "src": "android-chrome-192x192.png",
      "sizes": "192x192",
      "type": "image/png",
      "purpose": "any maskable"
    },
    {
      "src": "android-chrome-512x512.png",
      "sizes": "512x512",
      "type": "image/png",
      "purpose": "any maskable"
    }
  ]
}
```

### Icon Setup Status
✅ **Complete favicon implementation**
⚠️ Missing iOS splash screen icons
⚠️ No 180x180 icon in manifest (only references Android icons)

## 10) Server/Redirect Hints

### Configuration Files
❌ **No server configuration files found:**
- No .htaccess
- No _redirects (Netlify)
- No vercel.json
- No netlify.toml
- No nginx config files

### Implications
⚠️ **No redirect rules** - trailing slash handling undefined
⚠️ **No HTTPS enforcement** rules
⚠️ **No compression configuration**
⚠️ **No caching headers** configuration

## 11) Top 10 Likely Issues

### 🔴 CRITICAL (Fix Immediately)
1. **Stale sitemap.xml reference** - References deleted `index-video.html`
   - **File:** sitemap.xml (line 10-14)
   - **Fix:** Remove the index-video.html URL entry

### 🟡 HIGH PRIORITY
2. **Missing robots.txt**
   - **Issue:** No crawl directives for search engines
   - **Fix:** Create robots.txt with sitemap reference

3. **Large social sharing image (411KB)**
   - **File:** katariina-tamm-1200x630.jpg
   - **Fix:** Optimize without losing quality

4. **No responsive images**
   - **File:** index.html (hero-image references)
   - **Fix:** Implement srcset/sizes or picture element

### 🟠 MEDIUM PRIORITY  
5. **Missing width/height on images**
   - **Issue:** Potential layout shift (CLS)
   - **Fix:** Add dimensions to prevent reflow

6. **No server configuration**
   - **Issue:** No caching, compression, or redirect rules
   - **Fix:** Add appropriate config for hosting platform

7. **Inline CSS (28KB file size)**
   - **File:** index.html contains large CSS blocks
   - **Fix:** Move complex styles to external files

### 🔵 LOW PRIORITY
8. **Incomplete JSON-LD schema**
   - **Enhancement:** Add birthDate, education details
   - **File:** index.html lines 39-51

9. **Missing iOS splash screen icons**
   - **Enhancement:** Add apple-touch-startup-image
   - **File:** Requires new icon assets

10. **No 180x180 icon in manifest**
    - **File:** site.webmanifest
    - **Fix:** Add apple-touch-icon to manifest icons array

---

## Summary
The site is generally well-structured with good SEO fundamentals, but has some technical debt around sitemap maintenance and performance optimization. The most critical issue is the outdated sitemap reference that needs immediate attention.