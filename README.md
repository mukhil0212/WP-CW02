# CW-02 CSS Positioning Exercise

## Overview
This exercise demonstrates various CSS layout techniques including:
- Page sections and semantic HTML
- Flexbox layouts
- Float and clear properties  
- Fixed positioning
- Responsive design

## Requirements Implemented

### ✅ HTML Structure
- Wrapped h1 and h2 in `<header>` element
- Created `<main>` container for content area
- Used `<aside>` for left column
- Used `<section>` for right column
- Added appropriate classes and IDs

### ✅ CSS Layout Features

**1. Header Centering**
- Centered h1 and h2 using `text-align: center`

**2. Main Content Area**
- 70% width and centered with `margin: 0 auto`
- Flexbox container with `display: flex`

**3. Column Layout**
- Left column (aside): `flex-basis: 33%`
- Right column (section): `flex-basis: 67%`
- Shared class for styling both columns

**4. Float and Clear**
- Puppy image floated right with `float: right`
- Image width set to 200px
- Specific paragraph uses `clear: both`

**5. Box Model**
- Both columns have 2em padding, 2em margin
- 4px dashed red border on both columns

**6. Fixed Positioning**
- Bottom paragraph positioned 5px from viewport bottom
- Uses `position: fixed`

### ✅ Additional Features
- Responsive design for mobile devices
- Hover effects and transitions
- Professional styling and typography
- Semantic HTML structure

## Files
- `index.html` - Main HTML file with layout structure
- `styles.css` - Complete CSS implementation
- `puppy-mowgli.jpg` - Puppy image file for floating demonstration

## Image File
✅ **Image included:** `puppy-mowgli.jpg` - Puppy image for floating demonstration

## Browser Testing
- Tested responsive behavior
- Flexbox compatibility
- Float and clear functionality
- Fixed positioning across different screen sizes

## Key CSS Techniques Demonstrated
1. **Flexbox**: Container and item properties
2. **Float**: Image positioning with text wrap
3. **Clear**: Breaking float behavior
4. **Fixed Position**: Viewport-relative positioning
5. **Box Model**: Padding, margin, border combination
6. **Responsive Design**: Media queries for mobile