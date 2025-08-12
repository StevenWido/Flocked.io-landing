# 🚀 Flocked Landing Page Hosting Instructions

## Quick Summary
I've created a professional landing page for Flocked with Privacy Policy and Terms of Service pages. Here are the best hosting options for getting it online quickly.

## Files Created
- `index.html` - Main landing page
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `styles.css` - Main styling
- `legal.css` - Legal pages styling

## 🎯 Recommended: Vercel (Free & Instant)

### Why Vercel?
- **Free hosting** for static sites
- **Instant deployment** (< 2 minutes)
- **Automatic HTTPS** certificate
- **Custom domain support** included
- **Global CDN** for fast loading
- **No credit card required**

### Deploy to Vercel:

1. **Install Vercel CLI** (optional but fastest):
```bash
npm i -g vercel
```

2. **Deploy in one command**:
```bash
cd /Users/stevenwido/flocked-landing
vercel
```

3. **Follow prompts**:
   - Login/signup with GitHub
   - Confirm project settings (just press Enter)
   - Get your live URL instantly!

4. **Add your custom domain**:
   - Go to https://vercel.com/dashboard
   - Select your project
   - Go to Settings → Domains
   - Add your domain (e.g., flocked.app or www.flocked.app)
   - Update DNS records as instructed

## 🔄 Alternative Options

### Option 2: Netlify (Also Free)
1. Go to https://app.netlify.com
2. Drag and drop the `flocked-landing` folder
3. Instant deployment!
4. Add custom domain in Site Settings

### Option 3: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Enable GitHub Pages from main branch
5. Access at `https://yourusername.github.io/repo-name`

### Option 4: Cloudflare Pages (Free)
1. Go to https://pages.cloudflare.com
2. Connect GitHub account
3. Create new project
4. Deploy automatically on push

## 📝 Custom Domain Setup

Once hosted, configure your domain:

### For Vercel/Netlify:
1. Add these DNS records at your domain registrar:
   - **A Record**: Point `@` to provided IP
   - **CNAME**: Point `www` to your-site.vercel.app

### Example DNS Configuration:
```
Type    Name    Value
A       @       76.76.21.21
CNAME   www     flocked-landing.vercel.app
```

## ✅ Post-Deployment Checklist

1. **Verify all pages load**:
   - Homepage: https://your-domain.com
   - Privacy: https://your-domain.com/privacy.html
   - Terms: https://your-domain.com/terms.html

2. **Update placeholder content**:
   - Email addresses (currently: hello@flocked.app)
   - Social media links
   - Actual user/club statistics

3. **For Apple Developer Account**:
   - Your website must be live
   - Must have Privacy Policy (✓)
   - Must have Terms of Service (✓)
   - Must show company/organization info (✓)

## 🚀 Quick Start Commands

### Using Vercel (Recommended):
```bash
# Navigate to project
cd /Users/stevenwido/flocked-landing

# Deploy instantly
npx vercel

# Or if you installed Vercel CLI globally
vercel
```

### Using Surge.sh (Alternative quick option):
```bash
# Install and deploy
npm install -g surge
cd /Users/stevenwido/flocked-landing
surge
# Choose domain: flocked.surge.sh (or custom)
```

## 📱 Mobile Responsiveness
The site is fully responsive and will look great on:
- Desktop browsers
- Tablets
- Mobile devices
- Apple's review team devices

## 🔐 HTTPS/SSL
All recommended hosting options provide free SSL certificates automatically. This is required for:
- Apple Developer Account verification
- App Store submission
- User trust and SEO

## 💡 Pro Tips

1. **Start with Vercel/Netlify** - Get online in 2 minutes
2. **Add custom domain later** - You can use the provided URL initially
3. **Keep it simple** - This landing page is perfect for Apple's requirements
4. **Update regularly** - Keep content fresh as your app develops

## 📞 Need Help?

Common issues:

**Domain not working?**
- DNS changes take 24-48 hours to propagate
- Use provided Vercel/Netlify URL in meantime

**Pages not found?**
- Ensure all files are in root directory
- Check file names are lowercase
- Verify .html extensions

**SSL certificate error?**
- Wait 10-15 minutes after domain setup
- Certificate provisioning is automatic

## 🎉 You're Ready!

Once deployed, you'll have:
- ✅ Professional website for Apple Developer Account
- ✅ Privacy Policy and Terms pages
- ✅ HTTPS secure hosting
- ✅ Mobile-responsive design
- ✅ Fast global CDN delivery

The site is designed to meet all Apple's requirements for transitioning your developer account to an organization. Good luck with your iOS app development!