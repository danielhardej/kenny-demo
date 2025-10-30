# GitHub Pages Setup Instructions

This repository now contains a GitHub Pages site ready to be published!

## How to Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/danielhardej/kenny-demo`
2. Click on **Settings** (tab near the top)
3. Scroll down to the **Pages** section in the left sidebar
4. Under "Source", select the branch: `copilot/create-github-pages-site` (or merge to `main` and select `main`)
5. Keep the folder as `/ (root)`
6. Click **Save**

Your site will be published at: `https://danielhardej.github.io/kenny-demo/`

## What's Included

- **index.html**: The main home page with:
  - Beautiful gradient header
  - Introduction section
  - Custom content embed section (with ID `customContentArea`)
  - Usage guide with code examples
  
- **styles.css**: Professional styling with:
  - Modern purple-to-pink gradient header
  - Responsive design for all screen sizes
  - Smooth animations
  - Clean card-based layout

## Using the Custom Embed Section

The page includes a dedicated section for embedding custom HTML/CSS. You can use it in several ways:

### Method 1: Direct HTML Editing
Edit `index.html` and replace the content inside:
```html
<div class="custom-content-area" id="customContentArea">
    <!-- Your custom HTML here -->
</div>
```

### Method 2: JavaScript Loading
Add a script tag to dynamically load content:
```javascript
document.getElementById('customContentArea').innerHTML = 
    '<div>Your custom HTML here</div>';
```

### Method 3: External Content
Load content from another source using JavaScript fetch or iframe.

## Customization

Feel free to customize:
- Colors in `styles.css` (search for `#667eea` and `#764ba2` for the gradient colors)
- Site title and tagline in `index.html`
- Add more sections or pages as needed

Enjoy your new GitHub Pages site! 🎉
