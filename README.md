# NovaTech Landing Page

A modern, responsive landing page for a fictional tech startup built with React, Vite, and Tailwind CSS.

## Features

- Responsive design that works on all devices
- Modern UI with animations using Framer Motion
- Interactive components including:
  - Responsive navigation
  - Hero section with animated elements
  - Features/services section
  - Testimonial carousel
  - Pricing plans with toggle
  - Contact form
  - Footer with social links

## Technologies Used

- React
- Vite
- Tailwind CSS
- Framer Motion (animations)
- React Icons
- React Scroll (smooth scrolling)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd startup-landing-page
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Build for Production

```bash
npm run build
# or
yarn build
```

The build files will be in the `dist` directory.

## Project Structure

```
src/
├── assets/
│   └── images/
│       ├── logo.svg
│       └── hero-image.svg
├── components/
│   ├── layout/
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   └── sections/
│       ├── Hero.jsx
│       ├── Features.jsx
│       ├── Testimonials.jsx
│       ├── Pricing.jsx
│       └── Contact.jsx
├── App.jsx
├── index.css
└── main.jsx
```




