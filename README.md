# Portail Landing Site

3-page landing site for portailapp.ca

## Files
- index.html — Home page
- about.html — About page  
- download.html — Download page
- styles.css — All styles

## Assets needed (add to root folder)
- logo.png — Your Portail logo (from assets/logo.png in the app)
- screen1.png — Home screen screenshot (IMG_1831)
- screen2.png — Booking screen screenshot (IMG_1832)
- screen3.png — My Trips screenshot (IMG_1833)
- screen4.png — Create Account screenshot

## Deploy to Vercel
1. Create a GitHub repo and push this folder
2. Go to vercel.com → New Project → Import repo
3. Deploy (no build config needed — static HTML)
4. Add custom domain: portailapp.ca

## Point domain to Vercel (Namecheap)
In Namecheap DNS settings, add:
- Type: CNAME | Host: www | Value: cname.vercel-dns.com
- Type: A | Host: @ | Value: 76.76.21.21
