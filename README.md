# Personal Links Page

A tiny, elegant personal links page featuring:
- Your name and avatar
- 4 social media links (Twitter, GitHub, LinkedIn, Instagram)
- Dark theme support using CSS prefers-color-scheme
- Responsive design
- Semantic HTML structure

## Features

- **Dark Theme**: Automatically adapts to user's system preference
- **Responsive**: Looks great on mobile, tablet, and desktop
- **Semantic HTML**: Proper structure for accessibility and SEO
- **Social Icons**: Uses Font Awesome for clean, recognizable icons
- **Smooth Transitions**: Hover effects and color transitions
- **Minimal CSS**: Clean, maintainable styling with CSS variables

## File Structure

```
personal-links-page/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with dark theme
├── script.js           # Placeholder for interactivity
├── assets/
│   ├── avatar.png      # Your avatar image (200x200px recommended)
│   └── favicon.ico     # Site favicon (16x16px recommended)
└── README.md           # This file
```

## Customization

1. **Replace placeholder images**:
   - Replace `assets/avatar.png` with your actual avatar (200x200px)
   - Replace `assets/favicon.ico` with your favicon (16x16px)

2. **Update personal information**:
   - Edit `index.html` to change:
     - Your name in the `<title>` and `<h1>` tags
     - Social media URLs in the `<a>` href attributes
     - Meta description if desired

3. **Adjust colors** (optional):
   - Modify CSS variables in `style.css`:
     - `--bg-light`: Light mode background
     - `--fg-light`: Light mode foreground
     - `--bg-dark`: Dark mode background
     - `--fg-dark`: Dark mode foreground
     - `--accent`: Accent color for borders and hover effects

## Deployment

This project is configured to deploy automatically to Vercel when pushed to GitHub.

### Manual Deployment to Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Login: `vercel login`
3. Deploy: `vercel` (follow prompts)

## Development

To run locally:
1. Clone the repository
2. Open `index.html` in your browser
3. No build step required - pure HTML/CSS/JS

## Browser Support

- Chrome 49+
- Firefox 45+
- Safari 10+
- Edge 79+
- Opera 36+

## Credits

- Icons: [Font Awesome](https://fontawesome.com)
- Design inspiration: Minimal personal links pages

## License

MIT - Feel free to use and modify for your personal use.