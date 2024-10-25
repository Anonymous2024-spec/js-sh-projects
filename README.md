# Cookie Consent Banner

A lightweight, customizable cookie consent banner implementation with support for different cookie categories and user preferences management.

## 🔴 Live Demo
Visit the live demo: [Cookie Consent Banner Demo](https://roadmap.sh/projects/cookie-consent) 
*(Note: Replace with your actual project URL when deployed)*

## ✨ Features

- 🎨 Modern, responsive design
- 🔄 Smooth animations
- 💾 Local storage for preference management
- ✅ Multiple cookie categories (Essential & Marketing)
- 📱 Mobile-friendly interface
- ♿ Accessible toggle switches
- 🔒 GDPR-compliant structure

## 🚀 Quick Start

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cookie-consent-banner.git
cd cookie-consent-banner
```

2. No additional dependencies are required! The project uses vanilla JavaScript and CSS.

### Usage

1. Open `index.html` in your web browser to see the cookie consent banner in action.
   - You can use a local development server like Live Server in VS Code
   - Or simply double-click the index.html file

2. To integrate into your existing project:

```html
<!-- Add to your HTML -->
<link rel="stylesheet" href="path/to/cookie-banner.css">
<script src="path/to/cookie-banner.js"></script>
```

Then copy the banner HTML structure:

```html
<div class="cookie-banner">
  <!-- Cookie banner content -->
</div>
```

## 🛠️ Customization

### Styling
Modify the CSS variables in the stylesheet to match your brand colors:

```css
.cookie-banner {
    /* Modify background color */
    background: #f8f9fa;
    /* Modify shadow */
    box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.1);
}

.btn-primary {
    /* Modify primary button color */
    background: #007bff;
}
```

### Adding New Cookie Categories
Add new cookie categories by extending the HTML structure:

```html
<div class="cookie-setting">
    <label class="switch">
        <input type="checkbox" id="newCookieCategory">
        <span class="slider"></span>
    </label>
    <div>
        <strong>New Cookie Category</strong>
        <p>Description of the new cookie category.</p>
    </div>
</div>
```

## 📝 Cookie Categories

1. **Essential Cookies**
   - Required for basic website functionality
   - Cannot be disabled
   - No personal data collection

2. **Marketing Cookies**
   - Used for personalized advertising
   - Analytics and traffic pattern analysis
   - Optional and can be disabled

## 💻 Technical Details

### Local Storage
The banner uses localStorage to save user preferences:
- `cookieChoice`: Tracks if user has made a choice
- `marketingCookies`: Stores marketing cookies preference

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📮 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/cookie-consent-banner](https://github.com/yourusername/cookie-consent-banner)
