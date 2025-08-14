# 🔍 Handling Hard-to-Reproduce Bugs

## Role Context

Manual Q&A Intern at Focus Bear.  
In my role, I may encounter bugs that don’t occur consistently. These require extra investigation and thorough documentation to help developers reproduce and fix them.

---

## 🔍 Research & Learn

### Common Causes of Intermittent Bugs

- **Timing issues** (race conditions, delays in API responses).
- **Device-specific differences** (OS version, hardware capabilities).
- **Network instability** (slow or dropped connections).
- **State-dependent scenarios** (only after certain actions or sequences).
- **Memory leaks or resource exhaustion** (after prolonged usage).

### Tools to Capture Debug Information

- **Debug logs** (console logs, app log files).
- **Network monitoring tools** (Chrome DevTools, Charles Proxy, Wireshark).
- **Crash reporting tools** (Sentry, Firebase Crashlytics).
- **Screen recording tools** to capture exact steps and behavior.

### Strategies to Make Bugs More Reproducible

- Reproduce in a clean environment with minimal variables.
- Try on different devices, browsers, or network conditions.
- Document **exact steps** leading to the issue.
- Keep a record of timestamps and environment details.
- Increase logging verbosity for the affected module.

### Handling "Cannot Reproduce" Issues

- Provide all collected details, including logs, screenshots, and recordings.
- Suggest possible conditions under which the bug appears.
- Collaborate with developers to add temporary debug logs or flags.
- Retest periodically to see if conditions change.

---

## 📝 Reflection

### How I Would Report an Occasional Bug

- Include exact reproduction steps (even if success rate is low).
- Document the environment (OS, device, app version, network condition).
- Attach relevant logs, screenshots, and screen recordings.
- Mention the frequency and any observed patterns.

### If a Developer Marks a Bug as "Not Reproducible"

- Review my reproduction steps and confirm environment details.
- Ask if additional logging can be added to track the issue.
- Offer to pair-test with the developer.
- Keep the issue open for monitoring if it still impacts users.

### Tools & Techniques for Capturing Extra Details

- Use **screen recording** to capture rare events.
- Enable **debug logging** in the affected module.
- Test under **simulated network or device conditions**.
- Use **error tracking tools** like Firebase Crashlytics to collect stack traces.

---
