# Greeting Card

An interactive digital greeting card created with HTML and CSS, now updated with custom portrait media queries for better display on mobile and portrait devices.

## 📋 Description

This project features a birthday greeting card with interactive visual effects and internal navigation:
- Birthday greeting message displayed in a centered card
- Hover effects with scale and background-color transitions
- Decorative emoji accents added via CSS pseudo-elements
- "Send Card" and "Share on Social Media" anchor links
- Hidden action sections that appear when links are selected
- Accessible focused link states and visited link styling

## 🛠️ Technologies Used

- **HTML5**: Semantic structure with anchor links and content sections
- **CSS3**: Styling, hover effects, transitions, pseudo-elements, and responsive media query support

## 🚀 How to View

1. Open `index.html` in your web browser
2. Hover over the card to see the interactive transform and color effects
3. Click the "Send Card" or "Share on Social Media" links to reveal the corresponding section below

## 📁 Files

- `index.html` - Main HTML structure with card content and action sections
- `styles.css` - CSS styling with hover effects, button states, and responsive support

## 🎨 Design Details

- **Background**: `whitesmoke` page background with a white card container
- **Card Width**: `max-width: 400px` for a compact card layout
- **Spacing**: `40px` padding and `50px auto 0` margin for centered spacing
- **Card Styling**: Rounded corners (`10px`), box shadow, and smooth transitions
- **Button Styling**: Midnight blue buttons with hover color change to orangered, focus outline, and visited link color
- **Interactive Sections**: Hidden content panels that appear only when targeted by anchor links
- **Section Effects**: Sections skew on hover for an extra visual effect

## 📱 Responsive Support

- Includes a custom `@media screen and (orientation: portrait)` rule
- Reduces card padding on portrait devices
- Adds `min-width: 160px` to keep the card usable on narrow screens
- Uses a small gap between buttons for better spacing in portrait mode

---

*Part of Practice Projects*