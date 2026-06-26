# 🎬 Toffee UI - Premium Streaming Platform Design

A modern, responsive streaming platform UI with Toffee's signature pink branding and dark theme.

## ✨ Features

### 🎯 Core Features
- **Hero Section** - Dynamic auto-rotating carousel with featured content
- **Trending Section** - Real-time trending content with badges
- **Multiple Categories** - Movies, Series, and Sports sections
- **Search & Filter** - Quick search with genre and rating filters
- **User Profile** - Dropdown menu with profile options
- **Video Player** - Modal-based video player
- **Watchlist** - Add content to personal watchlist
- **Social Sharing** - Share content with friends

### 🎨 Design Elements
- **Color Scheme**: Toffee Pink (#E91E63) & Magenta (#FF1493)
- **Dark Theme**: OLED-friendly dark background
- **Responsive Design**: Mobile, Tablet, and Desktop optimized
- **Smooth Animations**: Hover effects and transitions
- **Modern Typography**: Plus Jakarta Sans font
- **Interactive Cards**: Hover overlays with ratings and metadata

### 📱 Responsive Breakpoints
- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px
- **Large Desktop**: > 1200px

## 🚀 Getting Started

### Installation
1. Download `toffee-index.html`
2. Optionally, link `toffee-styles.css` for modular styling
3. Open in your web browser

### No Dependencies Required
- Pure HTML/CSS/JavaScript
- No external libraries (CSS framework independent)
- Works offline

## 📁 File Structure

```
toffee-ui/
├── toffee-index.html      # Main HTML file with all features
├── toffee-styles.css      # Separated CSS (optional)
└── toffee-README.md       # This file
```

## 🎮 Interactive Features

### Hero Carousel
```javascript
// Auto-rotates every 5 seconds
// Click navigation buttons to manually browse
```

### Search Functionality
```javascript
// Toggle search bar with magnifying glass icon
// Filter by Movies, Series, Sports, or Latest
```

### User Profile Dropdown
```javascript
// Click profile icon to open menu
// Options: Profile, Watchlist, Continue Watching, Downloads, Settings, Logout
```

### Video Player
```javascript
// Click play button on any content card
// Opens modal video player with controls
```

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Pink | #E91E63 | Buttons, links, highlights |
| Secondary Magenta | #FF1493 | Gradients, accents |
| Dark | #0a0a0a | Background |
| Darker | #141414 | Cards, modals |
| Light | #f5f5f5 | Text highlights |
| Text | #ffffff | Primary text |
| Text Secondary | #b3b3b3 | Secondary text |
| Border | #2a2a2a | Dividers |

## 🔧 Customization

### Change Primary Color
```css
:root {
    --primary: #YOUR_COLOR;
    --secondary: #YOUR_ACCENT;
}
```

### Add Custom Fonts
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT" rel="stylesheet">
```

### Modify Content
- Update image URLs in content cards
- Change section titles and descriptions
- Add/remove content categories

## 📊 Section Breakdown

### Header
- Logo with gradient text
- Navigation menu (hidden on mobile)
- Search, notifications, profile icons
- Sticky positioning

### Hero
- Full-width banner with overlay
- Auto-rotating slides
- Title, description, CTA buttons
- 70vh height with responsive sizing

### Content Sections
- **Trending Now**: Most watched this week
- **Popular Movies**: Curated movie selection
- **Binge-Worthy Series**: Latest series
- **Live Sports**: Live streaming content

### Footer
- Company information
- Navigation links
- Legal links
- Social media icons

## 🎥 Video Integration

To add real video streaming:

1. Replace `<div style="background: black;">` in player modal with:
```html
<video controls style="width: 100%; height: 500px;">
    <source src="your-video-url" type="video/mp4">
</video>
```

2. Or integrate with third-party players:
   - HLS.js
   - Plyr
   - Video.js

## 📱 Mobile Optimization

- Bottom navigation for easy thumb access
- Touch-friendly button sizes (min 44px)
- Optimized grid layout for small screens
- Fast-loading images with lazy loading
- Reduced animations on mobile

## ♿ Accessibility

- ARIA labels on buttons
- Semantic HTML structure
- Keyboard navigation support
- High contrast text
- Focus indicators on interactive elements

## 🚀 Performance Tips

1. **Lazy Load Images**
```html
<img src="..." loading="lazy" alt="...">
```

2. **Optimize Images**
   - Use WebP format when possible
   - Compress to < 200KB
   - Use appropriate dimensions

3. **Minify CSS/JS**
   - Remove unused styles
   - Combine files
   - Use CDN for assets

## 🔐 Security

- Sanitize user inputs
- Use HTTPS for all external resources
- Implement CORS headers
- Validate video sources

## 🤝 Contributing

To improve Toffee UI:
1. Test on multiple devices
2. Report bugs with screenshots
3. Suggest new features
4. Share your implementations

## 📄 License

Free to use and modify for personal and commercial projects.

## 🎯 Browser Support

✅ Chrome/Edge (Latest)
✅ Firefox (Latest)
✅ Safari (Latest)
✅ Mobile Browsers

## 📞 Support

For issues and questions:
- Check the HTML comments in the code
- Review the CSS variable definitions
- Test in different browsers
- Clear browser cache if styles don't update

## 🎁 Bonus Features

- Dark mode (default)
- Smooth scroll behavior
- Ripple button effects
- Loading animations
- Modal transitions
- Dropdown menus
- Search functionality
- Filter system
- Responsive grids
- Social sharing

## 📈 Future Enhancements

- Real-time content API integration
- User authentication
- Payment gateway
- Recommendation algorithm
- Offline viewing
- Multiple language support
- Accessibility improvements
- Progressive Web App (PWA)

---

**Made with ❤️ for streaming enthusiasts**

Enjoy Toffee UI! 🎬✨
