# MITS College Website

A fully responsive and modern website for Madanapalle Institute of Technology & Science (MITS College) built with HTML, CSS, and JavaScript.

## Features

### 🎨 Design & User Experience
- **Responsive Design**: Mobile-first approach with breakpoints for all device sizes
- **Modern UI**: Clean, professional design with smooth animations and hover effects
- **Apple-level Aesthetics**: Attention to detail with premium visual presentation
- **Smooth Scrolling**: Seamless navigation between sections
- **Interactive Elements**: Hover states, transitions, and micro-interactions

### 📱 Navigation
- **Fixed Navigation Bar**: Transparent background with blur effect that becomes solid on scroll
- **Mobile Menu**: Hamburger menu with smooth slide-in animation for mobile devices
- **Smooth Scrolling**: Click navigation links to smoothly scroll to sections

### 🏠 Sections

#### Home (Hero Section)
- Gradient background with college branding
- Call-to-action buttons
- Key statistics display (students, faculty, programs, placement rate)

#### About Us
- College mission and vision statements
- Key features with icons (Quality Education, Research & Innovation, Industry Connect)
- Campus image showcase

#### Courses
- Engineering programs offered at MITS:
  - Computer Science & Engineering
  - Electrical & Electronics Engineering
  - Electronics & Communication Engineering
  - Mechanical Engineering
  - Civil Engineering
  - Master of Technology (M.Tech)
- Interactive course cards with hover effects
- Program details including duration and level

#### Gallery
- **Interactive Image Slider**: 
  - Auto-play functionality (5-second intervals)
  - Manual navigation with previous/next buttons
  - Dot indicators for direct slide access
  - Keyboard navigation support (arrow keys)
  - Pause on hover
- Campus facilities showcase (Library, Labs, Buildings, Sports)

#### Contact
- **Contact Information**: Address, phone, email, office hours
- **Contact Form** with comprehensive JavaScript validation:
  - Real-time field validation
  - Error message display
  - Form submission simulation
  - Loading states and user feedback

### 🔧 Technical Features

#### JavaScript Functionality
- **Mobile Navigation Toggle**: Responsive hamburger menu
- **Scroll Effects**: Navbar background change on scroll
- **Gallery Slider**: Full-featured image carousel
- **Form Validation**: Comprehensive client-side validation
- **Smooth Scrolling**: Enhanced navigation experience
- **Intersection Observer**: Scroll-triggered animations
- **Performance Optimization**: Lazy loading for images

#### CSS Features
- **CSS Custom Properties**: Consistent color scheme and spacing
- **Flexbox & Grid**: Modern layout techniques
- **Animations**: Fade-in effects and smooth transitions
- **Responsive Breakpoints**: Mobile, tablet, and desktop optimized
- **Modern Typography**: Inter font family with proper hierarchy

## File Structure

```
mits-college-website/
├── home.html           # Main landing page
├── about.html          # About Us page
├── courses.html        # Engineering programs
├── gallery.html        # Campus gallery
├── contact.html        # Contact information and form
├── styles.css          # Complete CSS styling
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional but recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mits-college-website.git
   cd mits-college-website
   ```

2. **Open the website**
   
   **Option 1: Direct file opening**
   - Open `home.html` in your web browser
   
   **Option 2: Using a local server (recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
   
   Then open `http://localhost:8000/home.html` in your browser

### 🎯 Usage

1. **Navigation**: Use the navigation bar to move between different sections
2. **Mobile**: The website is fully responsive - test on different screen sizes
3. **Gallery**: Use arrow keys or click buttons to navigate through images
4. **Contact Form**: Fill out the form to see validation in action

## 🛠️ Customization

### Colors
The website uses CSS custom properties for easy customization:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #f59e0b;
    /* ... more variables */
}
```

### Content
- Update college information in HTML files
- Replace images with your own (maintain aspect ratios)
- Modify contact information in `contact.html`
- Update course offerings in `courses.html`

### Styling
- All styles are in `styles.css`
- Responsive breakpoints: 480px, 768px, 1024px
- Uses mobile-first approach

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design System

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Line Heights**: 150% for body, 120% for headings

### Color Palette
- **Primary**: #2563eb (Blue)
- **Secondary**: #1e40af (Dark Blue)
- **Accent**: #f59e0b (Amber)
- **Success**: #10b981 (Green)
- **Error**: #ef4444 (Red)

### Spacing System
- Uses 8px base unit
- Consistent spacing variables (xs: 4px, sm: 8px, md: 16px, lg: 24px, xl: 32px)

## 🚀 Performance Features

- **Optimized Images**: Using Pexels CDN for fast loading
- **Efficient CSS**: Minimal redundancy with CSS custom properties
- **JavaScript Optimization**: Event delegation and performance best practices
- **Lazy Loading**: Images load as needed
- **Smooth Animations**: 60fps animations with CSS transforms

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Images**: [Pexels.com](https://pexels.com) (royalty-free stock photos)
- **Icons**: [Font Awesome 6.0.0](https://fontawesome.com)
- **Fonts**: [Google Fonts](https://fonts.google.com) (Inter family)
- **Design Inspiration**: Modern web design principles and best practices

## 📞 Contact

**MITS College** - Madanapalle Institute of Technology & Science  
- 📧 Email: admissions@mits.ac.in
- 📱 Phone: +91-8571-255555
- 🌐 Website: [MITS College](https://github.com/yourusername/mits-college-website)

---

**Built with ❤️ for MITS College**  
*Excellence in Engineering Education since 1998*
