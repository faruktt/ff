# Personal Static Website

A beautiful, responsive personal website built with HTML and Tailwind CSS featuring a warm, nostalgic scrapbook aesthetic.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Animations**: Smooth fade-ins, hover effects, and transitions
- **Polaroid-Style Gallery**: Unique photo presentation with rotation effects
- **Timeline Section**: Beautiful birthday milestones timeline
- **Contact Form**: Functional contact form with validation
- **Smooth Navigation**: Sticky header with smooth scroll to sections

## Sections Included

1. **Header/Navigation**: Sticky navigation bar with smooth scroll links
2. **Hero Banner**: Eye-catching welcome section with call-to-action
3. **About Section**: Personal description with profile photo
4. **Events Section**: Showcase special events with images
5. **Memories Gallery**: Grid of cherished memories with polaroid styling
6. **Birthday Timeline**: Chronological milestone celebrations
7. **Inspirational Quote**: Motivational quote section
8. **Contact Form**: Get in touch form
9. **Footer**: Links and social media connections

## How to Use

1. **Open the Website**:
   - Simply open `index.html` in any modern web browser
   - No server or build process required!

2. **Customize Your Content**:
   - Edit the text content directly in `index.html`
   - Update personal information, descriptions, and dates

3. **Add Your Photos**:
   - Place your photos in the `assets/images/` folder
   - Recommended image names:
     - `profile.jpg` - Your profile photo
     - `event1.jpg`, `event2.jpg`, `event3.jpg` - Event photos
     - `memory1.jpg` through `memory8.jpg` - Memory gallery photos
   - The website has fallback placeholders if images are missing

## Customization Tips

### Change Colors
The website uses CSS variables for easy color customization. Edit these in the `<style>` section:

```css
:root {
    --sepia: #f4ede4;
    --warm-brown: #8b6f47;
    --deep-brown: #5d4e37;
    --soft-cream: #faf6f0;
    --accent-rust: #b86f50;
}
```

### Update Typography
Current fonts:
- Headers: Playfair Display
- Body: Crimson Text

To change fonts, update the Google Fonts import link and font-family properties.

### Modify Sections
- Each section has an `id` attribute for navigation
- Add or remove sections as needed
- Update navigation links accordingly

### Social Media Links
Update the social media icons in the footer with your actual profile URLs:
```html
<a href="YOUR_FACEBOOK_URL">...</a>
<a href="YOUR_TWITTER_URL">...</a>
<a href="YOUR_INSTAGRAM_URL">...</a>
```

## Image Specifications

For best results:
- **Profile Photo**: 400x400px (square)
- **Event Photos**: 400x300px (4:3 ratio)
- **Memory Photos**: 300x300px (square)
- Format: JPG or PNG
- Optimized for web (< 500KB per image)

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Google Fonts**: Playfair Display & Crimson Text
- **Vanilla JavaScript**: Simple interactions and animations

## File Structure

```
personal-website/
├── index.html          # Main HTML file
├── README.md          # This file
└── assets/
    └── images/        # Your photos go here
```

## Tips for Best Experience

1. **Image Quality**: Use high-quality images for a professional look
2. **Content Length**: Keep descriptions concise and engaging
3. **Regular Updates**: Update events and memories as they happen
4. **Testing**: Test on different devices to ensure responsiveness
5. **Personalization**: Make it uniquely yours by customizing colors and content

## Deployment Options

You can host this website for free on:
- **GitHub Pages**: Push to a GitHub repo and enable Pages
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repo
- **Cloudflare Pages**: Direct upload or Git integration

## Support

For issues or questions:
- Check browser console for any errors
- Ensure all image paths are correct
- Verify internet connection for CDN resources (Tailwind CSS, Google Fonts)

## License

Feel free to use and modify this template for your personal use!

---

**Made with ❤️ and memories**

Enjoy your new personal website! 🎉
# ff
