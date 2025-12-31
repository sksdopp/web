# Figma UI/UX Design Guide for Business Portfolio Website

## 📐 Design System Overview

This guide provides comprehensive instructions for designing the business portfolio website in Figma, following modern UI/UX best practices for 2025.

## 🎨 Design Foundations

### Color Palette

```
Primary Colors:
├── Primary Blue: #2563EB
├── Secondary Blue: #1E40AF
└── Accent Orange: #F59E0B

Neutral Colors:
├── Text Dark: #1F2937
├── Text Light: #6B7280
├── Background Light: #F9FAFB
└── White: #FFFFFF

Semantic Colors:
├── Success: #10B981
├── Warning: #F59E0B
├── Error: #EF4444
└── Info: #3B82F6
```

### Typography System

**Primary Font**: Segoe UI (or Inter for modern look)
**Fallback**: Tahoma, Geneva, Verdana, sans-serif

```
Typography Scale:

H1 (Hero): 48px / 700 weight / 1.2 line-height
H2 (Section): 42px / 700 weight / 1.2 line-height
H3 (Card Title): 32px / 700 weight / 1.2 line-height
H4 (Small Title): 24px / 700 weight / 1.3 line-height
Body Large: 18px / 400 weight / 1.6 line-height
Body Regular: 16px / 400 weight / 1.6 line-height
Button Text: 16px / 600 weight / 1.5 line-height
Caption: 14px / 400 weight / 1.5 line-height
```

### Spacing System (8px Grid)

```
spacing-xs: 8px
spacing-sm: 16px
spacing-md: 24px
spacing-lg: 32px
spacing-xl: 48px
spacing-2xl: 64px
spacing-3xl: 80px
```

### Border Radius

```
radius-sm: 8px
radius-md: 12px (primary)
radius-lg: 16px
radius-full: 50% (circles)
```

### Shadows

```
shadow-sm: 0 2px 8px rgba(0,0,0,0.08)
shadow-md: 0 10px 30px rgba(0,0,0,0.1)
shadow-lg: 0 20px 50px rgba(0,0,0,0.15)
```

## 🖼️ Figma Setup Instructions

### 1. Create New Figma File

1. Open Figma and create new file: "Business Portfolio Website"
2. Set up pages:
   - 📱 Mobile Design (375px width)
   - 💻 Desktop Design (1440px width)
   - 🎨 Design System
   - 📦 Components Library

### 2. Design System Page Setup

#### Color Styles
1. Create color styles (right sidebar → Fill → Style icon → +)
   - Name: `Primary/Blue`
   - Name: `Primary/Dark Blue`
   - Name: `Accent/Orange`
   - Name: `Text/Dark`
   - Name: `Text/Light`
   - Name: `Background/Light`

#### Text Styles
1. Create text styles (Text → Style icon → +)
   - `Heading/H1`
   - `Heading/H2`
   - `Heading/H3`
   - `Body/Large`
   - `Body/Regular`
   - `Button/Text`

#### Effect Styles (Shadows)
1. Create effect styles
   - `Shadow/Small`
   - `Shadow/Medium`
   - `Shadow/Large`

### 3. Components Library Setup

Create reusable components:

#### Button Component
```
Variants:
- Primary (filled blue)
- Secondary (outlined white)
- Size: Default (48px height)
- State: Default, Hover, Active

Properties:
- Padding: 14px 32px
- Border-radius: 12px
- Font: 16px/600
```

#### Card Component
```
Base Card:
- Background: White
- Padding: 40px
- Border-radius: 12px
- Shadow: Medium

Variants:
- Service Card
- Team Card
- Portfolio Card
```

#### Icon Container
```
Size: 70px × 70px
Border-radius: 50%
Background: Gradient (Primary to Secondary)
Icon: 32px (Font Awesome or Figma icons)
```

## 📱 Page-by-Page Design Guide

### Page 1: Mobile Design (375px)

#### Frame 1: Mobile Hero Section
```
Dimensions: 375px × 667px

Components:
1. Navigation Bar (top)
   - Logo: "BusinessPro" (24px)
   - Hamburger Menu Icon (right)
   - Height: 60px
   - Background: White
   - Shadow: Small

2. Hero Content
   - Heading: "Transforming Ideas Into Reality"
   - Subheading: 2-3 lines of text
   - 2 Stacked Buttons (full-width minus 40px margin)
   - Floating stat cards (2-3 small cards)

Design Notes:
- Use gradient background (purple to pink)
- White text for contrast
- Cards should float with subtle shadows
```

