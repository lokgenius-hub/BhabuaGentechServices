# GentechServices Logo & Graphics Files

This folder contains all the custom-designed SVG logos and illustrations for the GentechServices website.

## 📁 Files Included

### Logos
1. **logo.svg** - Full logo with circuit design (200x60px)
   - Use in: High-resolution displays, marketing materials
   
2. **favicon.svg** - Website favicon (64x64px)
   - Use in: Browser tabs, bookmarks, mobile home screen

### Illustrations
3. **hero-illustration.svg** - Main hero section illustration (600x600px)
   - Features: Laptop, mobile app, website, cloud services, analytics cards
   - Use in: Homepage hero section

## 🎨 Logo Variants

The logo comes in two styles:

### Circuit Design (Default - Used on Website)
- Modern microchip/circuit board aesthetic
- Blue (#2563eb) primary color
- Tech-inspired with connection pins
- Perfect for IT/digital services

### Gear Design (Alternative)
- Mechanical gear icon
- Available in logo.svg file
- Can be swapped if preferred

## 💡 Usage Guidelines

### In HTML
```html
<!-- Favicon -->
<link rel="icon" type="image/svg+xml" href="favicon.svg">

<!-- Logo in Navigation -->
<img src="logo.svg" alt="GentechServices Logo" class="logo">

<!-- Hero Illustration -->
<img src="images/hero-illustration.svg" alt="Digital Services">
```

### Color Scheme
- **Primary Blue**: #2563eb
- **Accent Cyan**: #06b6d4
- **Dark Gray**: #1e293b
- **White**: #ffffff

## ✏️ Customization

All SVG files can be edited in:
- Adobe Illustrator
- Inkscape (free)
- Figma (online)
- Any text editor (SVG is XML-based)

### Changing Colors
Open the SVG file in a text editor and find:
- `fill="#2563eb"` - Change this to your brand color
- `stroke="#1e40af"` - Change this to match

## 📏 Dimensions

| File | Size | Format | Usage |
|------|------|--------|-------|
| favicon.svg | 64x64px | SVG | Browser favicon |
| logo.svg | 200x60px | SVG | Navigation, footer |
| hero-illustration.svg | 600x600px | SVG | Hero section |

## 🔄 Export Options

To convert SVG to PNG (if needed):

### Online Tools
- https://cloudconvert.com/svg-to-png
- https://svgtopng.com/

### Command Line (ImageMagick)
```bash
convert -background none favicon.svg -resize 64x64 favicon.png
convert -background none logo.svg -resize 400x120 logo.png
```

## ✨ Benefits of SVG

- **Scalable**: Looks sharp at any size
- **Lightweight**: Small file size
- **Editable**: Easy to modify colors and shapes
- **Accessible**: Can be styled with CSS
- **SEO-friendly**: Search engines can read SVG content

## 🎯 Current Implementation

The logo is currently embedded inline in the HTML for:
1. Better performance (no extra HTTP request)
2. Easy CSS styling
3. Hover effects and animations
4. Color customization with CSS

## 📝 Notes

- All graphics are original designs created for GentechServices
- SVG format ensures crisp display on retina/high-DPI screens
- No external image dependencies
- Fully responsive and mobile-friendly

## 🆘 Need Changes?

To request logo modifications:
- Email: contact@gentechservices.com
- Phone: +91 90000 00000

---

**Created with ❤️ for GentechServices**
