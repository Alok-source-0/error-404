# Custom 404 Error Page

A stylish and user-friendly custom 404 error page built with HTML and CSS. This project provides a better user experience when visitors land on non-existent or broken links.

## Features

- ✨ **Clear "Page Not Found" message** - Immediately informs users about the error
- 🎨 **Modern gradient design** - Beautiful purple gradient background with professional styling  
- 🤖 **Animated robot illustration** - Friendly animated robot character to make the error less frustrating
- 📱 **Fully responsive** - Works perfectly on desktop, tablet, and mobile devices
- 🔗 **Homepage navigation** - Clear link to return to the main site
- 🎭 **Smooth animations** - Subtle animations and hover effects for enhanced UX

## Demo

![Desktop View](https://github.com/user-attachments/assets/51b05d4d-6e70-415a-ae3b-b551ddadcd85)

*Responsive design shown on different screen sizes*

## Files

- `index.html` - Main HTML structure for the 404 error page
- `style.css` - CSS styling with animations, responsive design, and modern aesthetics

## Usage

1. Clone or download this repository
2. Use `index.html` as your custom 404 error page
3. Configure your web server to serve this page for 404 errors

### Apache Configuration

Add to your `.htaccess` file:
```apache
ErrorDocument 404 /index.html
```

### Nginx Configuration

Add to your server block:
```nginx
error_page 404 /index.html;
```

## Browser Support

This page works in all modern browsers including:
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Customization

You can easily customize the page by modifying:
- Colors in the CSS gradient backgrounds
- Text content in the HTML
- Animation timings and effects
- Robot illustration styling

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
