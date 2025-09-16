# 🏗️ TISKA Construcciones y Servicios - Website

A modern, responsive website for TISKA Construcciones y Servicios, a Mexican construction company specializing in civil works and electrical installations.

## 📋 Project Overview

**TISKA Construcciones y Servicios** is a professional construction company website built with modern web technologies. The site showcases the company's services, projects, and values while providing an excellent user experience across all devices.

### 🎯 Company Information
- **Company Name:** TISKA Construcciones y Servicios
- **Industry:** Construction & Electrical Services
- **Location:** Monte Alban 604, Colonia letran valle, CP 03650, Benito Juarez, CDMX
- **Email:** tiskamx@outlook.com
- **Phone:** +52 55 5555 5555

### 🏆 Core Values
- **Calidad** - Highest quality in all projects
- **Precio** - Competitive prices without compromising quality
- **Compromiso** - Total dedication to clients
- **Entrega en tiempo** - Punctual delivery of agreed timelines

## 🚀 Features

### ✨ Modern Design
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Hover effects, smooth transitions, and engaging animations
- **Professional Branding** - Custom TISKA logo and consistent color scheme

### 📱 Key Components
- **Hero Section** - Eye-catching landing area with company principles
- **Navigation Menu** - Easy access to all sections
- **WhatsApp Integration** - Direct contact button with beautiful animations
- **Project Showcase** - Comprehensive projects gallery
- **Services Section** - Detailed service offerings
- **Contact Information** - Complete contact details and form
- **Client Logos** - Trusted partners display

### 🛠️ Technical Features
- **Fast Loading** - Optimized for performance
- **SEO Friendly** - Proper meta tags and structure
- **Cross-browser Compatible** - Works on all modern browsers
- **Mobile First** - Designed with mobile users in mind

## 📁 Project Structure

```
site/
├── assets/
│   ├── img/                    # Images and photos
│   │   ├── about.jpg
│   │   └── hero.jpg
│   ├── logos/                  # Company and client logos
│   │   ├── cliente-a.svg
│   │   ├── cliente-b.svg
│   │   ├── cliente-c.svg
│   │   ├── cliente-d.svg
│   │   └── tiska-logo.svg      # Main company logo
│   └── qr/                     # QR code assets
├── content/
│   └── content.es.json         # Dynamic content configuration
├── tools/
│   └── make-qr.html           # QR code generator utility
├── index.html                  # Homepage
├── nosotros.html              # About page
├── proyectos.html             # Projects showcase
├── servicios.html             # Main services page
├── servicios-adicionales.html # Additional services
└── README.md                  # This file
```

## 🎨 Pages Overview

### 🏠 **Homepage (index.html)**
- Hero section with company principles
- Features showcase
- About section
- Contact information
- Client logos
- WhatsApp contact button

### 👥 **About Us (nosotros.html)**
- Company history and mission
- Team information
- Core values display
- Company statistics

### 🏗️ **Projects (proyectos.html)**
- Project showcase gallery
- Project categories
- Statistics and achievements
- Call-to-action sections

### ⚡ **Services (servicios.html)**
- Main services offered
- Service descriptions
- Contact forms
- Service categories

### 🔧 **Additional Services (servicios-adicionales.html)**
- Specialized services
- Process overview
- Additional offerings
- Consultation information

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (Vanilla)** - Interactive functionality
- **SVG** - Scalable vector graphics for logos

### Design & UX
- **Responsive Design** - Mobile-first approach
- **Modern Animations** - Smooth transitions and effects
- **Professional Typography** - Inter font family
- **Color Scheme** - Red and white brand colors

### Performance
- **CDN Resources** - Tailwind CSS and Google Fonts
- **Optimized Images** - Web-optimized graphics
- **Minimal Dependencies** - Fast loading times

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A web server (for local development)
- Git (for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/greensky0077/TISKA_Site.git
   cd TISKA_Site
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Open `http://localhost:8000` in your browser

## 📝 Content Management

### Updating Content
The website uses a JSON-based content management system. To update content:

1. **Edit `content/content.es.json`**
   - Update company information
   - Modify service descriptions
   - Change contact details
   - Update client information

2. **Key Content Areas**
   - `hero_title` - Main headline
   - `hero_sub` - Subtitle
   - `features` - Company values/features
   - `about_text` - About section content
   - `contact_*` - Contact information
   - `clients` - Client logos and names

### Adding New Content
- **New Pages**: Create new HTML files following the existing structure
- **New Images**: Add to `assets/img/` directory
- **New Logos**: Add to `assets/logos/` directory
- **Update Navigation**: Modify navigation menus in all HTML files

## 🎨 Customization

### Colors
The website uses a red and white color scheme. To change colors:
- Update Tailwind CSS classes in HTML files
- Modify the gradient definitions in CSS
- Update the logo SVG colors

### Fonts
- Primary font: Inter (Google Fonts)
- To change fonts, update the Google Fonts link and CSS font-family

### Layout
- All pages use responsive grid layouts
- Mobile-first design approach
- Easy to modify with Tailwind CSS classes

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop** (1024px and above)
- **Tablet** (768px - 1023px)
- **Mobile** (320px - 767px)

### Breakpoints
- `sm:` - 640px and up
- `md:` - 768px and up
- `lg:` - 1024px and up
- `xl:` - 1280px and up

## 🔧 Maintenance

### Regular Updates
- Update contact information as needed
- Add new projects to the showcase
- Update client logos and testimonials
- Refresh content to keep it current

### Performance Optimization
- Compress images before adding
- Minimize CSS and JavaScript if adding custom code
- Use web-optimized formats (WebP for images, SVG for icons)

## 📞 Support

For technical support or questions about the website:
- **Email:** tiskamx@outlook.com
- **Phone:** +52 55 5555 5555
- **Address:** Monte Alban 604, Colonia letran valle, CP 03650, Benito Juarez, CDMX

## 📄 License

This project is proprietary to TISKA Construcciones y Servicios. All rights reserved.

## 🚀 Deployment

### GitHub Pages
The website can be deployed directly from GitHub:
1. Push changes to the master branch
2. Enable GitHub Pages in repository settings
3. Select source branch (master)
4. Website will be available at `https://username.github.io/TISKA_Site`

### Other Hosting Options
- **IONOS** - Current hosting provider
- **Netlify** - Easy deployment with drag-and-drop
- **Vercel** - Fast deployment with Git integration
- **Any web hosting service** - Upload files via FTP

## 📈 Future Enhancements

### Planned Features
- [ ] Contact form functionality
- [ ] Blog section for company news
- [ ] Project filtering and search
- [ ] Multi-language support
- [ ] Admin panel for content management
- [ ] SEO optimization improvements

### Technical Improvements
- [ ] Progressive Web App (PWA) features
- [ ] Advanced animations and interactions
- [ ] Performance monitoring
- [ ] Analytics integration
- [ ] Security enhancements

---

**Built with ❤️ for TISKA Construcciones y Servicios**

*Last updated: December 2024*

