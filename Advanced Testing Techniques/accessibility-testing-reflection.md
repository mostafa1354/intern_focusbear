# 🎨 How to Test Accessibility

## Role Context

Manual Q&A Intern at Focus Bear.  
Many Focus Bear users have ADHD, Autism, or other cognitive and physical challenges. My role includes ensuring the app remains accessible and usable for all, following WCAG standards and accessibility best practices.

---

## 🔍 Research & Learn

### WCAG Overview

- **Definition**: WCAG (Web Content Accessibility Guidelines) is the global standard for making digital content accessible to people with disabilities.
- **Four Key Principles (POUR)**:
  1. **Perceivable** – Information and UI must be presented in ways users can perceive.
  2. **Operable** – Navigation and controls must be usable by all.
  3. **Understandable** – Information and operation must be clear and predictable.
  4. **Robust** – Content must work well with assistive technologies.

### Screen Readers & Testing

- **Examples**:
  - NVDA (Windows)
  - VoiceOver (macOS/iOS)
  - TalkBack (Android)
- **Testing Approach**:
  - Navigate through Focus Bear without looking at the screen.
  - Verify that all elements have descriptive labels and reading order is logical.
  - Ensure interactive elements are clearly announced (buttons, links, toggles).

### Common Accessibility Issues

- Missing or incorrect `alt` text on images.
- Low contrast between text and background.
- Poor focus visibility.
- Inconsistent or illogical tab order.
- Elements not reachable via keyboard.
- Complex layouts without clear headings.

### Keyboard Navigation & Focus Management

- Check that all interactive elements can be reached using `Tab` and activated with `Enter` or `Space`.
- Verify focus indicators are visible and move logically.
- Test for "keyboard traps" (where focus gets stuck).

### Accessibility Testing Tools

- **Automated Checks**: Lighthouse, Axe DevTools, WAVE.
- **Manual Verification**: Screen readers, keyboard navigation, contrast checkers.

---

## 📝 Reflection

### How I Would Test Focus Bear with a Screen Reader

- Enable NVDA or VoiceOver and navigate through the app entirely by keyboard or swipe gestures.
- Check that each element is announced correctly with descriptive text.
- Confirm reading order follows the intended visual flow.
- Validate that all essential features are usable without relying on sight.

### Accessibility Barriers for ADHD or Autism Users

- Overly cluttered UI or distracting animations.
- Inconsistent navigation patterns.
- Lack of clear instructions or feedback after actions.
- Complex forms without progressive disclosure.

### Advocating for Fixing Accessibility Issues

If a developer says, _"this doesn't impact most users"_, I would:

- Explain that accessibility improvements benefit **all** users, not just those with disabilities.
- Highlight legal and ethical obligations to follow WCAG.
- Share examples of how accessibility improvements improve usability for a broader audience.
- Emphasize Focus Bear’s mission to support neurodivergent individuals.

---
