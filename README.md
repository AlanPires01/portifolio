# Alan Pires — Developer Portfolio

A dark, elegant personal portfolio built with **HTML**, **CSS (Sass architecture)** and **PHP** — showcasing full-stack development skills, professional experience and featured projects.

## Tech Stack

| Layer    | Technology                          |
|----------|-------------------------------------|
| Markup   | Semantic HTML5                      |
| Styles   | CSS with Sass architecture (variables, mixins, nesting logic) |
| Scripts  | Vanilla JavaScript (ES6+)           |
| Backend  | PHP 8+ (contact form handler)       |
| Fonts    | Syne · DM Sans · DM Mono (Google Fonts) |
| Hosting  | Any PHP-capable server or Vercel    |

## Project Structure

```
portfolio/
├── index.html          # Main page (all sections)
├── css/
│   └── style.css       # Compiled styles (Sass architecture)
├── js/
│   └── main.js         # Interactions & animations
└── php/
    └── contact.php     # Contact form backend (JSON response)
```

## Features

- **Responsive** — mobile-first, works on all screen sizes
- **Animated skill bars** — triggered on scroll via IntersectionObserver
- **Scroll reveal** — sections animate in as they enter the viewport
- **Contact form** — AJAX submission, PHP validation, rate limiting, email via `mail()`
- **Sticky nav** — transparent on top, frosted glass on scroll
- **Dark elegant theme** — black base, gold accents, Syne display font
- **Zero dependencies** — no jQuery, no frameworks, pure vanilla JS

## Running Locally

### Option 1 — PHP built-in server (full features)
```bash
cd portfolio
php -S localhost:3000
```
Then open http://localhost:3000

### Option 2 — Static (contact form in demo mode)
Open `index.html` directly in a browser. The contact form shows a demo message instead of sending email.

## Deploying

### Vercel (recommended for static + serverless)
```bash
npm i -g vercel
vercel
```

### Traditional PHP host (cPanel, HostGator, etc.)
Upload all files via FTP. The contact form works out of the box.

### GitHub Pages (static only)
The contact form falls back to demo mode gracefully.

## Customizing

All design tokens live in `css/style.css` under `:root`:

```css
:root {
  --gold:   #c9a96e;   /* accent color */
  --bg:     #0a0a0a;   /* main background */
  --text:   #f0f0f0;   /* primary text */
  /* ... */
}
```

## Contact

Alan Pires · alanpires.epdw@gmail.com
# portifolio
