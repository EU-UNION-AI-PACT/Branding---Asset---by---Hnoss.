# Typography and Fonts

This directory contains official Hnoss brand typography resources and font files.

## Primary Typeface

### Inter

**Usage**: Primary typeface for all digital applications

**Weights Available:**
- **Bold** (700): Headings, emphasis
- **Medium** (500): Subheadings, UI elements
- **Regular** (400): Body text, general content

**Why Inter?**
- Excellent screen readability
- Wide character support
- Open source and free
- Optimized for UI design

**Download**: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

## Secondary Typeface

### Roboto

**Usage**: Alternative and fallback typeface

**Weights Available:**
- **Bold** (700): Headings
- **Regular** (400): Body text
- **Light** (300): Captions, metadata

**Why Roboto?**
- Excellent fallback option
- Universal compatibility
- Professional appearance
- Widely supported

**Download**: [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto)

## Typography Scale

### Digital Scale

```
Heading 1 (H1): 48px / 3rem      | Inter Bold
Heading 2 (H2): 36px / 2.25rem   | Inter Bold
Heading 3 (H3): 28px / 1.75rem   | Inter Medium
Heading 4 (H4): 24px / 1.5rem    | Inter Medium
Body Large:     18px / 1.125rem  | Inter Regular
Body:           16px / 1rem      | Inter Regular
Small:          14px / 0.875rem  | Inter Regular
Caption:        12px / 0.75rem   | Inter Regular
```

### Print Scale

```
Heading 1: 36pt    | Inter Bold
Heading 2: 24pt    | Inter Bold
Heading 3: 18pt    | Inter Medium
Heading 4: 14pt    | Inter Medium
Body:      11pt    | Inter Regular
Caption:   9pt     | Inter Regular
```

## Line Height

- **Headings**: 1.2 (tight)
- **Body Text**: 1.5 (comfortable reading)
- **Captions**: 1.4

## Letter Spacing

- **Headings**: -0.02em (slightly tighter)
- **Body**: 0 (default)
- **All Caps**: 0.05em (slightly wider)

## Font Files

### Available Formats

- **WOFF2**: Modern web format (preferred)
- **WOFF**: Web format fallback
- **TTF/OTF**: Desktop installation
- **Variable Fonts**: For advanced implementations

### Web Font Implementation

```css
/* Example CSS */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap');

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
  font-size: 16px;
  line-height: 1.5;
}

h1, h2, h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
}
```

## Typography Guidelines

### Do's
✓ Use consistent hierarchy
✓ Maintain adequate line spacing
✓ Ensure sufficient contrast
✓ Keep line length readable (45-75 characters)
✓ Use web-safe fallback fonts

### Don'ts
✗ Don't use more than 2-3 font weights
✗ Don't use decorative fonts for body text
✗ Don't sacrifice readability for style
✗ Don't use all caps for long text blocks
✗ Don't use fonts outside the brand system

## Accessibility

All typography choices are made with accessibility in mind:
- Minimum 16px for body text
- 4.5:1 contrast ratio for normal text
- 3:1 contrast ratio for large text (18px+ or 14px+ bold)
- Scalable for different screen sizes
- Clear distinction between heading levels

## Installation

### For Designers

1. Download font files from Google Fonts
2. Install TTF/OTF files on your system
3. Restart design applications
4. Fonts available in font menu

### For Developers

Use Google Fonts CDN or self-host:

```html
<!-- Google Fonts CDN -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
```

---

For complete typography guidelines, see [Brand Guidelines](../guidelines/BRAND_GUIDELINES.md#typography).
