# APEX Athletic Website

## 🏆 Premium Sports Brand Website

A cutting-edge, fully responsive website for APEX Athletic - innovative sports products engineered for peak performance.

### 🌟 Features

- **Ultra-Modern Design**: Premium aesthetic with smooth animations and micro-interactions
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Performance Optimized**: Lightning-fast load times with lazy loading and optimized assets
- **Accessibility**: WCAG 2.1 AA compliant
- **SEO Ready**: Semantic HTML and meta tags for optimal search engine visibility
- **Interactive Elements**: GSAP animations, custom cursor, parallax scrolling

### 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/apex-athletic/website.git
   cd apex-athletic-website
   ```

2. **Install dependencies** (optional, for local development server)
   ```bash
   npm install
   ```

3. **Run locally**
   ```bash
   npm start
   ```
   Or use any static server:
   ```bash
   python3 -m http.server 8000
   ```

4. **Open in browser**
   Navigate to `http://localhost:8000`

### 📂 Project Structure

```
apex-athletic-website/
├── index.html          # Main HTML file
├── css/
│   ├── reset.css      # CSS reset for cross-browser consistency
│   ├── styles.css     # Main styles
│   └── animations.css # Advanced animations and effects
├── js/
│   └── main.js        # Interactive functionality
├── assets/
│   ├── icons/         # SVG icons and favicon
│   └── images/        # Image placeholders
├── package.json       # NPM configuration
├── vercel.json        # Vercel deployment config
└── README.md         # This file
```

### 🎨 Design System

- **Primary Color**: #0066FF (Electric Blue)
- **Secondary Color**: #00CC66 (Green)
- **Typography**: Inter font family
- **Spacing**: 8px base unit system
- **Grid**: CSS Grid and Flexbox hybrid approach

### 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: Vanilla JS for optimal performance
- **GSAP**: Premium animations via CDN
- **Vercel**: Deployment platform

### 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

### 🚀 Deployment

#### Option 1: Vercel (Recommended)

1. Fork this repository
2. Sign up at [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Deploy with one click

#### Option 2: Manual Upload (Drag & Drop)

1. Download or locate this `apex-athletic-website` folder
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click "Add New..." → "Project"
4. Choose "Continue without Git"
5. Drag and drop the entire `apex-athletic-website` folder
6. Click "Deploy"
7. Your site will be live instantly with a preview URL!

### 📸 Image Assets

The current version uses CSS gradients as placeholders. Replace with actual images:

- Hero video: `assets/videos/hero-bg.mp4`
- Product images: `assets/images/product-*.jpg`
- Athlete portraits: `assets/images/athlete-*.jpg`
- Other images: See `assets/images/placeholder.html`

### ⚡ Performance Tips

1. **Optimize Images**: Use WebP format with fallbacks
2. **Enable Compression**: Gzip/Brotli on server
3. **Use CDN**: Serve assets from edge locations
4. **Cache Headers**: Configured in `vercel.json`

### 🔧 Customization

1. **Colors**: Edit CSS variables in `css/styles.css`
2. **Content**: Update text in `index.html`
3. **Animations**: Modify GSAP settings in `js/main.js`
4. **Layout**: Adjust grid/flexbox in CSS files

### 📄 License

MIT License - feel free to use for any purpose

### 👥 Credits

Designed and developed for APEX Athletic - Engineered for Champions

---

**Note**: This is a demonstration website. In production, replace placeholder images with actual high-quality assets and connect the contact form to a backend service.