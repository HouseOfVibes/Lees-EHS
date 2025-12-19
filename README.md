# Lee's Essential Home Solutions

Website for Lee's Essential Home Solutions - a home maintenance service providing monthly HVAC filter delivery, water softener salt refills, and trash bin cleaning in Meridiana, Texas.

## Tech Stack

- **Framework:** [Astro](https://astro.build/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Deployment:** Vercel (recommended)

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/lees-essential-home-solutions.git

# Navigate to project directory
cd lees-essential-home-solutions

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:4321`

## Project Structure

```
/
├── public/
│   └── images/          # Static images
├── src/
│   ├── components/      # Reusable components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Route pages
│   └── styles/          # Global styles
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind configuration
└── package.json
```

## Available Scripts

| Command           | Action                                       |
|-------------------|----------------------------------------------|
| `npm run dev`     | Start development server at `localhost:4321` |
| `npm run build`   | Build production site to `./dist/`           |
| `npm run preview` | Preview build locally before deploying       |

## Deployment

This site is configured for deployment on Vercel:

1. Push to GitHub
2. Connect repository to Vercel
3. Deploy automatically on push to `main`

## Customization

### Update Contact Information

Edit the contact details in `src/pages/index.astro`:
- Phone number
- Email address
- Physical address

### Update Pricing

Pricing is displayed in the pricing section of `src/pages/index.astro`. Update the prices and plan details as needed.

### Add Images

Place images in the `public/images/` directory and reference them with `/images/filename.jpg`.

## License

Private - All rights reserved.

---

Built with Astro by MW Design Studio
