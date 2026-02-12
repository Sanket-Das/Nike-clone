# Nike Landing Page

A modern, responsive Nike landing page built with React and Tailwind CSS, showcasing Nike products with a clean and professional design.

## Tech Stack

- React 18.2.0
- Vite 4.4.5
- Tailwind CSS 3.3.3
- PostCSS & Autoprefixer

## Features

- Responsive navigation with mobile menu support
- Dynamic hero section with interactive shoe selection
- Popular products showcase with product cards
- Super quality section highlighting product features
- Services section (free shipping, secure payment, customer support)
- Special offers section
- Customer reviews with ratings
- Newsletter subscription
- Comprehensive footer with social media links
- Fully responsive design for all screen sizes
- Custom Tailwind configuration with brand colors and typography

## Project Structure

```
src/
├── assets/
│   ├── icons/          # SVG icons (social media, UI elements)
│   └── images/         # Product images and backgrounds
├── components/
│   ├── Button.jsx
│   ├── Nav.jsx
│   ├── PopularProductCard.jsx
│   ├── ReviewCard.jsx
│   ├── ServiceCard.jsx
│   └── ShoeCard.jsx
├── sections/
│   ├── Hero.jsx
│   ├── PopularProducts.jsx
│   ├── SuperQuality.jsx
│   ├── Services.jsx
│   ├── SpecialOffer.jsx
│   ├── CustomerReviews.jsx
│   ├── Subscribe.jsx
│   └── Footer.jsx
├── constants/
│   └── index.js        # App data (products, services, reviews, etc.)
├── App.jsx
├── main.jsx
└── index.css
```

## Getting Started

Prerequisites:
- Node.js (v14 or higher)
- npm or yarn

Installation:

```bash
# Clone the repository
git clone https://github.com/Sanket-Das/Nike-clone.git
cd nike-2-0

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run linter
npm run lint
```

The development server will start at [http://localhost:5173](http://localhost:5173)

## Custom Tailwind Configuration

The project uses custom Tailwind configuration including:

- Custom font families: Palanquin and Montserrat
- Brand colors: coral-red, slate-gray, pale-blue, primary
- Custom font sizes and line heights
- Custom box shadows
- Background images for hero and card sections
- Custom breakpoint for wide screens (1440px)

## Components

- **Button**: Reusable button component with icon support
- **Nav**: Navigation bar with mobile responsive menu
- **ShoeCard**: Interactive shoe thumbnail selector
- **PopularProductCard**: Product display card with image and pricing
- **ServiceCard**: Service feature card with icon and description
- **ReviewCard**: Customer review card with rating display

## Sections

- **Hero**: Main landing section with product showcase
- **PopularProducts**: Grid of featured Nike products
- **SuperQuality**: Product quality highlights
- **Services**: Company services (shipping, payment, support)
- **SpecialOffer**: Promotional offers section
- **CustomerReviews**: Customer testimonials
- **Subscribe**: Newsletter signup
- **Footer**: Site footer with links and social media

## Development

The project uses ESLint for code quality with React-specific rules. Prop-types validation is disabled in the ESLint configuration.

Custom CSS utilities are defined in `index.css` for consistent padding and spacing across the application.

## License

This project is open source and available for educational purposes.
