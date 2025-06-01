# PayPal.Verified - Account Verification Services

A professional website for PayPal account verification services with custom animations and Discord integration.

## Features

- Responsive design with PayPal branding
- Interactive pricing cards with click animations
- Discord integration for customer support
- Terms & Services page
- Optimized for Vercel deployment

## Verification Levels

- **3/5 Verified**: Email + Phone + Documents (€2)
- **4/5 Verified**: Email + Phone + Documents + Card (€3)
- **5/5 Verified**: Full verification including bank (€4)

## Deployment to Vercel

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Vercel will automatically detect the `vercel.json` configuration
4. Deploy with one click

The site is configured as a single-page application with proper routing for the Terms page.

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The build output will be in `dist/public/` which Vercel will automatically deploy.