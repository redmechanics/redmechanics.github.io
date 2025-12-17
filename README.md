# Red Mechanic AB Website

A modern, professional, low-bandwidth website built with pure HTML and Pico CSS.

## Features

- **Lightweight**: ~30-50KB per page load
- **No build process**: Pure HTML files, no compilation needed
- **Responsive**: Works on all devices (mobile, tablet, desktop)
- **Modern design**: Clean, professional aesthetic with Pico CSS framework
- **Fast**: Loads in <100ms
- **Accessible**: Semantic HTML with proper structure
- **No JavaScript**: Pure HTML/CSS for maximum compatibility

## Tech Stack

- Pure HTML5
- [Pico CSS v2](https://picocss.com) - Minimal CSS framework (~10KB)
- Formspree for contact form

## Pages

1. **index.html** - Homepage with company overview
2. **what-we-do.html** - Services and expertise
3. **clients.html** - Client portfolio and case studies
4. **contact.html** - Contact form
5. **privacy.html** - Privacy policy
6. **copyright.html** - Copyright and licensing information

## Deployment

### Option 1: GitHub Pages

1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select branch (usually `main`) and root directory
4. Your site will be live at `https://username.github.io/repo-name`

### Option 2: Any Static Host

Upload all HTML files to:
- Netlify
- Vercel
- Cloudflare Pages
- Any web server

## Local Development

Simply open `index.html` in any web browser. No server required!

For a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

Then visit `http://localhost:8000`

## Customization

### Colors

The primary red color is defined in the `:root` CSS variables in each file:

```css
:root {
    --pico-primary: #dc2626;
    --pico-primary-hover: #b91c1c;
    --pico-primary-focus: rgba(220, 38, 38, 0.125);
}
```

Change these values to customize the brand color.

### Contact Form

The contact form uses Formspree (https://formspree.io/f/moqzlpnb). To use your own:

1. Sign up at formspree.io
2. Create a new form
3. Replace the action URL in `contact.html`

## Performance

- Pico CSS: ~10KB (loaded from CDN)
- HTML per page: ~5-15KB
- Total page weight: ~15-25KB (excluding CDN cache)
- No JavaScript
- No tracking scripts
- No external fonts

## Browser Support

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

MIT License - See copyright.html for details

## Contact

info@redmechanic.com
