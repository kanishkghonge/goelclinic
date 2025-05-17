# Goel Urology and Dental Clinic Website

A modern, responsive single-page website for Goel Urology and Dental Clinic featuring a sleek design with glassmorphism elements and subtle animations.

## Features

- Single-page scrollable design with section-based navigation
- Fully responsive layout (mobile-first approach)
- Modern UI with glassmorphism effects
- Smooth scrolling and animations
- Testimonial slider
- Embedded appointment booking system
- Interactive Google Maps integration
- Mobile-friendly navigation menu

## Files Structure

- `index.html` - Main HTML structure
- `styles.css` - All styling including responsive design
- `script.js` - JavaScript for animations and interactivity
- `photos/` - Directory containing all image assets

## How to Use

1. Simply open the `index.html` file in a web browser to view the website locally.
2. To deploy the website, upload all files to your web hosting service.

## Customization

### Colors

The website uses a color scheme of greens and blues, defined as CSS variables in the `styles.css` file:

```css
:root {
    --primary-color: #0a9396;
    --secondary-color: #005f73;
    --accent-color: #94d2bd;
    --light-color: #e9ecef;
    --dark-color: #1d3557;
}
```

You can modify these values to change the color scheme throughout the site.

### Images

Replace the images in the `photos/` directory with your own images while keeping the same filenames:

- `logomain.jpg` - Clinic logo
- `dr-shailendra-kumar-goel.jpg` - Dr. Shailendra Goel's photo
- `sonalgoel-dentist.jpg` - Dr. Sonal Goel's photo
- `clinic-outside.png` - Clinic exterior photo

### Content

Edit the HTML file to update:

- Doctor information
- Services offered
- Clinic timings
- Contact information
- Testimonials

## Browser Compatibility

The website is compatible with all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Notes

- The appointment booking system is embedded via an iframe pointing to `http://34.42.189.227`. Update this URL if your booking system changes.
- The Google Maps embed uses coordinates for the clinic's location. Update the iframe src if the location changes.

## Credits

- Fonts: DM Sans from Google Fonts
- Icons: Font Awesome 6.4.0 