# EVP-Scan.nl

Employee Value Proposition Assessment Tool voor Nederlandse Tech Bedrijven

## 🚀 Features
- Interactive EVP Assessment via Typeform
- Real-time Analytics met Google Analytics 4
- Mobile-first Responsive Design
- Nederlandse Tech Recruitment Focus
- GDPR Compliant Privacy Integration

## 🎨 Design
- **Primaire kleuren**: Corporate Blue (#3498db, #2980b9)
- **Steunkleuren**: Warm Orange (#e67e22) accents  
- **Achtergrond**: Warm grijs-blauw gradient (#1e2536 → #2a3441)
- **Typography**: System fonts voor performance

## 🔧 Tech Stack
- Pure HTML/CSS/JavaScript (No frameworks)
- Typeform Embed SDK voor EVP Assessment
- Google Analytics 4 + Tag Manager
- Netlify voor hosting & CI/CD
- GitHub Actions voor automated deployment

## 📊 Analytics & Tracking
- Page views, scroll depth, time on site
- Typeform completion rates & drop-off points
- CTA click tracking & conversion funnels
- Custom dimensions voor EVP-specific metrics

## 🚀 Deployment
Automatische deployment naar Netlify bij push naar main branch.

### Setup Instructions:
1. Fork deze repository
2. Connect naar Netlify account
3. Stel environment variables in:
   - `NETLIFY_AUTH_TOKEN`
   - `NETLIFY_SITE_ID` 
   - `GA_MEASUREMENT_ID` (Google Analytics)
4. Update Google Analytics ID in index.html
5. Push naar main branch voor deployment

## 🔐 Environment Variables
```bash
# Netlify
NETLIFY_AUTH_TOKEN=your_netlify_token
NETLIFY_SITE_ID=your_site_id

# Google Analytics  
GA_MEASUREMENT_ID=G-XXXXXXXXXX
GTM_CONTAINER_ID=GTM-XXXXXXX

# Typeform
TYPEFORM_FORM_ID=YUJCxF86
```

## 📱 Performance
- Lighthouse Score: 95+ Performance
- Mobile-first responsive design
- Lazy loading voor images
- Optimized CSS zonder external dependencies
- CDN delivery via Netlify

## 📈 SEO Optimizations
- Semantic HTML structure
- Meta tags voor social media
- Structured data markup
- Fast loading times
- Mobile-friendly design

## 🔒 Security
- Content Security Policy headers
- XSS Protection
- HTTPS enforced
- No inline scripts (where possible)
- Typeform iframe sandboxing

## 📞 Contact
- **Website**: [recruitin.nl](https://recruitin.nl)
- **Email**: info@recruitin.nl
- **Privacy**: [Privacy Policy](https://recruitin.nl/privacyverklaring-recruitin/)