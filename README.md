# Omni - AI Therapy Companion Website

Professional landing page for Omni, an AI-powered mental health companion app that provides 24/7 support through CBT-based therapy, mood tracking, and wellness tools.

## 🌐 Live Website
Visit: [https://jaym9000.github.io/OmniSite](https://jaym9000.github.io/OmniSite)

## 🚀 Features

- **Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- **Modern UI/UX** - Clean, calming interface with smooth animations
- **SEO Optimized** - Meta tags and structured content for search engines
- **Fast Performance** - Lightweight, optimized assets
- **Accessibility** - WCAG compliant for inclusive access

## 📁 Project Structure

```
OmniSite/
├── index.html          # Main landing page
├── styles.css          # Styling and animations
├── script.js           # Interactive features
├── Images/             # App icons and illustrations
├── favicon-*.png       # Browser icons
└── apple-touch-icon.png # iOS home screen icon
```

## 🛠️ Technologies Used

- HTML5 (Semantic markup)
- CSS3 (Modern layouts, animations)
- JavaScript (Vanilla JS for interactions)
- Google Fonts (Inter, Plus Jakarta Sans)

## 📱 App Features Highlighted

- Unlimited AI therapy sessions
- Voice-to-voice support (coming soon)
- Mood tracking & insights
- Guided journaling
- Anxiety management tools
- Complete privacy & security

## 💰 Pricing Plans

- **Monthly**: $9.99/month
- **Annual**: $69.99/year (Save $50)
- Free trial included with all plans

## 🔧 Local Development

1. Clone the repository:
```bash
git clone https://github.com/jaym9000/OmniSite.git
cd OmniSite
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Visit `http://localhost:8000`

## 📝 Custom Domain Setup

### Option 1: GitHub Pages Custom Domain

1. Add a `CNAME` file to the repository root with your domain:
```
omniapp.ai
```

2. Configure DNS at your domain provider:

**For apex domain (omniapp.ai):**
- A record → 185.199.108.153
- A record → 185.199.109.153
- A record → 185.199.110.153
- A record → 185.199.111.153

**For subdomain (www.omniapp.ai):**
- CNAME record → jaym9000.github.io

3. In GitHub repository settings:
   - Go to Settings → Pages
   - Add custom domain
   - Enable "Enforce HTTPS"

### Option 2: Using Cloudflare (Recommended)

1. Add your domain to Cloudflare (free plan)
2. Update nameservers at your registrar
3. Add CNAME record pointing to `jaym9000.github.io`
4. Enable "Full" SSL/TLS encryption mode
5. Benefits: Free SSL, CDN, DDoS protection

### Recommended Domain Registrars

- **Namecheap**: Best value, ~$10-15/year
- **Cloudflare**: At-cost pricing, great features
- **Google Domains** (Squarespace): Simple interface
- **GoDaddy**: Often has promotions

### Suggested Domain Names

- `omniapp.ai` - Premium AI domain (~$50-70/year)
- `omni-therapy.com` - Clear purpose (~$12/year)
- `getomni.app` - Modern, action-oriented (~$20/year)
- `omnicompanion.com` - Descriptive (~$12/year)

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6B8E7F;  /* Sage green */
    --primary-dark: #5A7A6D;
    --secondary-color: #F5E6D3; /* Warm beige */
}
```

### Content
Update text directly in `index.html` for:
- Hero section messaging
- Feature descriptions
- Pricing details
- FAQ content

### Images
Replace files in the `Images/` folder:
- `OmniAppIcon1024.png` - Main app icon
- Add new illustrations as needed

## 📊 Analytics Setup

To add Google Analytics:

1. Get your GA4 Measurement ID
2. Add before `</head>` in index.html:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is proprietary and confidential. All rights reserved.

## 🔗 Important Links

- [Privacy Policy](https://jaym9000.github.io/OmniPrivacyPolicy/)
- [Terms of Use](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
- [App Store](#) - Coming Soon

## 📞 Support

For support or inquiries, contact: support@omniapp.ai

---

Built with 💚 for mental wellness