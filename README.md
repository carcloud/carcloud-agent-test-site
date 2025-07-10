# CarCloud - Premium Car Rental Website

A modern, responsive single-page website for a premium car rental service. Built with HTML5, CSS3, and JavaScript, featuring smooth animations, mobile-first design, and automatic deployment to GitHub Pages.

## 🚗 Features

- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Elements**: Animated counters, smooth scrolling, and hover effects
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Performance Optimized**: Lazy loading, smooth scrolling, and intersection observer APIs
- **SEO Friendly**: Proper semantic HTML structure and meta tags

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with Flexbox, Grid, and CSS animations
- **JavaScript**: Vanilla JS for interactions and animations
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Inter font family for modern typography
- **GitHub Actions**: Automated deployment to GitHub Pages

## 📁 Project Structure

```
carcloud-agent-test-site/
├── index.html              # Main HTML file
├── style.css               # All CSS styles and responsive design
├── script.js               # JavaScript functionality
├── README.md               # Project documentation
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions deployment workflow
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Git (for version control)
- GitHub account (for deployment)

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/carcloud-agent-test-site.git
   cd carcloud-agent-test-site
   ```

2. **Open in browser**:
   - Simply open `index.html` in your preferred web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **View the website**:
   - Open `http://localhost:8000` in your browser

## 🌐 Deployment to GitHub Pages

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Source" as "GitHub Actions"
   - The workflow will automatically deploy your site

3. **Access your site**:
   - Your site will be available at: `https://yourusername.github.io/carcloud-agent-test-site/`

### Manual Deployment

If you prefer manual deployment:

1. Go to repository Settings → Pages
2. Select source as "Deploy from a branch"
3. Choose "main" branch and "/ (root)" folder
4. Click Save

## 🎨 Customization

### Colors and Branding

The main brand colors are defined in CSS custom properties. You can easily change them:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #667eea;
  --accent-color: #764ba2;
}
```

### Content

- **Company Information**: Edit the HTML content in `index.html`
- **Contact Details**: Update the contact section with your real information
- **Fleet Details**: Modify the car fleet section with your vehicles
- **Images**: Replace placeholder car icons with actual images

### Styling

- **Fonts**: Change the Google Fonts import in `index.html`
- **Layout**: Modify the CSS Grid and Flexbox layouts in `style.css`
- **Animations**: Adjust timing and effects in `script.js`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Development

### Adding New Sections

1. Add HTML structure in `index.html`
2. Create corresponding CSS styles in `style.css`
3. Add JavaScript functionality in `script.js` if needed
4. Update navigation links

### Performance Optimization

- Images are lazy-loaded using Intersection Observer
- CSS and JavaScript are minified in production
- Fonts are preloaded for better performance

## 📈 SEO Features

- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Structured data for search engines
- Fast loading times
- Mobile-friendly design

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎯 Future Enhancements

- [ ] Add real car images
- [ ] Implement booking system
- [ ] Add pricing calculator
- [ ] Include customer testimonials
- [ ] Add blog section
- [ ] Implement search functionality
- [ ] Add multi-language support
- [ ] Include map integration

## 📞 Support

If you have any questions or need help with deployment, please open an issue in the repository.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- GitHub Pages for free hosting
- GitHub Actions for CI/CD

---

**Made with ❤️ for CarCloud - Your Premium Car Rental Experience** 