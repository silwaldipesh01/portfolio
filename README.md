# My Portfolio Website 🚀

A modern, responsive portfolio website showcasing my projects, skills, and experiences. Built with vanilla HTML, CSS, and JavaScript.

## Features ✨

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dynamic Project Showcase**: Automatically fetches your public GitHub projects using the GitHub API
- **Smooth Animations**: Beautiful scroll animations and hover effects throughout
- **Skills Section**: Highlight your technical expertise
- **Contact Form**: Get in touch with visitors (with client-side validation)
- **Modern UI**: Gradient backgrounds, glassmorphism effects, and smooth transitions
- **Dark Theme**: Eye-friendly dark mode design

## Sections 📄

1. **Navigation Bar** - Fixed navbar with smooth scrolling links
2. **Hero Section** - Eye-catching introduction with animated shapes
3. **Projects Section** - Displays all your public GitHub repositories
4. **Skills Section** - Showcase your technical skills with icons
5. **Contact Section** - Contact form and social links
6. **Footer** - Copyright information

## Technologies Used 🛠️

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with animations and gradients
- **Vanilla JavaScript** - No frameworks needed
- **GitHub API** - Fetches your public repositories dynamically

## Getting Started 🎯

### Prerequisites

- A GitHub account (for fetching your repositories)
- A text editor or IDE
- A web browser

### Installation

1. Clone the repository:
```bash
git clone https://github.com/silwaldipesh01/portfolio.git
cd portfolio
```

2. Open `index.html` in your web browser or use a local server:

Using Python:
```bash
# Python 3
python -m http.server 8000
```

Using Node.js:
```bash
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## Customization 🎨

### Update Your Information

Open `index.html` and modify:
- Hero section text
- Skills section
- Social links in contact section

### Modify Colors

Edit `:root` variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... other colors */
}
```

### Update GitHub Username

In `script.js`, change the GitHub username in the API call:
```javascript
const response = await fetch('https://api.github.com/users/YOUR_USERNAME/repos?type=public&sort=updated');
```

## Features Breakdown 📋

### Projects Section
- Automatically fetches your GitHub repositories
- Displays project name, language, stars, and forks
- Links directly to GitHub repositories
- Fallback to sample projects if API fails

### Contact Form
- Client-side validation
- Email format verification
- Success/error notifications
- Mobile-friendly layout

### Animations
- Floating shapes in hero section
- Fade-in effects on scroll
- Hover animations on cards
- Smooth scroll transitions
- Parallax effects

## Performance Optimization ⚡

- Optimized images and graphics
- Minimal dependencies (no frameworks)
- Efficient CSS animations using GPU acceleration
- Lazy loading of images when possible

## Browser Support 🌐

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment 🚀

### Deploy on GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings
3. Under "Pages" section, select `main` branch as source
4. Your site will be live at `https://silwaldipesh01.github.io/portfolio`

### Other Hosting Options
- Netlify
- Vercel
- Firebase Hosting
- Heroku

## Troubleshooting 🔧

**Projects not loading?**
- Check if GitHub API rate limit is exceeded (60 requests/hour)
- Ensure your GitHub username is correct in script.js
- Check browser console for errors

**Styling not applying?**
- Clear browser cache
- Ensure all CSS file is in the same directory
- Check for CSS syntax errors

## License 📝

This project is open source and available under the MIT License.

## Contact 📧

- GitHub: [@silwaldipesh01](https://github.com/silwaldipesh01)
- Feel free to reach out through the contact form on the website!

## Future Enhancements 🎯

- [ ] Add blog section
- [ ] Implement dark/light theme toggle
- [ ] Add more animation effects
- [ ] SEO optimization
- [ ] Performance monitoring
- [ ] Email backend integration
- [ ] Multi-language support

---

Made with ❤️ by Silwal Dipesh
