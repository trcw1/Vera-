# Vera Modeling Agency

Vera Modeling Agency - Professional landing page with comprehensive features for model registration, booking, and portfolio management.

## Features

- 12 action buttons for various services
- 8 different form types (registration, booking, contact, search, etc.)
- Responsive design with tablet and mobile breakpoints
- Accessible with ARIA labels and keyboard navigation
- Modern gradient-based design system
- Career opportunities, blog, events, gallery, testimonials, and FAQ sections

## Quick Start

### Installation

```bash
npm install
```

### Run the Server

```bash
npm start
```

The website will be available at: `http://localhost:3000`

## Deployment

### For Production

The server runs on port 3000 by default. To connect your domain:

1. Set up your DNS to point to your server IP
2. Configure a reverse proxy (nginx/Apache) or use port forwarding
3. Run the server with: `npm start`

### Environment Variables

You can customize the port by setting the `PORT` environment variable:

```bash
PORT=3000 npm start
```

## Files

- `index.html` - Main landing page
- `styles.css` - Stylesheet with gradient design system
- `server.js` - Express server for serving static files
- `package.json` - Node.js dependencies and scripts

## Technologies

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Node.js
- Express.js

## License

MIT

# Vera Modeling Agency Website

A modern, responsive website for Vera Modeling Agency featuring model portfolios, galleries, and announcements.

## Features

- **Model Profiles**: Browse through our talented models with detailed profiles
- **Photo Galleries**: Each model has a dedicated gallery showcasing their work
- **Announcements**: Stay updated with casting calls, news, and events
- **Contact Form**: Easy way to get in touch with the agency
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

## Pages

1. **Home** (`index.html`) - Welcome page with agency overview
2. **Our Models** (`models.html`) - Grid view of all models
3. **Model Detail** (`model-detail.html`) - Individual model profiles with galleries
4. **Announcements** (`announcements.html`) - Latest news and casting calls
5. **Contact** (`contact.html`) - Contact information and message form

## Technology

- Pure HTML5, CSS3, and JavaScript
- No external dependencies or frameworks
- Fully responsive design
- Modern gradient color scheme

## Getting Started

Simply open `index.html` in a web browser to view the website locally. For deployment, upload all files to your web server.

### Local Development

You can start a simple HTTP server to test the site:

```bash
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.

## Structure

```
Vera-/
├── index.html              # Homepage
├── models.html             # Models listing
├── model-detail.html       # Model profile template
├── announcements.html      # Announcements page
├── contact.html            # Contact page
├── styles.css              # All styling
├── script.js               # JavaScript functionality
└── README.md               # This file
```

## Customization

### Adding Models

Edit the `modelsData` array in `script.js` to add or modify model profiles.

### Adding Announcements

Edit the `announcementsData` array in `script.js` to add or modify announcements.

### Styling

All styles are contained in `styles.css`. Modify colors, fonts, and layouts as needed.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

© 2026 Vera Modeling Agency. All rights reserved.
