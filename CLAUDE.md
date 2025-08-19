# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for the Japan Tourism Association (日本観光振興協会) that provides information about tourism data services. The entire website is in Japanese.

## Project Structure

- **Technology**: Pure HTML5 + CSS3 (no JavaScript, no build process)
- **Main file**: `getting-started.html` - Single page with embedded CSS
- **Documentation**: `/docs/` directory contains downloadable PDFs, CSVs, and text files

## Development Commands

Since this is a static website with no build process:

- **To view the site**: Open `getting-started.html` directly in a browser
- **To deploy**: Upload files directly to any static hosting service
- **No build, test, or lint commands** - This is pure HTML/CSS

## Architecture & Key Patterns

### CSS Structure
- All styles are embedded in `<style>` tags within the HTML file
- Mobile-first responsive design with breakpoints at 768px
- Uses CSS Grid and Flexbox for layout
- JAPAN 47 GO brand color: `#A7001D`

### Content Sections
1. Hero section with service overview
2. Service descriptions with icons
3. Downloadable resources section
4. Contact information footer

### Font Stack
```css
font-family: "Hiragino Sans", "Hiragino Kaku Gothic ProN", "Yu Gothic", "YuGothic", "Meiryo", sans-serif;
```

## Important Notes

- All content must remain in Japanese (日本語)
- The website represents official Japan Tourism Association services
- External links point to:
  - JAPAN 47 GO: https://www.japan47go.travel/ja
  - Tourism Forecast Platform: https://kankouyohou.com
- Contact email: gyoumu@nihon-kankou.or.jp

## File Organization

```
/
├── getting-started.html    # Main webpage
├── README.md              # Project documentation (Japanese)
└── docs/                  # Downloadable resources
    ├── tourism-database-overview.pdf
    ├── sample-static-info.csv
    ├── sample-dynamic-info.csv
    └── [other documentation files]
```

## Maintenance Tasks

When updating this site:
1. Ensure all Japanese text is properly encoded (UTF-8)
2. Test responsive design on mobile devices
3. Verify all download links in the `/docs/` directory work correctly
4. Maintain consistent styling with the JAPAN 47 GO brand