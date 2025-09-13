# AutoSense Diagnostics Web App - Design Guidelines

## Design Approach: Reference-Based (Automotive/Professional Tools)
Drawing inspiration from professional diagnostic tools like OBD Fusion, Torque Pro, and enterprise automotive platforms. Focus on data clarity, technical precision, and professional credibility.

## Core Design Elements

### Color Palette
**Primary Colors:**
- Deep Blue: 220 85% 25% (professional automotive industry standard)
- Steel Blue: 215 60% 45% (secondary actions, borders)

**Dark Mode:**
- Background: 220 15% 8%
- Surface: 220 12% 12%
- Text: 0 0% 95%

**Light Mode:**
- Background: 0 0% 98%
- Surface: 0 0% 100%
- Text: 220 15% 15%

**Accent Colors:**
- Success Green: 120 60% 45% (healthy diagnostics)
- Warning Orange: 35 85% 55% (maintenance alerts)
- Error Red: 0 75% 50% (critical issues)

### Typography
- **Primary Font:** Inter (via Google Fonts CDN)
- **Monospace Font:** JetBrains Mono (for diagnostic codes, sensor data)
- **Headings:** Font weights 600-700
- **Body Text:** Font weight 400
- **Data/Codes:** Font weight 500, monospace

### Layout System
Use Tailwind spacing units: 2, 4, 6, 8, 12, 16
- Consistent 4-unit gaps between related elements
- 8-unit margins for section separation
- 16-unit padding for major containers

### Component Library

**Navigation:**
- Clean horizontal nav with minimal styling
- Active states using primary blue
- Mobile hamburger menu for responsive design

**Data Displays:**
- Card-based diagnostic panels with subtle shadows
- Tabular data with alternating row colors
- Status indicators using color-coded badges
- Real-time sensor reading widgets

**Forms:**
- Professional input styling with clear focus states
- Dropdown selectors for vehicle makes/models
- File upload areas for diagnostic reports
- Multi-step forms for complex diagnostic workflows

**Dashboard Elements:**
- Grid-based layout for diagnostic cards
- Trend charts showing historical data
- Quick action buttons for common tasks
- Alert/notification system for critical issues

### Visual Treatment
- **Gradients:** Subtle blue gradients (220 85% 25% to 215 60% 45%) for hero sections and important CTAs
- **Shadows:** Minimal, professional shadows for depth
- **Borders:** Clean 1px borders using steel blue
- **Icons:** Heroicons for consistency, automotive-specific icons where needed

### Images
**Hero Section:** Large hero image featuring modern automotive diagnostic equipment or OBD-II scanner in a professional garage setting. Image should convey precision and technology.

**Dashboard:** Small thumbnail images of vehicle types/categories for visual identification.

**No decorative images** - focus on functional imagery that supports the diagnostic workflow.

### Mobile Optimization
- Touch-friendly button sizes (minimum 44px)
- Swipeable diagnostic cards
- Collapsible data tables
- Thumb-zone navigation placement

### Professional Considerations
- High contrast ratios for readability in various lighting
- Minimal animations - only subtle transitions
- Clear information hierarchy for quick scanning
- Error states that don't alarm but inform clearly

This design emphasizes trust, precision, and professional competence - essential qualities for automotive diagnostic software used by technicians and vehicle owners
