# 🕌 Rahma Islamic Centre - Complete Website

## 📦 Files Included

### HTML Pages (All comments in English):
✅ **index.html** - Home page with prayer times widget
✅ **prayer-times.html** - Monthly prayer schedule with table
✅ **about.html** - About Us, Mission & Values
✅ **contact.html** - Contact form and Google Maps
⚠️ **activities.html** - TO BE CREATED (Activities & Services)
⚠️ **donate.html** - TO BE CREATED (Donation page)
⚠️ **newsletter.html** - TO BE CREATED (Newsletter signup)

### CSS & Assets:
✅ **style.css** - Complete stylesheet for all pages
✅ **islamic-pattern.png** - Background pattern for site
⚠️ **logo.png** - YOUR LOGO (you need to add this)
⚠️ **masjid.png** - YOUR HERO IMAGE (you need to add this)

## 🎨 Design Features

- Deep navy blue (#0B2545) and gold (#D4AF37) color scheme
- Islamic pattern background throughout
- Beige navbar with pattern
- Fully responsive mobile design
- Real-time prayer times API integration
- Monthly prayer schedule table
- Google Maps integration

## 🔧 Setup Instructions

1. **Extract all files** to a folder
2. **Add your images**:
   - `logo.png` - Your mosque logo (circular, transparent background)
   - `masjid.png` - Your hero/mosque image
   - `islamic-pattern.png` - Already included!

3. **Configure Prayer Times**:
   - Open `index.html`
   - Find `MOSQUE_CONFIG` section (line ~300)
   - Update latitude, longitude, city, country

4. **Test locally**:
   - Open `index.html` in a web browser
   - Check all navigation links work
   - Verify prayer times load correctly

## 📄 Pages Status

### ✅ COMPLETED:
1. **Home (index.html)**
   - Hero section
   - About section with circular logo
   - Newsletter strip (navy blue)
   - Prayer times widget (live API)
   - Activities cards
   - Footer

2. **Prayer Times (prayer-times.html)**
   - Monthly calendar table
   - Month selector
   - Print button
   - Today's prayer times widget
   - Automatic API loading

3. **About Us (about.html)**
   - Full about text
   - Photo gallery (6 images)
   - Mission statement section
   - Our values (6 value cards)

4. **Contact Us (contact.html)**
   - Contact form
   - Contact information cards
   - Google Maps embed
   - Form submission handling

### ⚠️ TO BE COMPLETED:
5. **Activities & Services** - Needs creation
6. **Donate Page** - Needs creation
7. **Newsletter Page** - Needs creation

## 🌐 Prayer Times API

The site uses **Aladhan Prayer Times API**:
- Automatically calculates prayer times
- Based on your mosque location
- Updates daily
- Supports multiple calculation methods

### Configuration:
```javascript
const MOSQUE_CONFIG = {
    latitude: 49.8951,    // Change this
    longitude: -97.1384,  // Change this
    city: "Winnipeg",     // Change this
    country: "Canada",    // Change this
    method: 2,            // 2 = ISNA for Canada
};
```

## 🎯 Key Features

### Navigation:
- Home
- Prayer Times
- Activities & Services
- About Us
- Contact Us
- DONATE button

### Prayer Times:
- Real-time API integration
- Monthly calendar view
- Printable schedule
- Today's times widget

### Design:
- Islamic pattern background
- Beige navbar with larger pattern
- Navy blue and gold colors
- Fully responsive
- Mobile hamburger menu

## 📱 Responsive Design

All pages work on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔗 Navigation Structure

```
Home (index.html)
├── Prayer Times (prayer-times.html)
├── Activities & Services (activities.html) ⚠️
├── About Us (about.html)
├── Contact Us (contact.html)
├── Donate (donate.html) ⚠️
└── Newsletter (newsletter.html) ⚠️
```

## 🎨 Color Scheme

- **Primary Navy**: #0B2545
- **Gold Accent**: #D4AF37
- **Light Background**: #F5F5F5
- **Navbar Beige**: #D4C4B0
- **Footer Dark**: #000b14

## 📝 Notes

- All JavaScript comments are in English
- All HTML comments are in English
- Prayer times auto-refresh every hour
- Forms have basic validation
- Google Maps coordinates need verification

## 🆘 Support

For issues or questions:
- Check CONFIGURATION.md for prayer times setup
- Verify all image files are present
- Test in modern browsers (Chrome, Firefox, Safari, Edge)

---

**Built for Rahma Islamic Centre, Winnipeg** 🕌✨
