# Modern Academic Jekyll Theme

A beautiful, modern Jekyll theme designed specifically for academic portfolios and personal websites. Features a clean design with dark/light mode toggle, responsive layout, and comprehensive sections for showcasing academic work.

## Features

- 🌙 **Dark/Light Mode Toggle** - Automatic theme switching with user preference persistence
- 📱 **Fully Responsive** - Mobile-first design that works on all devices
- 🎨 **Modern Design** - Clean, professional layout with smooth animations
- 📚 **Academic Focus** - Dedicated sections for CV, publications, research, and contact
- ⚡ **Fast Loading** - Optimized CSS and minimal JavaScript
- 🔍 **SEO Optimized** - Built-in SEO tags and structured data
- 🎯 **Easy Customization** - Well-organized CSS variables and modular structure

## Quick Start

1. **Download the template files** to your GitHub Pages repository
2. **Add your profile image** to `assets/images/profile.jpg`
3. **Update `_config.yml`** with your information
4. **Customize the content** in the markdown files
5. **Push to GitHub** and your site will be live!

## File Structure

```
├── _config.yml              # Site configuration
├── _layouts/
│   ├── default.html         # Main layout with navigation
│   ├── page.html           # Page layout
│   └── publication.html    # Publication layout
├── assets/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   └── images/
│       └── profile.jpg     # Your profile image
├── index.html              # Homepage
├── cv.md                   # CV page
├── publications.md         # Publications page
├── research.md            # Research page
├── contact.md             # Contact page
└── Gemfile                # Jekyll dependencies
```

## Customization

### 1. Site Configuration

Edit `_config.yml` to update your personal information:

```yaml
title: "Your Name"
email: "your.email@university.edu"
description: "Your academic description"

author:
  name: "Your Name"
  bio: "Your bio"
  location: "Your Location"
  # ... other details
```

### 2. Profile Image

Replace `assets/images/profile.jpg` with your own profile photo. Recommended size: 400x400px.

### 3. Content Pages

Update the markdown files with your own content:
- `index.html` - Homepage with hero section
- `cv.md` - Your curriculum vitae
- `publications.md` - Your publications and talks
- `research.md` - Your research projects
- `contact.md` - Contact information

### 4. Styling

The theme uses CSS custom properties for easy customization. Edit `assets/css/main.css` to modify:
- Colors and themes
- Typography
- Spacing and layout
- Animations and transitions

## Theme Colors

The theme includes both light and dark mode with the following color scheme:

**Light Mode:**
- Primary: Blue (#3b82f6)
- Secondary: Indigo (#6366f1)
- Background: White (#ffffff)
- Text: Dark gray (#1e293b)

**Dark Mode:**
- Primary: Light blue (#60a5fa)
- Secondary: Indigo (#6366f1)
- Background: Dark blue (#0f172a)
- Text: Light gray (#f8fafc)

## Icons

The theme uses [Lucide Icons](https://lucide.dev/) for a consistent, modern icon set. Icons are loaded via CDN and initialized with JavaScript.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Local Development

To run the site locally:

1. Install Jekyll: `gem install jekyll bundler`
2. Install dependencies: `bundle install`
3. Run the server: `bundle exec jekyll serve`
4. Open `http://localhost:4000` in your browser

## GitHub Pages Deployment

This theme is designed to work seamlessly with GitHub Pages:

1. Push the template files to your `username.github.io` repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://username.github.io`

## License

This theme is open source and available under the MIT License.

## Credits

- Built with [Jekyll](https://jekyllrb.com/)
- Icons by [Lucide](https://lucide.dev/)
- Fonts by [Google Fonts](https://fonts.google.com/)

---

**Note:** Remember to replace placeholder content with your own information and add your profile image before deploying!



<!-- Triggering new build -->

