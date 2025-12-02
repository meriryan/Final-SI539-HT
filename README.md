# Appendix

Resources and references used in completing the Harmonic Thinking final project.

---

## Development Tools

- **Chrome DevTools** for layout debugging, CSS testing, and responsive breakpoint previews
- **WAVE accessibility checker** for structural errors, contrast validation, and ARIA verification
- **WebAIM Contrast Checker** for manual color contrast ratio calculations

---

## AI Assistance

Claude was used for code review, clarifying logic, restructuring code organization, and adding comments:

> Anthropic. Claude. Accessed 2024. [https://claude.ai](https://claude.ai)

### Prompts Used:

**Layout & CSS:**
- "Why is my grid layout collapsing at smaller viewports and how can I fix the column sizing?"
- "What is causing extra white space at the bottom of my page when I use min height with flexbox?"
- "My section spacing looks inconsistent across pages. Can you help me reorganize my margin and padding rules?"
- "Can you refactor my CSS to reduce repeated code across the three pages?"
- "How do I create overlapping color blocks using absolute positioning? I want a blocky, geometric look."

**CSS Gradients & Visual Design:**
- "Can you help me create a layered radial gradient background that looks textured but still keeps text readable?"
- "Can you explain what each parameter in this gradient is doing? I want to understand how to control the shape better."
- "My color palette is failing contrast checks but I don't want to lose the vibrant look. Can you suggest adjusted values that still feel bold?"

**Accessibility:**
- "My focus states are invisible on dark backgrounds. How can I make them visible while keeping my color palette?"
- "What's the difference between tabindex='0' and adding ARIA roles? Which should I use for section navigation?"

**JavaScript:**
- "I want to add a back-to-top button with JavaScript. Can you walk me through how createElement and appendChild work?"
- "Can you add comments to my JavaScript explaining what each function does?"

**Code Organization:**
- "Can you help me organize my CSS file with clear section comments and group related styles together?"

---

## Documentation & References

- **MDN Web Docs** for CSS properties (Grid, Flexbox, clamp(), custom properties) and JavaScript DOM methods
- **CSS-Tricks** for visual guides on Grid and Flexbox layout
- **W3C WCAG 2.1 Guidelines** for accessibility requirements and success criteria
- **WebAIM** for accessibility best practices and skip link implementation
- **Adobe Fonts (Typekit)** for Futura PT web font integration

---

## Course Materials

- **SI 539 lecture slides and assignments** for foundational HTML/CSS structure
- **SI 539 accessibility module** for WCAG compliance strategies
- **Client project from SI 539** as reference for responsive breakpoint patterns
