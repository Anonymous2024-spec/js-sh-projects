# Character Counter Textarea

A lightweight, responsive textarea component with real-time character counting and maximum limit enforcement. Perfect for forms, comment sections, or any text input that requires length validation.

## 🔴 Live Demo
Visit the live demo: [Character Counter Demo](https://roadmap.sh/projects/restricted-textarea) 
*(Note: Replace with your actual project URL when deployed)*

## ✨ Features

- 📝 Real-time character counting
- 🚫 Maximum character limit enforcement
- 🎨 Visual feedback on limit reached
- 📱 Responsive design
- ✨ Smooth animations
- 📋 Paste event handling
- 🎯 No external dependencies

## 🚀 Quick Start

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/character-counter.git
cd character-counter
```

2. No additional dependencies required! The project uses vanilla JavaScript and CSS.

### Usage

1. Open `index.html` in your web browser to see the character counter in action.
   - Use a local development server (like Live Server in VS Code)
   - Or simply double-click the index.html file

2. To integrate into your existing project:

```html
<!-- Add to your HTML -->
<div class="textarea-wrapper">
  <textarea 
    class="character-textarea" 
    placeholder="Start typing... (Maximum 200 characters)"
  ></textarea>
  <div class="counter">0 / 200</div>
</div>
<div class="limit-message">Character limit reached!</div>
```

```javascript
// Add the JavaScript
const textarea = document.querySelector('.character-textarea');
const counter = document.querySelector('.counter');
const limitMessage = document.querySelector('.limit-message');
const CHAR_LIMIT = 200;

// Add the event listeners and functions from the script section
```

## 🛠️ Customization

### Modifying Character Limit
Change the `CHAR_LIMIT` constant in the JavaScript:

```javascript
const CHAR_LIMIT = 500; // Change to your desired limit
```

### Styling
Modify the CSS variables to match your brand colors:

```css
.character-textarea {
    /* Modify border color */
    border: 2px solid #ccc;
    /* Modify focus color */
    border-color: #007bff;
}

.counter {
    /* Modify counter style */
    background: rgba(255, 255, 255, 0.9);
    color: #666;
}
```

## 💻 Technical Details

### Features Explained

1. **Real-time Counting**
   - Updates character count as user types
   - Handles backspace and delete operations
   - Manages paste events

2. **Limit Enforcement**
   - Prevents typing beyond limit
   - Truncates pasted text if it exceeds limit
   - Visual feedback when limit is reached

3. **Visual Feedback**
   - Border color changes
   - Counter color updates
   - Warning message appears
   - Smooth transitions

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)



