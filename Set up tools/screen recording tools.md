# 🎥 Screen Recording Tools – Reflection

## 🎯 Goal

Understand how to capture high-quality screen recordings and screenshots for bug reporting.

---

## ❓ Why is this important?

In QA work, clear and well-structured visual evidence helps developers quickly understand and reproduce issues. Screen recordings and annotated screenshots provide context beyond text descriptions, reducing back-and-forth communication and speeding up bug fixes.

---

## 🔍 Research & Learn

**Best free screen recording tools for Windows/macOS:**

- **Windows:** Xbox Game Bar (built-in), OBS Studio, ShareX, ScreenRec
- **macOS:** QuickTime Player (built-in), OBS Studio, Loom, CleanShot X

**Best paid tools:**

- Camtasia (Windows/macOS) – advanced editing and annotations
- Snagit (Windows/macOS) – quick capture and lightweight editing
- Loom (Business Plan) – shareable links and team collaboration features

**Recording a specific part of the screen:**

- Most tools (OBS, ShareX, Loom, CleanShot X) allow selecting a **custom region** or **specific application window** before recording.
- On macOS, press **Shift + Command + 5** to select a region for screen capture/recording.
- On Windows, use Snipping Tool or ShareX for partial captures, or set OBS to “Window Capture” mode.

**Best practices for including screen recordings in bug reports:**

- Keep the recording short and focused (30–90 seconds if possible).
- Start with the bug in its initial state, then show steps to reproduce.
- Highlight or zoom in on key actions if your tool supports it.
- Name the file descriptively (e.g., `login-error-2025-08-14.mp4`).
- Use consistent resolution and frame rate for clarity (1080p, 30fps is ideal).

**Reducing file size without losing quality:**

- Export in **MP4 (H.264)** format for high compression with good clarity.
- Lower frame rate to 30fps if the bug doesn’t require high motion detail.
- Use compression tools like **HandBrake** or built-in export settings in recording apps.

---

## 📝 Reflection

**Key information to include in a bug recording:**

1. **Title/Context:** Briefly state the bug (e.g., “Settings page crashes after changing language”).
2. **Steps to Reproduce:** Show each click/interaction leading to the bug.
3. **Expected vs Actual Result:** Mention what should happen vs what happened.
4. **Environment Details:** Include app version, OS version, and device type.

**Ensuring no sensitive information is shared:**

- Close unrelated apps and tabs before recording.
- Hide personal details (emails, passwords, addresses).
- Use blur tools in Snagit, Camtasia, or editing software before sharing.

**Capturing bugs that occur during fast interactions:**

- Use a tool with high frame rate capture (60fps) for smooth playback.
- Slow down the video in editing software to highlight the moment.
- Provide a **step-by-step written description** alongside the video for clarity.

---
