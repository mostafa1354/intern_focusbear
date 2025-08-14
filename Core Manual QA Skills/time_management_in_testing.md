# ⏳ Deciding How Long to Spend on Testing an Issue

## Role Context

Manual Q&A Intern at Focus Bear.  
My role involves testing a variety of issues, from small visual tweaks to high-priority bugs, while managing my time effectively to meet deadlines.

---

## 🔍 Research & Learn

### Factors Influencing Testing Duration

- **Complexity**: More complex features or bugs require deeper exploration.
- **Risk**: Higher risk to users or core functionality demands more thorough testing.
- **Priority**: Critical issues should take precedence over minor defects.
- **Deadlines**: Testing scope may be reduced if release timelines are tight.
- **Reproducibility**: Intermittent bugs may require more investigation to confirm.

---

### Techniques for Prioritising Testing Efforts

- **Risk-Based Testing**: Focus on areas most likely to cause severe issues if they fail.
- **Exploratory Timeboxing**: Allocate a fixed time (e.g., 30 minutes) for open-ended investigation.
- **Impact Assessment**: Consider the number of users affected and potential business consequences.

---

### Understanding “Good Enough” Testing

- Testing is sufficient when:
  - Core functionality is verified.
  - High-risk areas are covered.
  - No major regressions are found.
  - Remaining risks are documented and accepted by stakeholders.

---

### Balancing Depth vs. Speed

- Deep testing for **high-impact, high-risk** issues.
- Faster validation for **low-impact, low-risk** fixes.
- Use past bug patterns and heuristics to decide how deep to go.

---

## 📝 Reflection

### Approach for Different Issues

- **Small UI Bug**: Quick visual verification, confirm change across affected devices/screens, minimal exploratory testing.
- **Critical Login Issue**: Deep investigation, test across all login methods, explore edge cases (incorrect credentials, network loss), regression test related features.

---

### Deciding What to Test First With Limited Time

1. Start with **highest impact and highest risk** areas.
2. Test **most used workflows** first.
3. Focus on issues that could **block users or releases**.

---

### Risks of Over-Testing

- Delays in release cycles.
- Reduced coverage of other pending issues.
- Wasted time on low-value scenarios.

### Risks of Under-Testing

- Missed critical bugs.
- User frustration and potential loss of trust.
- Increased post-release fixes and hotfixes.

---
