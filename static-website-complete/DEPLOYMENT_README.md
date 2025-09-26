# Static Website Deployment Guide

This ZIP file contains a static version of the Swasth Nabha healthcare platform that can be deployed on any static hosting service.

## Contents

The ZIP file contains:
- `index.html` - Main homepage
- `login.html` - Login page
- `dashboard.html` - Dashboard page
- `symptom-checker.html` - AI-powered symptom checker (with mock responses)
- `consultations.html` - Consultations page
- `pharmacies.html` - Pharmacies page
- `records.html` - Medical records page
- Various dashboard pages for different user types (doctor, pharmacy, ASHA)
- `_next/` - JavaScript and CSS assets
- `favicon.ico` - Website icon

## Deployment Instructions

### For Hostinger:
1. Extract all files from the ZIP to your hosting directory
2. Upload all files to the `public_html` folder
3. The website will be accessible at your domain

### For Firebase Hosting:
1. Extract the ZIP file
2. Run `firebase init hosting` in the extracted directory
3. Run `firebase deploy`

### For Netlify:
1. Extract the ZIP file
2. Drag and drop the extracted folder to Netlify
3. Your site will be deployed automatically

### For Vercel:
1. Extract the ZIP file
2. Connect your GitHub repository or drag and drop the folder
3. Vercel will automatically deploy your static site

## Important Notes

- The symptom checker now uses mock responses instead of AI analysis (suitable for static hosting)
- All pages are fully functional with client-side routing
- The website supports multiple languages (English, Punjabi, Hindi)
- All styling and JavaScript functionality is preserved

## File Structure

```
/
├── index.html (Homepage)
├── login.html
├── dashboard.html
├── symptom-checker.html
├── consultations.html
├── pharmacies.html
├── records.html
├── asha/dashboard.html
├── doctor/dashboard.html
├── pharmacy/dashboard.html
├── pharmacy.html
├── _next/ (JavaScript and CSS assets)
└── favicon.ico
```

## Browser Support

This static website works in all modern browsers including:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Contact

For technical support or questions about deployment, please contact the development team.
