# Property Listing Website

## 📁 Folder Structure

Create the following folder structure for your property listing website:

```
property-listing/
├── index.html
├── style.css
├── images/
│   ├── image1.jpg
│   ├── image2.jpg
│   ├── image3.jpg
│   ├── image4.jpg
│   ├── image5.jpg
│   └── image6.jpg
└── README.md
```

## 📸 Image Requirements

Place your property photos in the `images` folder with these simple names:

- **`image1.jpg`** - Any property photo
- **`image2.jpg`** - Any property photo
- **`image3.jpg`** - Any property photo
- **`image4.jpg`** - Any property photo
- **`image5.jpg`** - Any property photo
- **`image6.jpg`** - Any property photo

### Flexible Image Naming:
- Use **any image format**: `.jpg`, `.jpeg`, `.png`, `.webp`
- **Easy numbering**: Just rename your photos to `image1`, `image2`, etc.
- **No specific content required**: Use any property photos you have
- **Add/Remove easily**: Want fewer images? Just remove the `<img>` tags from HTML

### Image Specifications:
- **Format**: JPG, PNG, or WebP
- **Recommended Size**: 800x600 pixels or higher
- **Aspect Ratio**: 4:3 or 16:9 works best
- **File Size**: Keep under 2MB per image for faster loading

## 🔧 Setup Instructions

1. **Download the files**: `index.html` and `style.css`
2. **Create folder structure** as shown above
3. **Add your property images** to the `images` folder
4. **Customize the content** in `index.html`:
   - Update property details (title, location, price, area)
   - Change agent contact information
   - Update Google Maps embed code
   - Modify property features list

## 🎨 Customization

### Update Property Details:
- Edit the `<title>` tag and header content
- Change price and area in the `.price-area` section
- Update property description

### Update Agent Contact:
- Change agent name, phone, and email
- Update WhatsApp link: Replace `919876543210` with actual number
- Update email link with actual email address

### Update Location:
- Replace the Google Maps iframe `src` with your actual location embed code
- Get embed code from: Google Maps → Share → Embed a map

### Add/Remove Images:
- **To add more images**: Add them to the `images` folder as `image7.jpg`, `image8.jpg`, etc., and add corresponding `<img>` tags in the HTML
- **To remove images**: Simply delete the unwanted `<img>` tags from the gallery section in `index.html`
- **To change image names**: Update the `src` attribute in the `<img>` tags to match your file names

### Supported Image Formats:
- **JPG/JPEG**: `image1.jpg` or `image1.jpeg`
- **PNG**: `image1.png` 
- **WebP**: `image1.webp`

### Custom Image Names:
If you want to use your own naming convention, just update the `src` attributes in the HTML:
```html
<img src="images/your-custom-name.jpg" alt="Property Image" />
```

## 🌐 Testing

1. Open `index.html` in a web browser
2. Test WhatsApp and email links
3. Check responsive design on different screen sizes
4. Verify all images load properly

## 📱 Mobile Optimization

The website is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones

## 🔗 Links Format

- **WhatsApp**: `https://wa.me/COUNTRY_CODE_PHONE_NUMBER`
- **Email**: `mailto:email@example.com`

## 🚀 Going Live

To publish your website:
1. Upload all files to your web hosting provider
2. Ensure the folder structure is maintained
3. Test all links and images after upload

## 📞 Support

If you need help customizing the website or have questions about the code, refer to the HTML and CSS files - they contain clear, readable code with proper structure.

## 🔄 Quick Customization Checklist

- [ ] Update property title and location
- [ ] Change price and area details
- [ ] Replace agent contact information
- [ ] Update WhatsApp number and email
- [ ] Add actual property images
- [ ] Update Google Maps location
- [ ] Modify property features list
- [ ] Update property description
- [ ] Test all links and functionality

## 📋 File Descriptions

- **`index.html`** - Main webpage with property listing
- **`style.css`** - All styling and design rules
- **`images/`** - Folder containing property photos
- **`README.md`** - This instruction file

## 🎯 Features Included

- Responsive design for all devices
- WhatsApp direct contact integration
- Email contact with pre-filled subject
- Google Maps integration
- Image gallery with hover effects
- Modern gradient design
- Professional property listing layout
- Mobile-optimized interface