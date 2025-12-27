# SVG Mind Map Creation Prompt

Create an SVG mind map on [TOPIC] following these specifications:

## Canvas Setup
- Use viewBox="0 0 1600 1200" for the coordinate system
- Make it responsive with: `style="width: 100%; max-width: 1600px; margin: 20px auto; display: block;"`
- Center point at (800, 600)

## Design Requirements

### Color Scheme
- **Central node**: Pink gradient (#FFB6D9 to #FF8DC7)
- **Box fill**: Light pink (#FFF5FA)
- **Box borders**: Medium pink (#FFB6D9), 2px width
- **Connecting lines**: Medium pink (#FFB6D9), 2px width, 60% opacity
- **Headings**: Bold magenta (#D81B60), 22px
- **Body text**: Dark gray (#555), 18px
- **Central node text**: White, 22px bold

### Layout Structure
1. **Central ellipse** at (800, 600) with rx="140" ry="70"
2. **10-12 topic boxes** radiating around center in circular pattern
3. **Box dimensions**: 
   - Width: 300-380px
   - Height: 160-220px (depending on content)
   - Border radius: rx="10"

### Box Positioning Guidelines
- **Top left quadrant**: x=30-350, y=50-500
- **Left side**: x=30-350, y=300-800
- **Bottom left**: x=200-500, y=1000-1200
- **Top right quadrant**: x=1040-1420, y=50-500
- **Right side**: x=1160-1420, y=400-900
- **Bottom center**: x=660-820, y=800-1200

### Text Formatting Rules
1. **Box heading**: 
   - font-size="22", font-weight="bold", fill="#D81B60"
   - Position: 30-35px from box top
2. **Content lines**:
   - font-size="18", fill="#555"
   - Line spacing: 25px between lines
   - Start first line 30-40px after heading
3. **Center all text** using text-anchor="middle"

### Drawing Order (Important!)
1. First: Define gradients in `<defs>`
2. Second: Draw all connecting lines
3. Third: Draw central node
4. Fourth: Draw all boxes with their text

### Content Structure Per Box
```svg
<rect x="X" y="Y" width="320" height="190" rx="10" fill="#FFF5FA" stroke="#FFB6D9" stroke-width="2"/>
<text x="CENTER_X" y="Y+35" text-anchor="middle" font-size="22" font-weight="bold" fill="#D81B60">Heading</text>
<text x="CENTER_X" y="Y+65" text-anchor="middle" font-size="18" fill="#555">• Point 1</text>
<text x="CENTER_X" y="Y+90" text-anchor="middle" font-size="18" fill="#555">• Point 2</text>
<text x="CENTER_X" y="Y+115" text-anchor="middle" font-size="18" fill="#555">• Formula or fact</text>
```

## Topic Requirements for [SUBJECT]

Include these main branches:
1. Definition/Introduction
2. Key formulas and equations
3. Units and measurements
4. Properties and characteristics
5. Related concepts
6. Practical applications
7. Important laws/principles
8. Diagrams or symbols (if applicable)

## Content Guidelines
- Use bullet points (•) for list items
- Include formulas in appropriate notation
- Keep text concise (max 6-7 lines per box)
- Add SI units where relevant
- Use mathematical symbols: ², ³, ₁, ₂, ∝, ×, ÷, π, Ω, etc.

## Line Connections
- Connect center (800, 600) to approximate center of each box
- Calculate box center: (box_x + width/2, box_y + height/2)
- Format: `<line x1="800" y1="600" x2="BOX_CENTER_X" y2="BOX_CENTER_Y" stroke="#FFB6D9" stroke-width="2" opacity="0.6"/>`

## Quality Checklist
✓ All text is readable with proper spacing (25px minimum)
✓ No boxes overlap
✓ Lines connect center to all boxes
✓ Central concept is clearly visible
✓ Color scheme is consistent
✓ All formulas use proper notation
✓ Box sizes accommodate all content
✓ Proper hierarchy: heading → details → formulas

## Example Output Format
Generate complete SVG code starting with:
```xml
<svg viewBox="0 0 1600 1200" xmlns="http://www.w3.org/2000/svg" style="width: 100%; max-width: 1600px; margin: 20px auto; display: block;">
  <defs>
    <!-- gradients -->
  </defs>
  <!-- lines -->
  <!-- central node -->
  <!-- topic boxes -->
</svg>
```

## Example Box Positions (for 12 boxes)

### Left Side Boxes
- **Top Left 1**: x=30, y=50, width=320, height=180
- **Top Left 2**: x=600, y=170, width=320, height=160
- **Left Middle**: x=30, y=310, width=320, height=200
- **Left Lower**: x=30, y=580, width=320, height=190
- **Component/Diagram**: x=30, y=790, width=380, height=220
- **Bottom Left**: x=220, y=1015, width=300, height=180

### Right Side Boxes
- **Top Right 1**: x=1270, y=50, width=320, height=160
- **Top Right 2**: x=1040, y=205, width=300, height=160
- **Right Middle**: x=1270, y=450, width=320, height=190
- **Right Lower**: x=1270, y=710, width=320, height=190
- **Bottom Right**: x=1160, y=970, width=320, height=200

### Center Bottom Boxes
- **Electric Power/Main Concept**: x=660, y=820, width=320, height=160
- **Related Concept**: x=660, y=1010, width=320, height=190

## Spacing Guidelines
- Minimum gap between boxes: 20px
- Vertical spacing between stacked boxes: 20-30px
- Horizontal spacing from edges: 30px minimum
- Keep central area (600-1000, 500-700) clear for central node

## Tips for Success
1. Start with a rough layout on paper
2. Place central node first
3. Distribute boxes evenly around the center
4. Work outward from center in layers
5. Adjust spacing to prevent overlaps
6. Test text readability at different zoom levels
7. Ensure all mathematical notation renders correctly
8. Preview on different screen sizes

---

**To use this prompt:**
1. Replace `[TOPIC]` and `[SUBJECT]` with your specific subject
2. Add any topic-specific requirements
3. Feed it to Claude, GPT-4, or any capable LLM
4. Review and adjust positioning as needed
5. Test responsiveness and readability

**Example Usage:**
"Now create an SVG mind map for: **Chemical Reactions - Types and Properties**"