#### Frame 2: Mobile About Section
```
Layout:
1. Section Header (centered)
   - Title with underline accent
   - Subtitle below

2. Experience Badge (circular)
   - "15+ Years Experience"
   - Centered

3. Text Content
   - Paragraph text
   - 2×2 Stats Grid
   - CTA Button

Spacing: 24px between elements
```

#### Frame 3: Mobile Services
```
Service Cards (vertical stack):
- Icon circle at top
- Title
- Description text
- "Learn More" link

Spacing: 20px between cards
```

#### Frame 4: Mobile Portfolio
```
Filter Buttons (horizontal scroll):
- Pill-shaped buttons
- Active state highlighted

Portfolio Grid:
- Single column
- Image cards
- Overlay on hover (show in second state)
```

#### Frame 5: Mobile Contact
```
Contact Info Cards:
- Icon + Text layout
- Stacked vertically

Form:
- Full-width inputs
- 16px padding
- 12px border-radius
```

### Page 2: Desktop Design (1440px)

#### Frame 1: Desktop Hero (1440px × 800px)
```
Layout (Grid: 2 columns, 60px gap):

Left Column:
- Headline (56px)
- Body text
- Button row (side by side)

Right Column:
- Floating cards animation
- 3 cards in scattered layout
- Use Figma Smart Animate for prototype

Background:
- Gradient fill (135°)
- Purple (#667EEA) to Pink (#764BA2)
```

#### Frame 2: Desktop About (1440px × 600px)
```
Grid: 2 columns

Left: Image placeholder with experience badge
Right: Text + 2×2 Stats Grid

Auto-layout: Use for stats grid (gap: 20px)
```

#### Frame 3: Desktop Services (1440px × 800px)
```
Grid: 3 columns × 2 rows
Gap: 30px between cards

Each Service Card:
- Use component from library
- Hover state with lift effect (prototype)
```

#### Frame 4: Desktop Portfolio (1440px × 900px)
```
Filter Bar (centered):
- 4-5 filter buttons
- Gap: 20px

Portfolio Grid: 3 columns
- Auto-layout with wrap
- Gap: 30px

Prototype:
- Click filter → Show filtered items
- Hover card → Show overlay
```

#### Frame 5: Desktop Team (1440px × 700px)
```
Grid: 4 columns
Team cards with hover states
```

#### Frame 6: Desktop Contact (1440px × 600px)
```
Grid: 2 columns (1fr 1.5fr)

Left: Contact info (4 items)
Right: Contact form (white card)
```

## 🎯 Prototyping Guidelines

### Interactions to Create

1. **Navigation Menu**
   - Desktop: Hover underline animation
   - Mobile: Hamburger menu slide-in

2. **Button Hovers**
   - Scale up slightly (1.05)
   - Color change
   - Shadow increase

3. **Card Hovers**
   - Lift effect (translateY -10px)
   - Shadow increase

4. **Portfolio Filter**
   - Click button → Show/hide items
   - Active state change

5. **Smooth Scroll**
   - Link nav items to sections
   - Use "Scroll to" behavior

### Animation Properties
```
Duration: 300ms
Easing: Ease Out
Smart Animate: Enable between frames
```

## 📐 Layout Grids

### Desktop Grid
```
Type: Column Grid
Count: 12 columns
Margin: 120px (both sides)
Gutter: 24px
Color: Red (10% opacity)
```

### Mobile Grid
```
Type: Column Grid  
Count: 4 columns
Margin: 20px (both sides)
Gutter: 16px
Color: Red (10% opacity)
```

### Baseline Grid
```
Size: 8px
Color: Blue (5% opacity)
```

## 🎨 Design Tips & Best Practices

### Visual Hierarchy
1. Use size to establish importance
2. Use color to create focus points
3. Use spacing to group related items
4. Use contrast for CTAs

### White Space
- Don't be afraid of white space
- Minimum 40px padding for sections
- 20-30px between related elements
- 60-80px between sections

