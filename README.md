# NYS Times Hotel Website

A modern, responsive website for NYS Times Hotel.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher)

### Installation

```bash
npm install
```

### Development

Run the local development server:

```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Production

This is a static site. Simply deploy to Vercel:

```bash
npx vercel
```

Or connect your GitHub repository to Vercel for automatic deployments.

## Project Structure

```
NYSTimes/
├── index.html        # Homepage
├── about.html        # About page
├── rooms.html        # Rooms page
├── facilities.html   # Facilities page
├── gallery.html      # Gallery page
├── tariff.html       # Tariff/pricing page
├── contact.html      # Contact page
├── css/              # Stylesheets
├── js/               # JavaScript files
├── package.json      # NPM configuration
└── vercel.json       # Vercel deployment config
```

## Deployment

This project is configured for [Vercel](https://vercel.com). Push to your main branch and Vercel will automatically deploy.