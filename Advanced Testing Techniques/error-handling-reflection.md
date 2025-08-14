# 💥 Testing Error Handling & Edge Cases

## Role Context

Manual Q&A Intern at Focus Bear.  
In my role, I need to ensure that Focus Bear works reliably not only in normal use but also under unusual, extreme, or unexpected conditions.

---

## 🔍 Research & Learn

### Boundary Value Analysis

- **Definition**: A testing technique that focuses on values at the edges of input ranges (e.g., minimum, maximum, just inside/outside limits).
- **Usefulness**: Helps detect defects that occur at the “boundaries” where developers may not have accounted for edge conditions.

### Common Edge Cases for QA

- **Forms**: Empty inputs, excessively long text, invalid formats (e.g., wrong email syntax), special characters/emojis.
- **Authentication**: Wrong passwords, expired links, multiple failed login attempts.
- **App Flows**: Skipping steps, back button behavior, simultaneous actions.

### Testing Network Failures

- Simulate offline mode by disabling Wi-Fi/data mid-action.
- Test on slow connections using network throttling tools.
- Check if the app retries gracefully or shows meaningful error messages.

### Unexpected Input & Invalid Data

- Inputting symbols, SQL keywords, or unusual characters.
- Pasting large amounts of data into fields.
- Providing unsupported file formats.

### Testing Error Messages

- Ensure messages are **clear**, **specific**, and **user-friendly**.
- Avoid technical jargon—messages should guide the user on how to fix the issue.
- Consistency in style, tone, and placement.

---

## 📝 Reflection

### Edge Cases That Could Break Focus Bear’s Onboarding Flow

- Entering an extremely long name or email.
- Skipping required steps by navigating backwards or closing the app.
- Attempting to sign up with an already registered email.
- Poor internet connection during the onboarding tutorial.

### Expected Behavior if the App Fails Midway Through a Critical Action

- Save progress so the user can resume later.
- Display a clear message explaining what happened and how to proceed.
- Avoid data loss—store locally until the action can be retried.

### Testing for Network Instability

- Toggle network on/off during key actions (e.g., sign-up, habit creation).
- Use 3G/slow network simulation to check if UI remains responsive.
- Ensure actions either retry automatically or prompt the user to retry manually.

---