### Consistency
- Use components for repeated elements
- Maintain spacing rhythm (8px grid)
- Consistent border radius throughout
- Uniform icon sizes per section

### Accessibility
- Color contrast ratio: minimum 4.5:1 for text
- Clickable elements: minimum 44×44px
- Clear focus states
- Readable font sizes (16px minimum)

## 🖱️ Interactive States to Design

For each interactive element, create these states:

### Buttons
1. Default
2. Hover (darker, shadow increase)
3. Active (pressed, slight scale down)
4. Disabled (opacity 0.5)

### Form Inputs
1. Default (border: light gray)
2. Focus (border: primary blue)
3. Error (border: red)
4. Success (border: green)

### Cards
1. Default
2. Hover (elevated)
3. Active/Selected

## 📱 Responsive Design Approach

### Breakpoint Frames to Create
```
Mobile: 375px (iPhone X)
Tablet: 768px (iPad Portrait)
Desktop: 1440px (Standard Desktop)
Large Desktop: 1920px (Optional)
```

### Content Adaptation Rules

**Desktop → Mobile:**
- 2-3 columns → 1 column
- Side-by-side → Stacked
- Horizontal nav → Hamburger menu
- Larger text → Slightly smaller
- More padding → Less padding

## 🎭 Figma Plugins to Use

1. **Unsplash** - For placeholder images
2. **Iconify** - For icons (alternative to Font Awesome)
3. **Content Reel** - For dummy text and data
4. **Stark** - For accessibility checking
5. **Autoflow** - For flowcharts (optional)

## 📋 Design Checklist

Before finalizing:

- [ ] All text uses text styles
- [ ] All colors use color styles
- [ ] Components used for repeated elements
- [ ] Proper naming conventions
- [ ] Organized layers and frames
- [ ] Grid overlays set up
- [ ] Responsive designs created
- [ ] Interactive prototype connected
- [ ] Accessibility contrast checked
- [ ] Design handed off to development

## 🔄 Design-to-Development Workflow

### Handoff Process

1. **Organize Figma File**
   - Clean up unused layers
   - Name everything clearly
   - Group related elements

2. **Add Annotations**
   - Note animations
   - Explain interactions
   - Specify responsive behavior

3. **Export Assets**
   - Icons: SVG format
   - Images: PNG or JPEG (optimized)
   - Logo: SVG and PNG

4. **Use Dev Mode**
   - Enable Figma Dev Mode
   - Developers can inspect CSS
   - Copy exact values

## 🎓 Learning Resources for Figma

1. **Figma Official Tutorials**
   - figma.com/resources/learn-design/

2. **Component Best Practices**
   - Use Auto-layout
   - Create variants
   - Proper naming

3. **Design System Setup**
   - Start with foundations
   - Build component library
   - Document usage

## 🚀 Advanced Techniques

### Auto-Layout Magic
- Use for responsive components
- Set constraints (hug/fill/fixed)
- Proper spacing values

### Variables (New Feature)
- Use for colors
- Use for spacing
- Create modes (light/dark)

### Component Properties
- Boolean (show/hide elements)
- Instance swap (change icons)
- Text properties

## 📊 Project Timeline

Estimated time to complete design:

```
Setup & Research: 1-2 hours
Design System: 2-3 hours
Mobile Designs: 4-5 hours
Desktop Designs: 5-6 hours
Prototyping: 2-3 hours
Refinement: 2-3 hours

Total: 16-22 hours
```

---

## 🎯 Final Deliverables

When design is complete, you should have:

1. ✅ Complete design system
2. ✅ Component library
3. ✅ Mobile responsive design (5-6 screens)
4. ✅ Desktop design (6-7 sections)
5. ✅ Interactive prototype
6. ✅ Exported assets
7. ✅ Developer handoff notes

## 💡 Pro Tips

1. **Start with wireframes** - Low fidelity first
2. **Design mobile first** - Then scale up
3. **Use real content** - Avoid lorem ipsum when possible
4. **Test your prototype** - Get feedback early
5. **Keep it simple** - Don't over-design
6. **Stay consistent** - Use your design system
7. **Think accessibility** - From the start

---

**Happy Designing! 🎨**

This design system ensures consistency, scalability, and professional quality across all screens.
