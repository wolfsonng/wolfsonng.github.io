# Aerospace Executive Portfolio

A professional personal website for aerospace MRO executives that uses **Markdown files for easy content editing** - just like Jekyll themes! This works directly with GitHub Pages with no build process required.

## Quick Setup

1. **Fork or download this repository**
2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

Your site will be live at: `https://yourusername.github.io/repository-name`

## Easy Content Editing with Markdown

Just like Jekyll themes, you can edit your content using simple Markdown files:

### 📝 Edit Your Profile (`profile.md`)
```markdown
# Your Name
**Your Job Title**  
*Your Location • Years Experience*

Your professional summary paragraph here...

## Core Expertise
- Your expertise area 1
- Your expertise area 2
- etc...

## Key Achievements  
- Your achievement 1
- Your achievement 2
- etc...
```

### 📅 Update Your Career (`career.md`)
```markdown
# Career Timeline

## 2020 - Present
**Your Current Job Title**  
*Company Name*

Description of your current role and achievements...

## 2015 - 2020
**Previous Job Title**  
*Previous Company*

Description of this role...
```

### 📞 Update Contact Info (`contact.md`)
```markdown
# Contact Information

**Email:** your-email@email.com  
**LinkedIn:** [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  
**Location:** Your City, State

Your availability message here...
```

## Adding Your Profile Photo

Edit `index.html` and find this line (around line 22):
```html
<img src="https://images.pexels.com/photos/2182970/pexels-photo-2182970.jpeg?auto=compress&cs=tinysrgb&w=400&h=400&fit=crop" alt="Professional Profile">
```

Replace with:
1. **Upload your photo to the repository** (e.g., `profile.jpg`) and use: `<img src="profile.jpg" alt="Professional Profile">`
2. **Or use another stock photo URL**

## Features

- ✅ **Edit content in Markdown** - just like Jekyll themes!
- ✅ **No build process** - works directly with GitHub Pages
- ✅ **Fully responsive** - looks great on all devices
- ✅ **Professional design** - appropriate for executive-level presentation
- ✅ **Timeline layout** - showcases career progression clearly
- ✅ **SEO optimized** - includes proper meta tags
- ✅ **Fast loading** - simple HTML/CSS with JavaScript for markdown parsing

## File Structure

```
├── index.html          # Main page (rarely needs editing)
├── styles.css          # Styling (rarely needs editing)
├── profile.md          # ← Edit your profile info here
├── career.md           # ← Edit your career timeline here
├── contact.md          # ← Edit your contact info here
└── README.md          # This file
```

## How It Works

The site uses JavaScript to automatically load and display your Markdown files:
- `profile.md` → Hero section and About section
- `career.md` → Career timeline
- `contact.md` → Contact section

Just edit the `.md` files and push to GitHub - your changes appear immediately!

## Deployment

Simply push your changes to GitHub. The site will automatically update within a few minutes.

## Support

This system gives you the same easy editing experience as Jekyll themes, but with a completely custom design. Just edit the Markdown files to update your content and push to GitHub - no technical knowledge required!