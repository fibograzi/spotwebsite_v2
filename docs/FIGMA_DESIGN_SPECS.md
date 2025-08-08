# 🎨 APEX Athletic - Figma Design Specifications

## Overview
This document provides detailed specifications for creating the APEX Athletic website design in Figma.

## 🎯 Design System

### Color Palette

#### Primary Colors
- **Electric Blue**: #0066FF
  - Use for: CTAs, links, primary actions
  - RGB: 0, 102, 255
  
- **Deep Black**: #000000
  - Use for: Backgrounds, high contrast text
  - RGB: 0, 0, 0

#### Secondary Colors
- **Success Green**: #00CC66
  - Use for: Success states, eco-friendly elements
  - RGB: 0, 204, 102

#### Neutral Colors
- **Gray 100**: #F8F9FA (Background)
- **Gray 200**: #E9ECEF (Borders light)
- **Gray 300**: #DEE2E6 (Disabled)
- **Gray 400**: #CED4DA (Placeholder)
- **Gray 500**: #ADB5BD (Muted text)
- **Gray 600**: #6C757D (Body text)
- **Gray 700**: #495057 (Headings)
- **Gray 800**: #343A40 (Dark text)
- **Gray 900**: #212529 (Darkest text)

### Typography

#### Font Family
- **Primary**: Inter
- **Fallback**: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif

#### Font Weights
- Light: 300
- Regular: 400
- Medium: 500
- Semibold: 600
- Bold: 700
- Black: 900

#### Type Scale
- **Hero Title**: 96px / Line-height: 1 / Weight: 900
- **H1**: 48px / Line-height: 1.2 / Weight: 700
- **H2**: 36px / Line-height: 1.3 / Weight: 700
- **H3**: 24px / Line-height: 1.4 / Weight: 600
- **H4**: 20px / Line-height: 1.4 / Weight: 600
- **Body Large**: 18px / Line-height: 1.6 / Weight: 400
- **Body**: 16px / Line-height: 1.5 / Weight: 400
- **Body Small**: 14px / Line-height: 1.5 / Weight: 400
- **Caption**: 12px / Line-height: 1.4 / Weight: 400

### Spacing System (8px Grid)
- **xs**: 4px
- **sm**: 8px
- **md**: 16px
- **lg**: 24px
- **xl**: 32px
- **2xl**: 48px
- **3xl**: 64px
- **4xl**: 96px
- **5xl**: 128px

### Border Radius
- **sm**: 4px
- **md**: 8px
- **lg**: 16px
- **xl**: 24px

### Shadows
- **sm**: 0 1px 2px rgba(0, 0, 0, 0.05)
- **md**: 0 4px 6px -1px rgba(0, 0, 0, 0.1)
- **lg**: 0 10px 15px -3px rgba(0, 0, 0, 0.1)
- **xl**: 0 20px 25px -5px rgba(0, 0, 0, 0.1)

## 📐 Layout Grid

### Desktop (1440px)
- **Columns**: 12
- **Margin**: 80px
- **Gutter**: 32px
- **Max Container**: 1200px

### Tablet (768px)
- **Columns**: 8
- **Margin**: 40px
- **Gutter**: 24px

### Mobile (375px)
- **Columns**: 4
- **Margin**: 16px
- **Gutter**: 16px

## 🧩 Components

### Navigation Bar
- **Height**: 80px (desktop), 60px (mobile)
- **Background**: rgba(0, 0, 0, 0.95) with backdrop blur
- **Logo**: 40x40px
- **Nav Links**: 16px Medium
- **CTA Button**: Primary button style

### Buttons
#### Primary Button
- **Padding**: 16px 32px
- **Background**: #0066FF
- **Text**: White, 14px, Semibold, Uppercase
- **Border Radius**: 8px
- **Hover**: Background #0052CC, translateY(-2px)

#### Secondary Button
- **Padding**: 16px 32px
- **Background**: Transparent
- **Border**: 2px solid white
- **Text**: White, 14px, Semibold, Uppercase
- **Hover**: Background white, text black

### Cards
#### Product Card
- **Width**: Min 350px
- **Border Radius**: 16px
- **Image Height**: 300px
- **Padding**: 32px
- **Shadow**: lg on hover

#### Athlete Card
- **Width**: Min 300px
- **Image**: Grayscale by default, color on hover
- **Quote**: Italic with large quotation mark

### Form Elements
- **Input Height**: 48px
- **Border**: 2px solid #DEE2E6
- **Border Radius**: 8px
- **Padding**: 16px
- **Focus**: Border color #0066FF

## 🎬 Animations & Interactions

### Scroll Animations
- **Fade In Up**: Opacity 0 → 1, translateY(50px) → 0
- **Scale**: Scale 0.8 → 1
- **Stagger**: 0.1s delay between elements

### Hover States
- **Links**: Underline animation
- **Cards**: Lift effect (translateY -8px)
- **Images**: Scale 1.1
- **Buttons**: Color shift + shadow

### Loading
- **Logo**: Pulse animation
- **Progress Bar**: Linear animation

## 📱 Responsive Breakpoints
- **Desktop**: 1024px and up
- **Tablet**: 768px to 1023px
- **Mobile**: Below 768px

## 🖼️ Image Specifications

### Hero Section
- **Video/Image**: 1920x1080px minimum
- **Overlay**: Gradient rgba(0,0,0,0.8) to rgba(0,102,255,0.3)

### Product Images
- **Size**: 800x800px
- **Format**: JPG/PNG
- **Background**: Clean, minimal

### Athlete Portraits
- **Size**: 600x800px
- **Style**: Professional, action shots
- **Treatment**: B&W with color on hover

## 📋 Figma Structure

### Pages
1. **Cover** - Project overview
2. **Style Guide** - Colors, typography, components
3. **Desktop** - All desktop screens
4. **Tablet** - Tablet responsive layouts
5. **Mobile** - Mobile responsive layouts
6. **Components** - Master components
7. **Prototype** - Interactive prototype

### Naming Convention
- **Frames**: Section/Subsection/State
- **Components**: Component/Variant/State
- **Colors**: Color/Shade
- **Text Styles**: Category/Size/Weight

## 🔗 Prototype Links
- Hero → Products (smooth scroll)
- Navigation → Sections (anchor links)
- Product cards → Hover states
- Form → Success state

## 💡 Design Tips
1. Use Auto Layout for responsive components
2. Create color and text styles for consistency
3. Use components for repeated elements
4. Set up responsive constraints
5. Export assets at 2x for retina displays

---

**Note**: This design system ensures consistency between the Figma design and the coded website. All specifications match the CSS variables used in development.