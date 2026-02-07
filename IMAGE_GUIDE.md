# Image Optimization & Sourcing Guide

## Current Image Status

### ✅ Current Images in Project
- **Logo**: `IMG_4682.jpeg` (76KB) - Currently in use
- **Team Photos**:
  - `Ashleigh clear.svg` (8.4MB) - ⚠️ Needs optimization
  - `Charli clear.svg` (6.4MB) - ⚠️ Needs optimization
  - `Ashleigh CnA.webp` (1.07MB)
  - `Charlie CnA.webp` (649KB)

### ⚠️ Images Needed
You need **4 service photos** for:
1. In Home Support (household/cleaning scene)
2. Daily Living Assistance (shopping/transport scene)
3. Family & Carer Support (family interaction)
4. Companionship (social interaction scene)

---

## 📦 Image Optimization Guide

### Current Issues:
- SVG files are **8.4MB and 6.4MB** - Too large for web!
- These need to be converted to optimized formats

### Option 1: Use Existing WebP Files (RECOMMENDED)
The `.webp` files are already optimized:
- Ashleigh CnA.webp: 1.07MB (acceptable)
- Charlie CnA.webp: 649KB (good size)

**Action**: Update HTML to use these instead of SVG files.

### Option 2: Optimize SVG Files
If you want to keep using SVGs:

1. **Online Tools** (Easiest):
   - https://jakearchibald.github.io/svgomg/
   - Upload your SVG
   - Click "Download" to get optimized version
   - Should reduce size by 50-80%

2. **Command Line** (If you have Node.js):
   ```bash
   npm install -g svgo
   cd "Website images"
   svgo "Ashleigh clear.svg" -o "Ashleigh-optimized.svg"
   svgo "Charli clear.svg" -o "Charli-optimized.svg"
   ```

### Option 3: Convert to WebP (Best for Photos)
Using online converters:
- https://cloudconvert.com/svg-to-webp
- https://convertio.co/svg-webp/

Target size: **Under 200KB per image** for web use

---

## 🖼️ Finding Service Photos

### Best Free Stock Photo Sites

#### 1. **Unsplash** (https://unsplash.com/)
- Completely free, no attribution required
- High quality professional photos
- Search terms to try:
  - "elderly care"
  - "home help"
  - "senior companionship"
  - "caregiver"
  - "home assistance"

#### 2. **Pexels** (https://www.pexels.com/)
- Free, no attribution required
- Good for authentic care scenes
- Search terms:
  - "elderly support"
  - "home care"
  - "senior help"
  - "companionship"

#### 3. **Pixabay** (https://pixabay.com/)
- Free images and photos
- Good selection of care-related images
- Search: "elderly care", "home support"

#### 4. **Burst by Shopify** (https://burst.shopify.com/)
- Free high-resolution photos
- Good for professional services
- Search: "healthcare", "support services"

### Specific Photo Recommendations

#### For "In Home Support"
Search for:
- Clean, bright home interior
- Kitchen with food preparation
- Tidy living space
- Laundry or organization scenes

**Good examples**:
- Kitchen counter with fresh ingredients
- Organized pantry or cupboard
- Clean, welcoming home environment

#### For "Daily Living Assistance"
Search for:
- Shopping bags/groceries
- Car or transport
- Community settings
- Outdoor activities

**Good examples**:
- Grocery shopping scene
- Walking in community
- Coffee shop or social setting

#### For "Family & Carer Support"
Search for:
- Family conversation
- Multigenerational interaction
- Comfortable home setting
- Support and connection

**Good examples**:
- Family sitting together
- Conversation over coffee
- Supportive hand holding

#### For "Companionship & Social Support"
Search for:
- Two people talking
- Coffee/tea together
- Board games or activities
- Smiling older adults

**Good examples**:
- Friends having tea
- Conversation in garden
- Shared activity or hobby

---

## 🎨 Photo Selection Guidelines

### ✅ DO Look For:
- **Natural, authentic moments** (not overly posed)
- **Warm, welcoming environments**
- **Clear, well-lit images**
- **Diverse representation** (different ages, backgrounds)
- **Australian/Western feel** (if possible)
- **Resolution: At least 1920x1080px**

### ❌ AVOID:
- Overly clinical/medical settings
- Stock photo "fake smile" look
- Dark or poorly lit images
- Watermarked images
- Images with visible branding
- Too "perfect" or staged scenes

---

## 📐 Image Specifications for Website

### Recommended Sizes:
- **Logo**: 150x150px (current is fine)
- **Team Photos**: 800x1200px (portrait orientation)
- **Service Cards**: 800x600px (landscape orientation)

### File Formats:
- **Best**: WebP (smallest file size, modern browsers)
- **Fallback**: JPEG (85% quality, widely supported)
- **Avoid**: PNG for photos (too large)
- **SVG**: Only for logos/icons (and must be optimized)

### Target File Sizes:
- Logo: Under 50KB
- Team Photos: 150-300KB each
- Service Photos: 100-200KB each

---

## 🛠️ Quick Optimization Tools

### Online (No Installation):
1. **TinyPNG** (https://tinypng.com/)
   - Drag and drop images
   - Automatically optimizes
   - Can reduce size by 70%

2. **Squoosh** (https://squoosh.app/)
   - Google's image optimizer
   - Convert to WebP
   - Compare before/after

3. **CloudConvert** (https://cloudconvert.com/)
   - Convert any format
   - Batch processing
   - Quality control

### Desktop Apps:
- **XnConvert** (Free, Windows/Mac/Linux)
- **GIMP** (Free, open source)
- **Adobe Photoshop** (If you have it)

---

## 📋 Action Plan

### Immediate Steps:

1. **Switch to WebP files** (already in your folder):
   ```
   Use: Ashleigh CnA.webp instead of Ashleigh clear.svg
   Use: Charlie CnA.webp instead of Charli clear.svg
   ```

2. **Optimize logo** using TinyPNG:
   - Upload IMG_4682.jpeg
   - Download optimized version
   - Should reduce from 76KB to ~30KB

3. **Find 4 service photos**:
   - Visit Unsplash or Pexels
   - Download 4 photos (one for each service)
   - Name them:
     - `service-home-support.jpg`
     - `service-daily-living.jpg`
     - `service-family-support.jpg`
     - `service-companionship.jpg`

4. **Optimize new photos**:
   - Use TinyPNG or Squoosh
   - Convert to WebP if possible
   - Target: Under 200KB each

5. **Update HTML files**:
   - Replace image paths with new optimized images
   - Test on local server

---

## 🌐 SEO & Accessibility

### Image Alt Text (Already in HTML):
- Descriptive and specific
- Helps with SEO
- Essential for screen readers

### Image Names:
Use descriptive filenames:
- ✅ `elderly-care-companionship.webp`
- ❌ `IMG_12345.jpg`

---

## Need Help?

If you need assistance with:
- Converting images
- Optimizing files
- Updating HTML with new images

Just let me know and I can guide you through it!

---

**Last Updated**: February 7, 2026
