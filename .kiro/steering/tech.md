# Technology Stack

## Frontend Technologies
- **HTML5** - Semantic markup with proper meta tags for SEO
- **CSS Framework** - Tailwind CSS via CDN for styling
- **JavaScript** - Vanilla ES6+ for interactive features
- **Fonts** - Google Fonts (Poppins family)

## External Services
- **Game Hosting** - itch.io embedded iframes for game content
- **Analytics** - Google Analytics (gtag.js) and Microsoft Clarity
- **CDN** - Tailwind CSS and Google Fonts via CDN

## Build System
This is a static website with no build process required. Files are served directly.

### Development Workflow
- Direct file editing for HTML/CSS/JS
- No compilation or bundling steps
- Static file serving for deployment

### Common Commands
Since this is a static site, typical commands would be:

```bash
# Local development (simple HTTP server)
python -m http.server 8000
# or
npx serve .

# File operations
open index.html  # Preview main page
open duck-duck-clicker/index.html  # Preview classic version
```

## Browser Compatibility
- Modern browsers supporting ES6+
- Mobile-responsive design
- Fullscreen API support for enhanced game experience

## Performance Considerations
- External CDN usage for faster loading
- Optimized images in /images directory
- Minimal JavaScript for fast page loads
- Iframe embedding for game isolation