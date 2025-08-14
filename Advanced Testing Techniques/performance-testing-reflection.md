# ⚡ Testing Performance & Responsiveness

## Role Context

Manual Q&A Intern at Focus Bear.  
In my role, I help ensure the app not only works functionally but also delivers a smooth and fast user experience across different devices and network conditions.

---

## 🔍 Research & Learn

### Key Factors That Impact App Performance

- **CPU Usage** – Heavy processing can slow down the app, especially on low-end devices.
- **Memory (RAM)** – High memory usage can cause lag or crashes.
- **Network Speed & Latency** – Slow or unstable internet can delay loading and syncing.
- **Database Queries** – Inefficient queries can create bottlenecks.
- **Rendering & UI Updates** – Poorly optimized front-end rendering can cause stutter or delays.

### Measuring App Speed & Responsiveness

- Track load times for pages/screens.
- Measure response time for user actions (e.g., button clicks, data fetch).
- Record frame rates for smoothness of animations.

### Tools for Basic Performance Testing

- **Chrome DevTools** – Performance tab, network throttling.
- **Lighthouse** – Page speed and performance audits.
- **Mobile Profiling Tools** – Android Profiler, Xcode Instruments.
- **Network Simulation Tools** – Throttle network to test slow internet scenarios.

### Common Performance Issues

- **Web Apps** – Slow API responses, unoptimized images, excessive scripts.
- **Mobile Apps** – High memory usage, poor background process handling, laggy animations.

### Testing Under High Load or Low Resources

- Simulate low RAM by running background apps.
- Throttle CPU and network speed using developer tools.
- Test on older devices and budget phones.
- Use offline or intermittent connectivity scenarios.

---

## 📝 Reflection

### How I Would Test Focus Bear’s Performance on an Older Device or Slow Internet

- Use network throttling to simulate 3G/low-bandwidth conditions.
- Test app startup and navigation speed on a 3–4-year-old device.
- Monitor for crashes, loading delays, and unresponsive screens.

### If a User Reports the App Feels Slow

1. **Reproduce** the scenario on similar devices/networks.
2. **Profile** performance using Chrome DevTools or mobile profilers.
3. **Check logs** for slow API calls or resource-heavy operations.
4. **Document findings** with exact timing metrics for developers.

### Performance Optimizations for Low-End Devices

- Reduce unnecessary animations or visual effects.
- Optimize image sizes and formats.
- Implement lazy loading for heavy content.
- Cache frequently accessed data to reduce network calls.

---
