# Nsyte Recovery Agents Website

Professional surplus funds recovery website for Nsyte Recovery Agents - fully optimized for Vercel deployment.

## 🚀 Live Website
- **Production**: [Deploy to Vercel](https://vercel.com/new/clone?repository-url=https://github.com/hop3rs/nsyte-website-vercel)
- **Demo**: Available after deployment

## 📋 Overview

Nsyte Recovery Agents specializes in helping property owners recover unclaimed surplus funds from foreclosure sales. This website showcases our professional services with a modern, responsive design optimized for conversions.

### Key Features
- **Professional Design**: Modern, approachable interface following industry best practices
- **Lead Generation**: Optimized contact forms and call-to-action elements
- **Mobile Responsive**: Fully responsive design for all devices
- **SEO Optimized**: Comprehensive meta tags and structured data
- **Performance Optimized**: Fast loading times with optimized assets
- **Video Content**: Professional video presentations and testimonials

## 🛠 Technology Stack

- **Frontend**: React 19+ with modern JavaScript (ES2022+)
- **Styling**: Tailwind CSS 4+ with custom components
- **UI Components**: Radix UI primitives for accessibility
- **Icons**: Lucide React icon library
- **Build Tool**: Vite for fast development and optimized builds
- **Deployment**: Vercel-optimized with comprehensive configuration

## 📁 Project Structure

```
nsyte-vercel/
├── dist/                    # Built website (production ready)
│   ├── assets/             # Optimized CSS, JS, images, videos
│   ├── index.html          # Main landing page
│   ├── squeeze.html        # Lead capture page
│   ├── favicon.ico         # Site favicon
│   ├── robots.txt          # SEO crawling instructions
│   ├── sitemap.xml         # XML sitemap
│   └── _redirects          # Routing configuration
├── public/                 # Static assets
├── vercel.json            # Vercel deployment configuration
├── package.json           # Project metadata
├── .vercelignore          # Deployment ignore rules
└── README.md              # This file
```

## 🚀 Quick Deploy to Vercel

### Option 1: One-Click Deploy
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/hop3rs/nsyte-website-vercel)

### Option 2: Vercel CLI
```bash
# Install Vercel CLI
npm i -g vercel

# Clone and deploy
git clone https://github.com/hop3rs/nsyte-website-vercel.git
cd nsyte-website-vercel
vercel

# Follow the prompts:
# - Set up and deploy? Yes
# - Which scope? (Select your account)
# - Link to existing project? No
# - Project name: nsyte-recovery-agents
# - Directory: ./dist
# - Override settings? No
```

### Option 3: GitHub Integration
1. Fork this repository
2. Connect your GitHub account to Vercel
3. Import the repository in Vercel dashboard
4. Deploy automatically

## ⚙️ Deployment Configuration

The website is pre-configured for optimal Vercel deployment:

### Build Settings
- **Build Command**: `echo "Build already completed"`
- **Output Directory**: `dist`
- **Install Command**: `echo "No install needed"`

### Performance Features
- **Asset Caching**: Long-term caching (1 year) for static assets
- **Security Headers**: X-Frame-Options, X-Content-Type-Options, X-XSS-Protection
- **SPA Routing**: Proper routing for single-page application
- **SEO Optimization**: Complete meta tags, Open Graph, Twitter Cards

## 📊 Performance Metrics

- **Package Size**: 44MB (optimized for Vercel)
- **JavaScript Bundle**: 376KB (optimized)
- **CSS Bundle**: 112KB (Tailwind optimized)
- **Expected Load Time**: < 2 seconds
- **Lighthouse Score**: 90+ (estimated)

## 🎯 Business Features

### Services Highlighted
- **Surplus Funds Recovery**: Professional recovery services
- **Expert Consultation**: Free consultation offerings
- **Proven Results**: $8M+ recovered for clients
- **Legal Expertise**: Professional legal team handling

### Lead Generation
- **Contact Forms**: Optimized lead capture forms
- **Call-to-Action**: Strategic CTA placement
- **Phone Integration**: Direct calling functionality
- **Email Integration**: Professional email contact

## 🔧 Customization

### Content Updates
- Main content is in `dist/index.html`
- Lead capture page in `dist/squeeze.html`
- Update contact information in both files

### Styling Changes
- CSS is compiled in `dist/assets/index-[hash].css`
- For major changes, modify source files and rebuild

### Asset Updates
- Replace images in `dist/assets/` directory
- Update videos by replacing MP4 files
- Maintain same filenames for automatic linking

## 📞 Contact Information

- **Phone**: (504) 334-8866
- **Email**: info@nsyteagents.com
- **Website**: [nsyteagents.com](https://nsyteagents.com)

## 📄 License

This website is proprietary to Nsyte Recovery Agents. All rights reserved.

## 🤝 Support

For technical support or deployment assistance, please contact the development team.

---

**Ready to deploy?** Click the Vercel button above or follow the deployment instructions to get your website live in minutes!
