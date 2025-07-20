# Project Structure

## Root Directory Layout
```
/
├── index.html              # Main landing page (Duck Duck Clicker 3D)
├── README.md              # Project documentation
├── duck-duck-clicker/     # Classic 2D game subdirectory
│   └── index.html         # Classic game landing page
├── images/                # Static assets
│   ├── logo.png          # Site logo
│   └── duckduckclicker.png # Game thumbnail
├── .git/                  # Git repository
└── .kiro/                 # Kiro AI assistant configuration
    └── steering/          # AI guidance documents
```

## File Organization Principles

### HTML Structure
- **index.html** - Main entry point featuring Duck Duck Clicker 3D
- **duck-duck-clicker/index.html** - Separate page for classic 2D version
- Both pages follow identical structure and styling patterns

### Asset Management
- **images/** - All static images (logos, thumbnails, placeholders)
- Relative path references from subdirectories (e.g., `../images/logo.png`)
- Consistent naming convention using lowercase and hyphens

### Page Structure Pattern
Each HTML page follows this consistent structure:
1. SEO-optimized `<head>` with meta tags, analytics, and external resources
2. Sticky navigation bar with logo and menu
3. Hero section with game title and description
4. Game iframe container with interaction controls
5. Content sections (about, features, how-to-play)
6. Game recommendations grid
7. Footer with copyright

### Styling Conventions
- Tailwind CSS classes for all styling
- Custom CSS limited to font family and aspect ratio utilities
- Consistent color scheme: neutral grays with indigo accents
- Responsive design with mobile-first approach

### JavaScript Organization
- Inline scripts in HTML files
- Event-driven interactions (fullscreen, button toggles)
- No external JS files - keep it simple and contained

## Navigation Structure
- Root (`/`) - Duck Duck Clicker 3D (flagship game)
- `/duck-duck-clicker/` - Classic 2D version
- Relative linking between pages
- Breadcrumb-style navigation in subdirectories