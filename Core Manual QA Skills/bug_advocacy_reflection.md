# 📢 Core Manual QA Skills – Bug Advocacy

## Role Context

Manual Q&A Intern at Focus Bear.  
My role involves identifying, documenting, and communicating bugs in a way that helps developers quickly understand, reproduce, and fix them.

---

## 🔍 Research & Learn

### What Makes a Good Bug Report vs. a Bad One

**Good Bug Report:**

- Clear, concise title describing the issue.
- Detailed reproduction steps.
- Actual vs. expected results.
- Relevant environment info (OS, browser, app version).
- Evidence: screenshots, logs, videos.
- Impact explained (why it matters to the user/business).

**Bad Bug Report:**

- Vague titles (“Feature not working”).
- Missing steps or unclear reproduction path.
- No environment details.
- No evidence.
- Lacks context on why it’s important.

---

### Details to Include for a Clear & Actionable Bug Report

- **Title**: Short but descriptive.
- **Environment**: Device, OS, browser/app version.
- **Steps to Reproduce**: Numbered list from a clean starting point.
- **Expected Result**: What should happen.
- **Actual Result**: What happened instead.
- **Attachments**: Screenshots, logs, recordings.
- **Severity**: Impact level on functionality.
- **Priority**: Importance/urgency from a business/user perspective.

---

### Making a Bug Easier to Reproduce

- Use fresh test accounts or reset to a known state.
- Minimize the steps to the exact trigger.
- Isolate variables (browser type, network speed, account settings).
- Provide sample test data if applicable.

---

### Bug Severity vs. Bug Priority

- **Severity**: How badly the bug impacts functionality (Critical, Major, Minor, Cosmetic).
- **Priority**: How urgently the bug should be fixed based on business or release needs.
- Example: A cosmetic typo (Low Severity) could be High Priority before a big release.

---

## 📝 Reflection

### Reporting a UI Glitch vs. Critical Login Failure

- **UI Glitch**:

  - Severity: Minor
  - Include screenshots highlighting the affected area.
  - Suggest fix only if it impacts usability or branding.
  - May have lower priority unless it affects accessibility.

- **Critical Login Failure**:
  - Severity: Critical
  - Provide full reproduction steps, error messages, and environment details.
  - Attach logs and screen recordings of the failed attempt.
  - Mark as highest priority and notify the team immediately.

---

### Advocating for a Bug Dismissed as "Not Important"

1. Provide concrete examples of how it affects user experience or business outcomes.
2. Show reproduction consistency or frequency.
3. Link it to potential revenue loss, brand image issues, or accessibility compliance.
4. Share customer feedback if available.

---

### How Screenshots, Logs, and Recordings Improve Bug Reports

- **Screenshots**: Provide immediate visual confirmation of the problem.
- **Logs**: Reveal technical details (error codes, stack traces) that speed up debugging.
- **Recordings**: Show the entire reproduction flow, helping developers see the sequence and timing of actions.

---
