# MAC Club Website

A professional, responsive website for the Media Arts & Coding (MAC) Club at Monta Vista High School. This website showcases the club's unique mission of bridging art and technology through creative coding projects.

## 🌟 Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Accessibility**: Semantic HTML and keyboard navigation support
- **SEO Optimized**: Meta tags, sitemap, and structured data
- **Netlify Ready**: Pre-configured for easy deployment

## 🚀 Quick Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Sign up or log in to your account
3. Drag the entire `MAC Club` folder to the deploy area
4. Your site will be live in seconds!

### Option 2: Git Integration
1. Push this code to a GitHub repository
2. Connect your GitHub account to Netlify
3. Select the repository and deploy
4. Netlify will automatically deploy updates when you push changes

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Navigate to the project directory
cd "MAC Club"

# Deploy
netlify deploy --prod --dir .
```

## 📁 Project Structure

```
MAC Club/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── _redirects          # Netlify redirects configuration
├── netlify.toml        # Netlify build configuration
├── robots.txt          # Search engine directives
├── sitemap.xml         # Site structure for search engines
└── README.md           # This file
```

## 🎨 Customization

### Colors
The website uses a modern color palette that can be easily customized in `styles.css`:
- Primary: `#6366f1` (Indigo)
- Secondary: `#fbbf24` (Amber)
- Background: `#f8fafc` (Gray-50)
- Text: `#1f2937` (Gray-900)

### Content
Update the content in `index.html` to reflect your club's specific information:
- Club name and description
- Meeting times and locations
- Contact information
- Project examples

### Images
To add images:
1. Place image files in the project directory
2. Update the HTML to reference the images
3. Consider using WebP format for better performance

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive features
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter)

### Browser Support
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

### Performance Features
- Optimized CSS and JavaScript
- Lazy loading for images
- Compressed assets
- Efficient animations

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images for different screen sizes
- Readable typography on all devices

## 🔍 SEO Features

- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- XML sitemap
- Robots.txt file
- Fast loading times

## 🛠️ Development

### Local Development
1. Open `index.html` in a web browser
2. Use a local server for full functionality:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### Making Changes
1. Edit the HTML, CSS, or JavaScript files
2. Test locally in your browser
3. Deploy to Netlify (if using Git integration, changes deploy automatically)

## 📧 Form Handling

The contact form is currently set up for demonstration. To make it functional:

1. **Netlify Forms** (Recommended):
   - Add `netlify` attribute to the form
   - Forms will be automatically handled by Netlify

2. **Custom Backend**:
   - Update the form action in `index.html`
   - Modify the JavaScript in `script.js`

3. **Third-party Services**:
   - Formspree, Netlify Forms, or similar services

## 🎯 Club Information

### Mission
MAC Club bridges the worlds of coding and creativity, fostering innovation through interdisciplinary art and technology projects.

### Activities
- Case study presentations
- Project workshops with mentor guidance
- Brainstorming sessions
- Friendly competitions with prizes

### Project Areas
- Interactive Media
- Generative Art
- Multimedia Arts

## 📞 Support

For questions about this website or the MAC Club:
- Update contact information in the footer
- Add social media links
- Include meeting times and locations

## 📄 License

This project is created for educational purposes. Feel free to modify and use for your own club or organization.

---

**Ready to deploy?** Just drag the `MAC Club` folder to Netlify and you're live! 🚀
