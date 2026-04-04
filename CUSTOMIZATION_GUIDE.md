# Portfolio Customization Guide

Your portfolio is now **100% customizable**! All content is controlled by a configuration object at the top of the HTML file.

## 📝 How to Edit Content

Open `portfolio.html` in any text editor and look for the **CONFIGURATION SECTION** (starts around line 220).

### 🖼️ How to Change Images

**Profile Image:**
```javascript
profileImage: "images/profile.jpg" // Change to any image in your images folder
```

**Portfolio Work Images:**
```javascript
portfolioWorks: [
  {
    image: "images/work2.jpg", // ← Change this path
  },
  {
    image: "images/work3.jpg", // ← Change this path
  }
]
```

**To add a new image:**
1. Save your image in the `images/` folder
2. Change the path in the config to: `"images/your-image.jpg"`

---

## ➕ How to Add New Work/Projects

In the `portfolioWorks` array, add a new object:

```javascript
{
  id: "work5",
  type: "grid", // or "featured" for large projects
  title: "Your Project Title",
  tag: "PROJECT CATEGORY",
  image: "images/your-image.jpg",
  description: "Brief description of the project",
  tools: ["TOOL1", "TOOL2"]
}
```

**For Featured Projects** (large layout):
```javascript
{
  id: "work6",
  type: "featured",
  title: "Big Project",
  tag: "BRANDING",
  image: "images/big-project.jpg",
  description: "Description here",
  tools: ["FIGMA", "PHOTOSHOP"],
  reverse: true // or false - this reverses left/right layout
}
```

---

## 👤 How to Change Personal Information

### Hero Section:
```javascript
hero: {
  firstName: "Ashok",
  lastName: "Bhattarai",
  title: "Visual Creator",
  tag: "Graphic Designer · Motion Graphics",
  bio: "Your bio text here...",
  buttonPrimaryText: "View My Work",
  buttonSecondaryText: "Get In Touch"
}
```

### Contact Information:
```javascript
contact: [
  { icon: "📧", label: "Email", value: "your-email@example.com" },
  { icon: "📱", label: "Phone", value: "+1 234 567 8900" },
  // Add more contact info as needed
]
```

---

## 🎯 How to Add/Edit Skills

```javascript
skills: [
  { name: "Figma", pct: "95%", icon: "●" },
  { name: "Photoshop", pct: "90%", icon: "★" },
  // Add more skills
]
```

**Change the icon:** Use any Unicode symbol: ●, ◆, ★, ▲, ◈, ◎, etc.

---

## 💼 How to Add/Edit Experience

```javascript
experience: [
  {
    role: "Senior Designer",
    company: "Company Name",
    duration: "2022 - Present"
  },
  // Add more experiences
]
```

---

## 🎓 How to Add/Edit Education

```javascript
education: [
  {
    year: "2020",
    degree: "Degree Name",
    school: "School Name"
  },
  // Add more education entries
]
```

---

## 📊 How to Change Statistics

```javascript
stats: [
  { number: "50+", label: "Projects" },
  { number: "10+", label: "Years" },
  { number: "100%", label: "Satisfaction" }
]
```

---

## 🎨 Advanced: Changing Colors

Open the `<style>` section and modify the CSS variables:

```css
:root {
  --bg: #030610;           /* Background color */
  --panel: #080f1f;        /* Card background */
  --gold: #f5c842;         /* Primary accent color */
  --gold2: #e0a500;        /* Hover gold */
  --cyan: #00e5ff;         /* Secondary accent */
  --text: #c8d8f0;         /* Text color */
  --dim: #4a5a78;          /* Dim text */
}
```

---

## 📁 Folder Structure

```
your-portfolio-folder/
├── portfolio.html              ← Main file (open this in browser)
├── CUSTOMIZATION_GUIDE.md      ← This file
└── images/                     ← Add all your images here
    ├── profile.jpg
    ├── work2.jpg
    ├── work3.jpg
    ├── work4.jpg
    └── work5.jpg
```

---

## 🚀 Quick Tips

1. **Save & Reload:** After editing the config, save and refresh your browser (Cmd+R on Mac, Ctrl+R on Windows)

2. **Adding Images:** 
   - Keep images in the `images/` folder
   - Use image format: `images/filename.jpg` or `images/filename.png`

3. **Adding New Sections:** 
   - Add to arrays in the config
   - JavaScript will automatically render them

4. **Customizing Styles:**
   - Most styling is in the `<style>` section
   - Change fonts, sizes, spacing as needed

5. **Test Everything:** 
   - Open in browser after changes
   - Check mobile view (Responsive Design)

---

## ✅ Checklist for Full Customization

- [ ] Change profile image in `hero.profileImage`
- [ ] Update personal name and title
- [ ] Add/update portfolio work items with images
- [ ] Update contact information
- [ ] Add your skills
- [ ] Add your experience and education
- [ ] Customize colors via CSS variables
- [ ] Change footer text

---

## 💡 Need Help?

- All content is in the `PORTFOLIO_CONFIG` object
- Search for `// ← CHANGE` comments to find editable items
- Images must be in the `images/` folder
- Use Firefox/Chrome DevTools (F12) to inspect and debug

**Happy customizing!** 🎨
