# README Customization Guide

This guide will help you customize your portfolio README to match your personal information and preferences.

## 🎨 Sections to Customize

### 1. Header & Typing Animation
**Location**: Lines 1-5

Update the typing animation text to match your titles/roles:
```markdown
lines=Full+Stack+Developer;Problem+Solver;Tech+Enthusiast;Always+Learning+New+Things
```

Replace with your own titles separated by semicolons and using `+` for spaces.

### 2. About Me Section
**Location**: Lines 13-22

Update these points to reflect your current status:
- 🔭 **Currently Working On**: Add your current projects
- 🌱 **Learning**: What you're currently learning
- 💡 **Interests**: Your technical interests
- 🎯 **Goals**: Your professional goals
- ⚡ **Fun Fact**: Add a personal touch

### 3. Tech Stack & Skills
**Location**: Lines 25-66

**To add a new badge**:
```markdown
![TechName](https://img.shields.io/badge/-TechName-HEXCOLOR?style=for-the-badge&logo=logoname&logoColor=white)
```

**To remove a badge**: Simply delete the entire line

**Find badge logos**: Visit [shields.io](https://shields.io/) or [Simple Icons](https://simpleicons.org/)

### 4. Featured Projects
**Location**: Lines 103-111

Replace the placeholder projects with your actual projects:
```markdown
| 🚀 **Project Name** | Description of your project | Tech Stack | [![GitHub](link-to-repo)] |
```

### 5. Social Links
**Location**: Lines 117-125

Update these links with your actual profiles:
- LinkedIn: `https://linkedin.com/in/YOUR_USERNAME`
- Twitter: `https://twitter.com/YOUR_USERNAME`
- Email: `mailto:YOUR_EMAIL@example.com`
- Portfolio: `https://YOUR_PORTFOLIO_URL.com`
- Discord: `https://discord.gg/YOUR_SERVER`

**To remove a social link**: Delete the entire badge line

**To add a new social link**:
```markdown
[![Platform](https://img.shields.io/badge/-Platform-COLOR?style=for-the-badge&logo=logoname&logoColor=white)](YOUR_URL)
```

## 🔧 Widget Customizations

### GitHub Stats Theme
Change the theme by replacing `tokyonight` with another theme:
- `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `highcontrast`, `dracula`

### GitHub Stats Languages
To show more or fewer languages, change `langs_count=8` to your desired number.

### Profile Views Badge Color
Change the color by replacing `2e9ef7` with any hex color (without #).

## 📝 Tips

1. **Keep it Updated**: Regularly update your projects and stats
2. **Be Authentic**: Customize the content to truly represent you
3. **Test Locally**: Preview your README before committing
4. **Mobile Friendly**: The design is responsive and works on all devices
5. **Performance**: All widgets are optimized for fast loading

## 🎯 Additional Resources

- [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Shields.io](https://shields.io/) - Create custom badges
- [Simple Icons](https://simpleicons.org/) - Find brand icons
- [GitHub README Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)

## 🚀 Quick Start

1. Clone this repository
2. Edit `README.md` with your information
3. Commit and push your changes
4. Your GitHub profile will automatically update!

---

**Note**: Some external services (like stats widgets) may take a few minutes to generate on first load.
