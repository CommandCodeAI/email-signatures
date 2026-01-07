# Email Signature Generator

A modern, feature-rich email signature generator built with HTML, CSS, and JavaScript. Create beautiful email signatures with custom colors, social links, credentials, and more.

## Features

- **Real-time Preview** - See your signature as you edit
- **Rich Text Editing** - Add bold text, links, and formatting
- **Social Links** - Include LinkedIn, Twitter, GitHub, and more
- **Credentials & Awards** - Showcase your achievements
- **Custom Colors** - Customize every aspect of the signature
- **One-Click Copy** - Copy signature to clipboard as HTML
- **Gmail Compatible** - Paste directly into Gmail settings

## Local Development

```bash
# Install dependencies
npm install

# Run dev server
npm run dev

# Open http://localhost:8787 in your browser
```

## Deployment

Deploy to Cloudflare Workers:

```bash
# Login to Cloudflare (first time only)
npx wrangler login

# Deploy
npm run deploy
```

Your app will be live at `https://email-signatures.<your-workers-subdomain>.workers.dev`

## How to Use

1. Fill in your name and role information
2. Add social links and credentials (optional)
3. Customize colors to match your brand
4. Click "Copy Signature" to copy the formatted signature
5. Paste into Gmail signature settings

### Adding to Gmail

1. Copy your signature
2. Open [Gmail Settings](https://mail.google.com/mail/u/0/#settings/general)
3. Scroll to "Signature" section
4. Click "+ Create new" and name your signature
5. Paste the signature (Cmd+V or Ctrl+V)
6. Save changes

## Built With

- Cloudflare Workers
- Wrangler CLI
- Vanilla JavaScript
- CSS Grid & Flexbox

## License

MIT
