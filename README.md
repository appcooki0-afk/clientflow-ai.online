# ClientFlow Website

## Files to Upload to GitHub

1. `index.html` - Main website
2. `admin.html` - Dashboard (view at /admin.html)
3. `robots.txt` - SEO
4. `sitemap.xml` - SEO

## How the Form Works

The website uses **Formspree** to collect leads. When someone submits the form:
- You get an email notification
- Leads are stored in your Formspree dashboard

### To Make the Form Work:

1. Go to [formspree.io](https://formspree.io)
2. Create a free account
3. Create a new form
4. Copy your form ID (something like `f/xxxxxx`)
5. Open `index.html` and find this line:
   ```
   action="https://formspree.io/f/xpwzgdpj"
   ```
6. Replace `xpwzgdpj` with your form ID

### To View Leads:

- Log in to formspree.io
- Go to your form dashboard
- View all submissions
- Export to CSV if needed

## Mobile Responsive

The website is fully responsive and looks great on:
- Desktop
- Tablet
- Mobile phone

Floating badges are hidden on mobile to provide a clean experience.

## Customization

To change text/content, edit `index.html` directly.

---
ClientFlow - Get More Customers
