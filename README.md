# 🔒 SecureCompress

**Privacy-first offline image compressor for official documents**

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://YOUR-USERNAME.github.io/securecompress/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![No Tracking](https://img.shields.io/badge/tracking-none-success)](https://YOUR-USERNAME.github.io/securecompress/)

**🌐 Live Demo:** https://YOUR-USERNAME.github.io/securecompress/

---

## 📸 The Problem

Most online image compressors:
- ❌ Expose sensitive ID photos/signatures to privacy risks
- ❌ Offer inconsistent or lossy compression
- ❌ Lack DPI or physical (cm-based) dimension controls
- ❌ Require internet connectivity

**There's a clear need for a privacy-first, offline, and guided image optimization tool.**

---

## ✨ The Solution

A secure, browser-based application that processes images **entirely on your device**. Perfect for government exam forms, job portals, visa applications, and any document requiring specific image specifications.

### Key Features
- 🔒 **100% Private** - No uploads, images never leave your browser
- 📏 **DPI Control** - Set precise resolution (72-600 DPI)
- 📐 **CM ↔ PX Converter** - Convert dimensions with DPI awareness
- 🔄 **Format Conversion** - JPEG, PNG, WEBP support
- ✂️ **Smart Resizing** - Custom width/height in pixels
- 💾 **Instant Download** - Process and save in seconds
- 🌐 **Fully Offline** - Works without internet after first load
- 📱 **Responsive Design** - Desktop and mobile friendly

---

## 🚀 Quick Start

1. **Visit** the [live demo](https://YOUR-USERNAME.github.io/securecompress/)
2. **Select** your image file
3. **Configure** output format, DPI, and dimensions
4. **Use** the CM→PX helper for physical size requirements
5. **Compress** and download your optimized image

No installation required. No sign-up. No tracking.

---

## 🎯 Perfect For

- 📋 Government exam applications (UPSC, SSC, banking exams)
- 💼 Job portals (Naukri, LinkedIn)
- ✈️ Visa/passport photo requirements
- 📄 Official document submissions
- 🆔 ID card photos
- 📝 Resume/CV attachments

---

## 🛠️ Tech Stack

- **HTML5 Canvas API** - Image processing and manipulation
- **Vanilla JavaScript** - Zero dependencies, pure performance
- **EXIF Parser** - Auto-detect DPI from JPEG metadata
- **CSS Grid** - Modern responsive layout

---

## 🔐 Privacy Promise

SecureCompress is built with privacy as the foundation:

- ✅ **No data collection** - We don't see or store your images
- ✅ **No cookies or tracking** - Zero analytics or monitoring
- ✅ **No external API calls** - Everything runs locally
- ✅ **No image uploads** - Files never leave your device
- ✅ **100% client-side** - All processing in your browser
- ✅ **Open source** - Code is fully auditable

**Your images stay on your device. Period.**

---

## 📖 How It Works

1. You select an image from your computer
2. The browser reads it using the File API
3. Image is rendered on an HTML5 Canvas
4. You adjust settings (size, format, DPI, quality)
5. Canvas processes the image with your settings
6. Download starts directly from your browser
7. **No server ever sees your image**

---

## 💡 CM to PX Helper

Understanding the relationship between physical size (cm) and pixels:
```
Formula: pixels = (centimeters × DPI) / 2.54

Example at 300 DPI:
- 3.5 cm × 4.5 cm photo
- Width: (3.5 × 300) / 2.54 = 413 px
- Height: (4.5 × 300) / 2.54 = 531 px
```

The built-in converter does this math for you automatically!

---

## 🌟 Use Cases

### Passport Photos
- Set exact dimensions (e.g., 3.5cm × 4.5cm)
- Convert to pixels using 300 DPI
- Export as JPEG with specific file size

### Government Forms
- Meet strict size requirements (e.g., < 50KB)
- Maintain required DPI (often 200-300)
- Correct format (usually JPEG/JPG)

### Job Applications
- Professional photo compression
- Standard dimensions
- Optimal file size for email

---

## 🚀 Local Development

Want to run it locally or contribute?
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/securecompress.git
cd securecompress

# Open in browser
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Visit: http://localhost:8000
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

**Ideas for contribution:**
- Additional image formats
- Batch processing
- Image cropping tool
- Aspect ratio presets
- More metadata extraction

---

## 📝 License

MIT License - See [LICENSE](LICENSE) file for details.

Free to use, modify, and distribute.

---

## ⭐ Support

If SecureCompress helped you:
- ⭐ Star this repository
- 🐛 Report bugs via Issues
- 💡 Suggest features
- 🔀 Contribute improvements
- 📢 Share with others who need it

---

## 📞 Contact

Have questions or feedback? Open an issue on GitHub!

---

**Made with ❤️ for privacy-conscious users**

*Secure by design. Private by default.*
```

---

## 🎨 Optional: Create a Logo

Simple text-based logo for the HTML header:
```
🔒 SecureCompress
