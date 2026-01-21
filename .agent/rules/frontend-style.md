---
trigger: always_on
---

When writing CSS code, ALWAYS use percentage (%) units instead of pixels (px) for:
- Width and height properties
- Padding and margin (when possible)
- Positioning (top, left, right, bottom)
- Font sizes (use rem or em, not px)

Exceptions where px can be used:
- Border width
- Box shadows
- Very small fixed values (< 5px)

Example of correct approach:
- width: 100%;
- padding: 5%;
- font-size: 1.2rem;
- margin: 2% 5%;

Example of incorrect approach:
- width: 500px;
- padding: 20px;
- font-size: 16px;

This rule ensures responsive design and better scalability across different screen sizes. Apply this rule to all CSS code generation unless explicitly told to use pixels.