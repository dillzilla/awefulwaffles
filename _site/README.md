# Awefull Waffles Restaurant Website 🧇

A beautifully crafted Jekyll website for **Awefull Waffles**, a retro-themed restaurant specializing in delicious waffles and classic comfort food. Built with modern web technologies and optimized for both user experience and search engines.

## 🎨 Design Features

- **Retro Classic Theme**: Authentic 1950s diner aesthetic with warm colors and vintage styling
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Modern Technology**: Built with Jekyll and Tailwind CSS for fast loading and easy maintenance
- **SEO Optimized**: Comprehensive meta tags, structured data, and search engine optimization

## 🏗️ Built With

- **Jekyll 4.3.0** - Static site generator
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **HTML5 & CSS3** - Modern web standards
- **JavaScript** - Interactive functionality
- **Liquid** - Templating language

## 📋 Website Structure

### Pages Included:
1. **Home Page** (`index.md`)
   - Hero section with restaurant introduction
   - Featured menu items preview
   - Customer testimonials
   - Call-to-action sections

2. **Menu Page** (`menu.md`)
   - Signature waffles with descriptions and prices
   - Breakfast combos and hearty meals
   - Sandwiches and light bites
   - Complete beverage menu
   - Sticky navigation for easy browsing

3. **About Us Page** (`about.md`)
   - Restaurant history and story
   - Meet the team section
   - Values and mission statement
   - Awards and recognition

4. **Contact Page** (`contact.md`)
   - Contact information and hours
   - Interactive contact form
   - Map integration placeholder
   - Social media links

5. **404 Error Page** (`404.html`)
   - Custom-designed error page with restaurant branding
   - Helpful navigation back to main content

## 🚀 Getting Started

### Prerequisites
- Ruby (version 2.7 or higher)
- Bundler gem
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd awefull-waffles-website
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the website**
   Open your browser and navigate to `http://localhost:4000`

### Build for Production

```bash
bundle exec jekyll build
```

The built site will be generated in the `_site` directory.

## 🎯 SEO Features

### Technical SEO
- **Semantic HTML5** structure for better accessibility
- **Meta descriptions** and title tags optimized for search engines
- **Open Graph** and **Twitter Card** meta tags for social media sharing
- **Schema.org structured data** for local business information
- **XML sitemap** (`sitemap.xml`) for search engine indexing
- **Robots.txt** file for search engine crawling guidance

### Content SEO
- **Keyword optimization** for restaurant and food-related terms
- **Local SEO** optimization with address and contact information
- **Image alt texts** and descriptive content
- **Internal linking** strategy between pages

## 🎨 Customization

### Colors (Retro Theme)
- **Orange** (`#FF6B35`) - Primary brand color
- **Yellow** (`#F7BA3E`) - Accent and button color
- **Brown** (`#8B4513`) - Text and footer background
- **Cream** (`#FFF8DC`) - Background and card colors
- **Red** (`#DC143C`) - Highlight and price color

### Fonts
- **Display Font**: Impact, Arial Black (for headings)
- **Body Font**: Georgia, serif (for readable content)

### Configuration
Edit `_config.yml` to update:
- Restaurant information (name, address, phone, hours)
- Social media links
- SEO settings
- Site navigation

## 📱 Responsive Design

The website is fully responsive with breakpoints optimized for:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px and above

## 🔧 Maintenance

### Updating Content
- **Menu items**: Edit `menu.md` to add/remove items and update prices
- **Restaurant info**: Update `_config.yml` for contact details and hours
- **About section**: Modify `about.md` to update team members and story
- **Images**: Add restaurant photos to `/assets/images/` directory

### Performance Optimization
- Images should be optimized and properly sized
- Consider implementing lazy loading for images
- Monitor Core Web Vitals for optimal performance

## 🚢 Deployment Options

### GitHub Pages
1. Push code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `gh-pages`)

### Netlify
1. Connect your Git repository to Netlify
2. Set build command: `bundle exec jekyll build`
3. Set publish directory: `_site`

### Custom Server
1. Build the site: `bundle exec jekyll build`
2. Upload contents of `_site` directory to your web server

## 📁 File Structure

```
awefull-waffles-website/
├── _config.yml              # Jekyll configuration
├── _layouts/
│   └── default.html         # Main layout template
├── _site/                   # Generated site (git ignored)
├── assets/
│   └── images/              # Restaurant images and assets
├── index.md                 # Home page
├── menu.md                  # Menu page
├── about.md                 # About page
├── contact.md               # Contact page
├── 404.html                 # Custom error page
├── sitemap.xml              # SEO sitemap
├── robots.txt               # Search engine instructions
├── Gemfile                  # Ruby dependencies
└── README.md                # This file
```

## 🎯 Future Enhancements

Consider adding these features:
- **Online ordering system** integration
- **Real-time table availability** system
- **Customer review** integration
- **Newsletter signup** functionality
- **Multi-language support**
- **Google Analytics** tracking
- **Live chat** support

## 📞 Support

For questions about this website template or customization requests:
- Review the Jekyll documentation: https://jekyllrb.com/docs/
- Check Tailwind CSS documentation: https://tailwindcss.com/docs
- Submit issues through the repository's issue tracker

## 📄 License

This project is created for educational and demonstration purposes. Feel free to use and modify for your restaurant business needs.

---

**Built with ❤️ and lots of syrup!** 🧇

*Ready to serve your customers with an awefull good online presence!*