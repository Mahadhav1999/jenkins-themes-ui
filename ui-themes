# 🎨 Jenkins UI Theme Customization Guide

Transform your Jenkins login page with custom themes and branding for a professional, personalized experience.

## 📋 Prerequisites

- Jenkins instance with administrative access
- Internet connection for plugin installation

## 🚀 Installation Steps

### Step 1: Access Plugin Management
Navigate to **Manage Jenkins** → **System Configuration** → **Plugins**

### Step 2: Install Login Theme Plugin
1. Go to **Available Plugins** tab
2. Search for **"Login Theme Plugin"**
3. Select the plugin and click **Install**
4. Wait for installation to complete and restart Jenkins if prompted

### Step 3: Configure Theme Settings
After installation, navigate to **Manage Jenkins** → **Appearance** → **Login Page Theme**

## 🎨 Customization Options

### Head Section Styling
Paste the following CSS code in the **Head Section**:

```css
<style>
.simple-page .logo {
    background-image: url('https://www.jenkins.io/images/logos/india/india.png');
    background-repeat: no-repeat;
    background-position: 50% 0;
    height: 350px;
    background-size: contain;
}

.simple-page form {
    width: unset;
    max-width: unset;
}
</style>
```

> 💡 **Tip**: Replace the logo URL with your preferred image from [Jenkins Artwork](https://www.jenkins.io/artwork)

### Header Customization
Add personalized welcome text in the **Header Section**:

```html
<script>
document.getElementsByTagName('h1')[0].textContent = 'Welcome to Your Jenkins Dashboard!';
</script>
```

> ✏️ **Customize**: Replace "Your" with your name or organization

### Footer Content
Enhance the footer in the **Footer Section**:

```html
<div style="text-align:center;">
    <p>Please login using your company credentials</p>
</div>
```

### Branding Image
Set your branding image URL:
```
https://www.jenkins.io/images/logos/india/india.png
```

## 🎭 Advanced Styling

### Custom Background Gradient
For a modern look, add this CSS for gradient backgrounds:

```css
position: absolute;
inset: 0;
z-index: 1;
background: linear-gradient(
    135deg,
    rgb(69, 123, 157) 10%,
    rgb(188, 187, 206) 30%,
    rgb(235, 176, 163) 50%,
    rgb(244, 213, 177) 70%,
    rgb(139, 185, 198) 90%,
    rgb(44, 113, 149) 110%
);
```

### Custom Header Logo
To replace the Jenkins head icon:

1. Go to **Manage Jenkins** → **Appearance** → **Simple Theme Plugin**
2. Click **Add** → Select **Extra CSS**
3. Paste the following code:

```css
#jenkins-head-icon {
    content: url("YOUR_LOGO_URL_HERE");
    height: 40px;
    width: auto;
}
```

> 🔗 **Replace**: Update `YOUR_LOGO_URL_HERE` with your actual logo URL

## 🎯 Best Practices

- **Image Optimization**: Use optimized images for faster loading
- **Consistent Branding**: Maintain brand colors and fonts throughout
- **Responsive Design**: Test themes on different screen sizes
- **Backup**: Always backup your Jenkins configuration before major changes

## 🛠️ Troubleshooting

### Common Issues
- **Plugin not showing**: Restart Jenkins after plugin installation
- **Images not loading**: Verify image URLs are accessible
- **Styling not applied**: Clear browser cache and refresh

### Resources
- [Jenkins Artwork Repository](https://www.jenkins.io/artwork)
- [Login Theme Plugin Documentation](https://plugins.jenkins.io/login-theme/)

## 📸 Example Result

After applying these customizations, your Jenkins login page will feature:
- ✅ Custom logo and branding
- ✅ Personalized welcome message
- ✅ Professional gradient background
- ✅ Custom footer content

---

**Made with ❤️ for the Jenkins community**

> 📝 **Note**: Always test customizations in a development environment before applying to production instances.
