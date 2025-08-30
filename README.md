# New Wave Apps - Official Website

A modern, responsive website for New Wave Apps LLC, showcasing our mobile app portfolio and select development services.

## About New Wave Apps

New Wave Apps LLC creates and publishes innovative mobile applications. Our primary focus is building our own app portfolio, with occasional select development services. We specialize in:

- App Publishing & Portfolio Management - Our own innovative mobile applications
- App Store Optimization - Maximizing visibility and success for our apps
- Select Development Services - Carefully chosen client projects that align with our vision
- Long-term App Maintenance - Continuous improvement and evolution of our apps

## Website Features

- **Modern Design**: Inspired by our colorful wave logo with a vibrant color scheme
- **Responsive**: Fully optimized for desktop, tablet, and mobile devices
- **Fast Loading**: Lightweight static site optimized for GitHub Pages
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Privacy Compliant**: Comprehensive privacy policy page
- **Contact Integration**: Direct email contact functionality

## Technology Stack

- **Jekyll**: Static site generator with templating and build tools
- **HTML5**: Semantic markup for better accessibility and SEO
- **SCSS**: Enhanced CSS with variables, mixins, and modular organization
- **Liquid**: Jekyll's templating language for dynamic content
- **Vanilla JavaScript**: Lightweight interactions without dependencies
- **Google Fonts**: Inter font family for clean typography
- **GitHub Pages**: Static hosting with Jekyll support

## Color Scheme

Based on our logo design:
- Primary Orange: `#FF6B35`
- Primary Teal: `#20B2AA` 
- Primary Blue: `#2F3A8F`
- Secondary Purple: `#4C3D91`
- Light Blue: `#7DD3FC`

## Getting Started

### Prerequisites
- Ruby 2.7 or higher
- Bundler gem

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/new-wave-apps/new-wave-apps-site.git
   cd new-wave-apps-site
   ```

2. **Install dependencies**:
   ```bash
   bundle install
   ```

3. **Run locally**:
   ```bash
   bundle exec jekyll serve
   ```
   
   Your site will be available at `http://localhost:4000`
   
   For live reloading during development:
   ```bash
   bundle exec jekyll serve --livereload
   ```

4. **Build for production**:
   ```bash
   bundle exec jekyll build
   ```
   
   This creates the `_site` folder with the generated static files.

### Deploy to GitHub Pages

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial Jekyll setup"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch
   - GitHub Pages will automatically build and deploy your Jekyll site

## File Structure

```
├── _config.yml         # Jekyll configuration
├── _layouts/           # Page templates
│   ├── default.html    # Base layout with header/footer
│   └── page.html       # Standard page layout
├── _includes/          # Reusable components
│   ├── header.html     # Site header and navigation
│   └── footer.html     # Site footer
├── _pages/             # Static pages
│   └── privacy.md      # Privacy policy page
├── assets/             # Static assets
│   └── css/
│       └── styles.scss # Main stylesheet (SCSS)
├── index.html          # Homepage with Jekyll front matter
├── Gemfile             # Ruby dependencies
├── .gitignore          # Git ignore rules
└── README.md          # This file
```

## Pages

### Homepage (/)
- Hero section with company logo and portfolio focus
- App Portfolio section with attractive empty state design
- Development Services section for select client work
- Company approach highlighting portfolio-first mindset
- Contact section with email integration
- Mobile-responsive design with smooth animations

### Privacy Policy (/privacy/)
- Comprehensive privacy policy in Markdown format
- Platform-specific privacy practices and app store compliance
- GDPR and privacy law considerations
- Dynamic content using Jekyll Liquid templating
- Automatically updated timestamps

## Contact

**Email**: [contact@newwaveapps.dev](mailto:contact@newwaveapps.dev)

## Legal

- **Privacy Policy**: Available at `/privacy.html`
- **Terms & Conditions**: [Apple's Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)

## License

© 2024 New Wave Apps LLC. All rights reserved.
