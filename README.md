# Ashok Bhattarai - Portfolio

A modern, responsive portfolio website for Ashok Bhattarai, a passionate Graphic Designer and Motion Graphics specialist.

## 🎨 Features

- **Responsive Design** - Works beautifully on desktop, tablet, and mobile
- **Modern UI** - Sleek dark theme with gold and cyan accents
- **Smooth Animation** - Scroll reveals and interactive cursor effects
- **Fully Customizable** - Easy-to-edit configuration section
- **No Dependencies** - Pure HTML, CSS, and JavaScript

## 📋 Sections

1. **Hero** - Introduction with profile image
2. **Skills** - Adobe Creative Suite proficiencies with progress bars
3. **Portfolio** - Showcase of design and motion graphics work
4. **Experience** - Professional work history
5. **Education** - Certifications and education details
6. **Contact** - Email, phone, location, and citizenship info

## 🛠️ Tech Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Orbitron, Rajdhani, Share Tech Mono)

## 📝 Customization

All content is controlled by a configuration object at the top of `index.html`:

```javascript
const PORTFOLIO_CONFIG = {
  hero: { ... },
  skills: [ ... ],
  portfolioWorks: [ ... ],
  // etc.
}
```

See [CUSTOMIZATION_GUIDE.md](CUSTOMIZATION_GUIDE.md) for detailed instructions.

## 🚀 How to Update Content

### Change Profile Image
```javascript
profileImage: "images/your-image.jpg"
```

### Add Portfolio Project
```javascript
portfolioWorks: [
  {
    id: "work5",
    type: "grid",
    title: "Your Project",
    tag: "CATEGORY",
    image: "images/your-work.jpg",
    description: "Project description"
  }
]
```

### Update Skills
```javascript
skills: [
  { name: "Skill Name", pct: "85%", icon: "●" }
]
```

## 📂 Folder Structure

```
portfolio/
├── index.html                  # Main portfolio file
├── portfolio.html              # Alternative customizable version
├── CUSTOMIZATION_GUIDE.md      # Detailed customization instructions
├── .gitignore
├── README.md
└── images/                     # Portfolio project images
    ├── profile.jpg
    ├── work2.jpg
    └── ...
```

## 🌐 Deployment

This portfolio is hosted on **GitHub Pages** and is automatically live!

**Live URL:** [Visit Portfolio](https://[username].github.io/portfolio-ashok)

### To Deploy Anywhere:
1. Simple HTTP server: `python -m http.server 8000`
2. GitHub Pages: Push to GitHub and enable Pages in settings
3. Netlify, Vercel, or any static hosting

## 📧 Contact

**Ashok Bhattarai**
- Email: 9861ashokbhattarai@gmail.com
- Phone: 9861691769
- Location: Kausaltar 03, Bhaktapur, Nepal
- Citizenship: 29-01-78-04034

## 💼 Skills

- **Premiere Pro** - 85%
- **After Effects** - 88%
- **Illustrator** - 82%
- **InDesign** - 80%
- **Photoshop** - 85%

## 🎓 Education

- **Diploma in IT** - Nepal Banepa Polytechnic Institute (2080)
- **Graphic Designing Certification** - Animax Animation Academy (2024)
- **Post Production & VFX Certification** - Animax Animation Academy (2024)
- **SLC** - Amenity English Secondary School (2076)

## 💪 Experience

- **Freelance Graphic Designer** - Self-Employed (2024 - Present)
- **Motion Graphics Designer** - Mysecondteacher (9 Months, 2024)

## 📄 License

This portfolio is open source and available under the MIT License.

---

**Created:** April 2025  
**Last Updated:** April 5, 2026  
**Status:** Active ✅
