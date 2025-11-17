# Mahaguru AI - Landing Page

A premium dark theme landing page for Mahaguru AI with Eleven Labs-inspired aesthetics.

## Features

- Pure black background (#000000) with white text (#ffffff)
- Purple highlights (#a855f7) for premium AI feel
- Fully responsive design
- Smooth animations and purple glow effects
- Early access forms integrated
- Production-ready code

## Quick Setup

### 1. Enable GitHub Pages for Simple URL

Currently, your URL is long. To get a simple URL like `https://03aar.github.io/landing-page/`:

1. Go to your repository: `https://github.com/03aar/landing-page`
2. Click **Settings** (top navigation)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select your branch: `claude/premium-dark-theme-01NKYigJoEQyLJaXJhn18B72`
5. Click **Save**
6. Wait 1-2 minutes, then visit: `https://03aar.github.io/landing-page/`

### 2. Set Up Form Submissions (Formspree - Free)

The forms are ready but need configuration to receive submissions:

1. **Create Formspree Account**
   - Go to [https://formspree.io](https://formspree.io)
   - Sign up for free (allows 50 submissions/month)

2. **Create Forms**
   - Create Form 1: "Early Access Applications"
   - Create Form 2: "Partnership Inquiries"
   - Copy each form's ID (looks like: `xpzvxyzw`)

3. **Update index.html**
   - Find line 749: `action="https://formspree.io/f/YOUR_FORM_ID"`
   - Replace `YOUR_FORM_ID` with your Early Access form ID
   - Find line 799: `action="https://formspree.io/f/YOUR_FORM_ID"`
   - Replace `YOUR_FORM_ID` with your Partnership form ID

4. **Test**
   - Submit a test form
   - Check your email for submissions

### 3. Optional: Custom Domain (e.g., mahaGuruai.com)

For a custom domain like `mahaguruai.com`:

1. **Buy a Domain**
   - Purchase from Namecheap, GoDaddy, or Google Domains
   - Recommended: `mahaguruai.com` or `mahaguru.ai`

2. **Configure DNS**
   - Add these DNS records at your domain registrar:
   ```
   Type: CNAME
   Name: www
   Value: 03aar.github.io

   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```

3. **Configure GitHub Pages**
   - Go to Settings > Pages
   - Under "Custom domain", enter your domain
   - Check "Enforce HTTPS"

## Current URLs

**Long URL (works now):**
```
https://htmlpreview.github.io/?https://github.com/03aar/landing-page/blob/claude/premium-dark-theme-01NKYigJoEQyLJaXJhn18B72/index.html
```

**After GitHub Pages Setup:**
```
https://03aar.github.io/landing-page/
```

**After Custom Domain:**
```
https://www.mahaguruai.com
```

## File Structure

```
landing-page/
├── index.html          # Complete landing page (single file)
└── README.md          # This file
```

## Sections Included

1. ✅ Early Access Banner (floating top-right)
2. ✅ Hero Section with tagline
3. ✅ Value Proposition
4. ✅ Core Features (6 cards)
5. ✅ The Experience (5 steps)
6. ✅ Who It's For (4 audiences)
7. ✅ Early Access Program Form
8. ✅ Founder Vision
9. ✅ Partner Contact Form
10. ✅ Footer

## Technologies Used

- Pure HTML5 + CSS3 + JavaScript
- No dependencies or frameworks
- Single-file deployment
- Mobile-responsive
- Production-ready

## Support

For questions or issues, contact the development team.

---

Built with conviction and clarity.
